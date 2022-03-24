# fieldasr

https://padlite.spline.de/p/nis_fieldasr

## Article

The [following paper](https://docs.google.com/document/d/1u0Ib7lIB-0OhClWviuIMvTLUIP2J9GLuwd6T9Z4J63M/edit?usp=sharing) presents a project focused on the research and creation of a new Automatic Speech Recognition (ASR) and Text to Speech (TTS) system based in the Chukchi language. The aim of this is to develop a system that makes the language more accessible to speakers of Chukchi - such as annotating subtitles on videos and movies, providing more accessible data for research and analysis, or the creation of chat-bots for online users. This system should consist of; an acoustic model for receiving an audio signal fragment and which gives the probability of various phonemes based on the fragment analyzed; a language model for determining which suggestions are more or less likely; and a decoder which will determine the most likely prediction. Predictive automatic speech recognition models already exist and are a popular focus in the realm of Natural Language Processing, however, the most challenging adversaries are low-resource languages due to extreme data deficits. 

This project is centered around a multi-step research process. Initially, we began by analyzing the Chukchi language from a linguistic perspective, but for the sake of clarity regarding motivations for making this system, it also must be looked at from a cultural and sociolinguistic perspective. What is known about the language, are there any cultural influences within the language, why is such a system necessary, and so on. Once there was extensive understanding of the subject at hand, the next step would be finding data that is usable. For this project, this included broadcasts from a Russian-based Chukchi radio station, videos and lessons from YouTube, written translations of the Bible, and the Higher School of Economics’ set of Chukchi-based corpora known as Chuklang. Once enough data is collected, there then comes the task of cleaning it. This included labeling and segmenting audio data for training, cleaning and filtering out unnecessary symbols (mainly Russian) from text, and determining which data would be used for pre-training and which would be used for testing the resultant model. Once enough data has been collected and cleaned for our model, we sample and train various models to understand how they process data. Additionally, we must try various encoders to understand how well they clean out noise and extra acoustic audio. Extra research must be conducted in order to compare models designed for both high- and low-resource languages. Various designs and tools for training ASR models include VQ-VAE, XLSR, the toolkit Kaldi, wav2vec, and more. The intended result of this project is an automatic speech-recognition system that can seamlessly work with Chukchi and provides us with the potential to be used for other low-resource languages. 

**If our work is in any way useful to you in your research, please refer to this repository.**

## Data

The authors of the project have compiled a [large list of data sources for the Chukchi language](https://github.com/ftyers/fieldasr/edit/main/DATA.md): 
- video converted to WAV format and audio in WAV format. Duration of all unannotated data - 17:48:05. Duration of all annotated data - 3:46:18;
- text corpus is composed of 112,719 sentences, and 2,068,273 words.

## License and Copyright

All the rights to the code belong to the respective authors, mentioned in the [attached notebook](notebook/XLSR.ipynb). Minimal changes were made to adapt the existing code to the data collected by the team of this project.\
All the rights to the [text data](data/text_corpus.txt), collected from open sources and included in this repository for educational and scientific purposes, belong to the respective authors, as well.

Everything else is licensed under the [MIT license](LICENSE.md)

## About us

2020-2022 Master's students of Higher School of Economics (Russia, Moscow) in "Computational Linguistics" *Emil Nadimanov*, *Anastasia Safonova*, *Tatiana Yudina* and Master's student in "Linguistic Theory and Language Description" *Sidney Davenport*. Assistant Professor in Linguistics of Indiana University Bloomington (Indiana, USA) and Higher School of Economics (Moscow, Russia)  *Francis Tyers*. 
Scientific advisors: Visiting faculty member of Higher School of Economics (Russia, Moscow) *Serikov Oleg*, research assistant of Indiana University Bloomington (Indiana, USA) *Anurag Kumar*, graduate student of Indiana University Bloomington (Indiana, USA) *Anastasia Kuznetsova*.
