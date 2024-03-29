# Chukchi Datasources

## Audio in WAV format

Duration of all unannotated data - 17:48:05

Duration of all annotated data - 3:46:18

Total duration of all audio data - 21:34:23

All received audio was cut into small fragments. Sometimes it was possible to cut by pauses, so as not to cut off parts of words that may be important for ASR model training. In this case, the Python libraries [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) and [pydub](https://github.com/jiaaro/pydub) were used. Sometimes it was impossible to cut by pauses (for example, if there was music playing in the background), if this was the case, then the files were cut by 5 minutes.


### Radio ‘Purga’ (2 hours 32 minutes)
One of the main sources of high-quality annotated data was the Chukchi radio station [Radio “Purga”](https://radiopurga.ru/), which has a special feature at their station in which they report news in Chukchi on a regular (almost daily) basis. These audio recordings were segmented by sentences, and labeled using the software ELAN.

### Bible Audio (3 hours 36 minutes 52 seconds)
The resource [Bible.is](https://www.faithcomesbyhearing.com/audio-bible-resources/bible-is) contains chapters from the Bible in a variety of languages from around the world, including Chukchi. Some Bible chapters do have a text annotation (for example, The Gospel of Luke), and some don’t (The Book of Jonah).

### Chuklang Corpora (1 hour 14 minutes 18 seconds)
The [Chuklang Corpora](https://chuklang.ru/) was created by professors and students of the National Research University - Higher School of Economics in Moscow, Russia, during the linguistic expeditions to the village of Amguema in the Iultinsky District of the Chukotka Autonomous Okrug. 

### Fairy tales (11 minutes 20 seconds)
* [Пипиӄылгын ынкъам рэӄокалгын (Сказка "Мышка и лисица")](https://drive.gybka.com/song/14507495/Antonina_Kymytvaal_-_Pipi_ylgyn_ynkam_re_okalgyn_Skazka_Myshka_i_lisica/)
* [Вэтлы ынкъам мэлёталгык'ай (Сказка "Ворон и зайчик")](https://drive.gybka.com/song/20362227/Antonina_Kymytvaal_-_Vetly_ynkam_melyotalgyk_aj_Skazka_Voron_i_zajchik/)
* [И'ны, вэтлы ынкъам кытэпалгын (Сказка "Волк, ворон и горный баран")](https://drive.gybka.com/song/27930653/Antonina_Kymytvaal_-_I_ny_vetly_ynkam_kytepalgyn_Skazka_Volk_voron_i_gornyj_baran/)
* [Мэлёталгык’ай ынкъам кэлы (Сказка "Зайчик и чёрт")](https://drive.gybka.com/song/36902558/Antonina_Kymytvaal_-_Melyotalgyk_aj_ynkam_kely_Skazka_Zajchik_i_chyort/)

### Video (14 hours 11 minutes 13 seconds)
All videos found were then converted into WAV format

#### Channel "ARCTIC MEGAPEDIA" (4 hours 55 minutes 29 seconds)
* [nuvano2](https://www.youtube.com/watch?v=VVul1mAuiq8)
* [Выквырагтыргыргына Л.С.](https://www.youtube.com/watch?v=7_0g6RscfWw&t)
* [Нувано В.Н. г Анадырь](https://www.youtube.com/watch?v=EHZMdEw0s8s&t)
* [Печетегина Т.А. г Анадырь](https://www.youtube.com/watch?v=lHpheP3MQqU)
* [Печетегина Т.А. г Анадырь](https://www.youtube.com/watch?v=yfxiyIBjDdo&t)
* [Ранаврольтыну Г.И., г. Анадырь](https://www.youtube.com/watch?v=tGwSlBPCvO8&t)
* [teleuroki chukot 01](https://www.youtube.com/watch?v=V5q6SpQvOjA&t)
* [teleuroki chukot 02](https://www.youtube.com/watch?v=WI6p_WwzFII&t)
* [teleuroki chukot 03](https://www.youtube.com/watch?v=ZABWiEwC2rs&t)
* [teleuroki chukot 04](https://www.youtube.com/watch?v=seJRqDaDtjQ)
* [teleuroki chukot 05](https://www.youtube.com/watch?v=Y0DKtJ_XQuY)
* [teleuroki chukot 06](https://www.youtube.com/watch?v=MYE7riNELgU)
* [teleuroki chukot 08](https://www.youtube.com/watch?v=0ZtulT0e14k)
* [teleuroki chukot 09](https://www.youtube.com/watch?v=4fpYjQIw6ME)
* [teleuroki chukot 10](https://www.youtube.com/watch?v=asnRCEI4ygg)
* [teleuroki chukot 11](https://www.youtube.com/watch?v=MryzWeCpVD8)
* [teleuroki chukot 12](https://www.youtube.com/watch?v=KlK1Hj51niA)
* [teleuroki chukot 13](https://www.youtube.com/watch?v=zi2Amw2kelU)
* [teleuroki chukot 14](https://www.youtube.com/watch?v=-9SD9vpJWkU)
* [teleuroki chukot 15](https://www.youtube.com/watch?v=ykZV_hzsMdA)
* [teleuroki chukot 16](https://www.youtube.com/watch?v=OmppoLPiTjA)
* [teleuroki chukot 17](https://www.youtube.com/watch?v=KpNTexqOgA8)
* [teleuroki chukot 18](https://www.youtube.com/watch?v=jl8Afqfx4v8)
* [teleuroki chukot 19](https://www.youtube.com/watch?v=EmRr-tpqAv8)
* [teleuroki chukot 20](https://www.youtube.com/watch?v=gkX2GJmR8VE)
* [teleuroki chukot 21](https://www.youtube.com/watch?v=9aEqHoYrv_0)
* [teleuroki chukot 22](https://www.youtube.com/watch?v=dvcQ0vQOqEo)
* [teleuroki chukot 24](https://www.youtube.com/watch?v=7mmOlqmTRrg)
* [teleuroki chukot 25](https://www.youtube.com/watch?v=cq8bK8xjSn0)
* [teleuroki chukot 26](https://www.youtube.com/watch?v=pAUXYTsyfAE)
* [teleuroki chukot 27](https://www.youtube.com/watch?v=nlAJUVFl1i8)
* [teleuroki chukot 28](https://www.youtube.com/watch?v=9Pz9o8fp70Y)
* [teleuroki chukot 29](https://www.youtube.com/watch?v=BsxTaD5t0OQ)
* [teleuroki chukot 30](https://www.youtube.com/watch?v=dypEoaf2ez0)
* [teleuroki chukot 31](https://www.youtube.com/watch?v=3K_tirFrWts)
* [teleuroki chukot 32](https://www.youtube.com/watch?v=dJGcYkO9QOw)
* [teleuroki chukot 33](https://www.youtube.com/watch?v=T4hKNqJRfHU)
* [teleuroki chukot 34](https://www.youtube.com/watch?v=AzYzNgNjizI)
* [teleuroki chukot 35](https://www.youtube.com/watch?v=H01UU_2hNTo)
* [teleuroki chukot 36](https://www.youtube.com/watch?v=2wANvN8yz_s)
* [teleuroki chukot 37](https://www.youtube.com/watch?v=jADKxbSobtU)
* [teleuroki chukot 38](https://www.youtube.com/watch?v=9cMeCYAvb14)
* [teleuroki chukot 39](https://www.youtube.com/watch?v=ADj5HfeHqFU)
* [teleuroki chukot 40](https://www.youtube.com/watch?v=Rq48NFTAABE)

#### Channel "Александр Куцкий" Project "Вэтгав. Уроки чукотского" (7 hours 50 minutes 54 seconds)
* [Вступительное слово к проекту "Вэтгав. Уроки чукотского" Михаила Зеленского и Антонины Кергитваль.](https://www.youtube.com/watch?v=TgyiFmizFac&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=1)
* [Урок №1. Тема «Гымнин нынны» («Моё имя»). Педагог Выквырагтыргыргына Лариса.](https://www.youtube.com/watch?v=FFApYFCuhWM&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=4)
* [Урок №2. Тема «Ԓьовыԓгыгыргын» («Встреча»). Педагог Грачёва Вера Алексеевна.](https://www.youtube.com/watch?v=Y8JvOojESFc&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=3)
* [Урок №3. Тема «Йъаяӄӄай» («Чаечка»). Педагог Гыргольнаут Ирина Григорьевна.](https://www.youtube.com/watch?v=BkT0S-lHA1U&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=5)
* [Урок №4. Тема «Рооԓӄыԓтэ рыркатъоԓгыпы ынкъам аӈӄатъоԓгыпы». Педагог Илены Ирина Николаевна.](https://www.youtube.com/watch?v=6axOZZKLDzc&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=6)
* [Урок №5. Тема «ЭЭК МОРЫГВАГЫРГЫК». Педагог Кайсагалиева Ирина Михайловна.](https://www.youtube.com/watch?v=jCk3MqoH1i8&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=7)
* [Урок №6. Тема «Мини-сказка «Уунъыӄэй» («Ягодка»). Педагог Кергитваль Антонина Николаевна.](https://www.youtube.com/watch?v=rAfZBuVHvr4&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=10)
* [Урок №7. Тема «Песня «Вэԓвыӄэгти» («Воронята»). Педагог Кергитваль Антонина Николаевна.](https://www.youtube.com/watch?v=gcVsCyZl9QE&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=11)
* [Урок №8. Тема «РЫԒГЫГЫРГЫН» («Счёт»). Педагог Королёва Лидия Ивановна.](https://www.youtube.com/watch?v=Sxmmf8JSBac&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=8)
* [Урок №9. Тема «Выргыргын [и], буква И. Выргыргын [и'], буква И'». Педагог Кочетагина Ева Николаевна.](https://www.youtube.com/watch?v=UGK5NiUGKcA&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=12)
* [Урок №10. Тема «ЭВИРЪЫТ» («Одежда»). Педагог Кытгиргина Кира Михайловна.](https://www.youtube.com/watch?v=QQyFd0uF4P4&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=9)
* [Урок №11. Тема «Чиниткинэт грэпыт тавайваамкэн эмнуӈыԓьин». Педагог Нотатынагиргина Галина Ивановна.](https://www.youtube.com/watch?v=fQcmU7xFWhQ&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=14)
* [Урок №12. Тема «Стихотворение «Ытԓянъёгты» («Братишке»). Педагог Тевлявье Елена Викторовна.](https://www.youtube.com/watch?v=sTyTM-h3b84&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=15)
* [Урок №13. Тема «Миӈкри тэйкык рэпаԓгъытвъат» («Как построить байдару»). Педагог Эллы Вячеслав.](https://www.youtube.com/watch?v=qsGKnfCuAZM&list=PLg-mb4TwccTK1gkIv4Ls1x3bgFaJL0JQf&index=13)

#### Other data sources (1 hour 25 minutes 50 seconds)
* ["Говорит Анадырь".СССР.Вещание на луораветланском чукотском языке.14 октября 1982 г.](https://www.youtube.com/watch?v=Kg_aKEp8qhM&t)
* [The Sound of the Chukchi language (Numbers, Greetings & The Parable)](https://www.youtube.com/watch?v=XrJiI_-IlM8&t)
* [Блудный сын (на чукотском языке)](https://www.youtube.com/watch?v=MR8F4xFUe20&t)
* [Книга пророка Ионы на чукотском языке](https://www.youtube.com/watch?v=-F1vh7aTW2w)
* [Мультфильм " У лукоморья..." на чукотском языке](https://www.youtube.com/watch?v=r2Ok3wzMqn8&t)
* [Новости на чукотском](https://www.youtube.com/watch?v=Ea1i7LyVQak)
* [Стихотворение А.С. Пушкина "Талисман" на чукотском языке. Часть 1](https://www.youtube.com/watch?v=PR8jjgwgl1I)
* [Стихотворение А.С. Пушкина "Талисман" на чукотском языке. Часть 2](https://www.youtube.com/watch?v=1jUtzz4jZiE)
* [ЧАУЧУ с титрами на русском языке YouTube](https://www.youtube.com/watch?v=1wzDs4S6nPA)
* [Бескрылый гусёнок (1987) мультфильм смотреть онлайн](https://www.youtube.com/watch?v=lwitTz9Gmrw)

## Text

### News sources
* [Internet newspaper "Extreme North"](https://www.ks87.ru/) 
* [A special supplement to the newspaper "Extreme North"](https://kzref.org/murgni-nutenut.html) 

### Literature sources
* ["Portal of National Literatures"](https://rus4all.ru/ckt/) 
* [The book "По аргишному пути канчаланского чаучу"](https://iknigi.net/avtor-samira-asadova/125720-po-argishnomu-puti-kanchalanskogo-chauchu-samira-asadova/read/page-1.html) 
* [Lingvoforum: stories](https://lingvoforum.net/index.php?topic=34883.0), [Lingvoforum: fairy tales](https://lingvoforum.net/index.php?topic=9422.0)
* [VK.com: fairy tales](https://vk.com/topic-9017077_20059103)
* [Puzzles](https://cyberleninka.ru/article/n/chukotskie-zagadki-materialy-k-izucheniyu)

### Charles.weinstein - Grammar and thematic dictionary of the Chukchi language, a collection of Chukchi literary texts 

* http://charles.weinstein.free.fr/chukches/LIT/litt.html 
* http://charles.weinstein.free.fr/chukches/LIT/litt_ru.html 
* http://charles.weinstein.free.fr/chukches/LIT/Yat_S_t.htm
* http://charles.weinstein.free.fr/chukches/GRAM/B16-Chisliteln.html
* http://charles.weinstein.free.fr/chukches/LEX/Lex_shamany_ru.html
* http://charles.weinstein.free.fr/chukches/LIT/Uroki_tch.htm
* http://charles.weinstein.free.fr/chukches/LEX/Lex_tchouvstva4_ru.html
* http://charles.weinstein.free.fr/chukches/LIT/Tynetegyn.htm
* http://charles.weinstein.free.fr/chukches/LEX/Lex-Temps-fr.html
* http://charles.weinstein.free.fr/chukches/GRAM/7-Sklonenie.html

### Other sources
* [The Wayback Machine](https://web.archive.org/web/20110502025902/http://www.ling-atlas.jp/r/tale/list) 
