# Мария Смирнова. Портфолио

## Оглавление
* [Управление продуктом](#управление-продуктом)
* [Управления проектами](#управления-проектами)
* [Python](#python)
* [Case solving experience](#case-solving-experience)
* [Блоги](#блоги)
* [Science portfolio](#science)



## Управление продуктом
### Акселератор с «Зелёным Чердаком»
«Зелёный чердак» - крафтовая травянная мастерска (изоготовление чайных купажей, коспетики и т.д.) Для «Зелёного чердака» мною были настроены процессы - сбора данных для аналитики (учёт финансов, анализ соцсетей, юнит экономика, lean canvas, анализ конкурентов)
1) [Финальная презентация](https://disk.yandex.ru/i/NxDnj9pZOEaV1w) травяной мастерской для акселератора Таврида.Арт 
2) [Презентация](https://disk.yandex.ru/i/AmVpJ1D1eZ_IGQ) на первый отбор травяной мастерской для акселератора Таврида.Арт

### Центр непрерывного повышения профессионального мастерства
*«Nastavnik»* - рекомендационная и аналитическая система для непрерывного повышения профессионального мастерства. Базируется на цифровом следе. Система опробовалась на нескольких пилотных школах и с профессиональным сообществом: формировалась система метрик, дополнялся функционал.   
Техническая реализация включала: 
* предобрабботку данных (входные данные: `xlsx`, `csv`, `pdf`, парсинг с веб-страниц). Конвертация `pdf` в `xlsx` c помощью `tabula` на [github](https://github.com/SlateFlegg/pdf_to_excel). Парсинг данных с вебсайта о курсах с помощью `selenium` и `BeautifulSoup`, пример на [gitflic](https://gitflic.ru/project/petitmx/dpomos_course_parsing).  
* хранение данных в БД (PostgreSQL 14);  
* обработка информации (разработка и согласование методики с проф.сообществом);  
* Реализация сервиса с помощью фрейм-ворка `plotly.Dash`:    

![image](https://github.com/user-attachments/assets/a02ba809-c0dc-4a33-ac1b-90c7225f74c7)


## Управления проектами
### Центр непрерывного повышения профессионального мастерства
Вовлечение работников происходило за счёт профильных конкурсов и через социальные медиа.
Общий охват конкурсов ~ 3 тыс. человек:
- Педагогический кейс-чемпионат «Мы - команда» (~ 2 тыс. человек). В качестве поставщиков кейсов выступали профессиональные сообщества Москвы. Кейсы первого этапа доступны на [я.диске](https://disk.yandex.ru/d/X42_mgUvrNUpBw), запись финальных выступлений команд в [ВК](https://vk.com/video-210962420_456239614). 
- «Фестиваль педагогического мастерства» (~ 2 тыс. человек) - при анализе конкурсов для профессионального роста, был выявлен дефицит внимания к дошкольной ступени образования. Чтобы его восполнить и был организован фестиваль. 
- тг-канал [«Москва.ЦНППМ»](https://t.me/mos_cnppm/196), развился с нуля до 1 тыс. подписчиков за 4 месяца.
### Профобучение без границ
Онлайн обучение детей старших классов с инвалидностью дистантным-профессиям (SMM, веб-дизайн, бисероплетение).
Моя задача полное сопровождение проекта от получения гос.задания до найма преподавателей и организации обучения.
Охват - 30 учеников, одного удалось трудоустроить.

### В сфере горной добычи
* Умное хвостохранилище - проект развиваемый на базе хвостохранилища КГМК и занявший 3е место 🏆 среди проектов диджитл-трансформации горнодобывающей отрасли Minex-2019: [Презентация](https://disk.yandex.ru/i/Jm8j6mEsaHiKVQ)
* Разработка робота-маркшейдера. Был создан прототип и представлена задача от Норникеля на кейс-чемпионат  Changellenge CupTechnical-2019, по результатам которого одна из команд продолжила развитие идеи.


## Python
### Публикации
* Использование средств языка python для автоматической обработки данных результатов диагностик [elibrary](https://www.elibrary.ru/item.asp?id=65116449), [запись выступления](https://rutube.ru/video/f45bd2d25f1331c00518bcb4caf3a65c/)
* Использование цифровых технологий при формировании информационной базы анализа кадрового развития сферы образования [текст](https://dlt.mgpu.ru/wp-content/uploads/sites/7/2023/11/mcu-journal-of-informatics-2023-3-65.pdf#page=40)
* Статья на хабр [Как подсветить временные отрезки на графиках](https://habr.com/ru/post/710530/)

### Проекты  
- Телеграм-бот опросник. На основании ответов пользователя, ему предлагаются рекомендации (по матрице рекомендаций) по развитию компетенций. Бот написан с использованием асинхронной библиотеки `aiogram`. [Проект на gitflic.](https://gitflic.ru/project/petitmx/teachers_recommendation_bot)  
- Вебстраница об оценки качества. Требовалось организовать оценку качества мероприятия без использования внешних сервисов - было решено установить планшеты, на которых открыть страницу созданную с помощью `plotly.Dash`. [Проект на gitflic](https://gitflic.ru/project/petitmx/quality_evaluation) доработанный 
m3m0.

### Работа с данными  
- Тетрадка-шпоргалка про работу с изображениями с помощью python. [Тетерадка на github](https://github.com/SlateFlegg/BasicImageManipulation)  
- Тетрадки для подготовки к олимпиаде по анализу данных ДАНО ВШЭ для школьников. [Репозиторий на github](https://github.com/SlateFlegg/training_dano_olymp)


### Хакатоны
#### Хакатон “Цифровой прорыв”. Infrastructure object recognition using satellite data

Задача: Создание бинарной маски - здание/не здание. Ключевая метрика F1-score восьмая по лидерборду на финальном сете. [](https://github.com/SlateFlegg/Infrastructure_object_recognition/tree/main)[https://github.com/SlateFlegg/Infrastructure_object_recognition](https://github.com/SlateFlegg/Infrastructure_object_recognition)  

#### Хакатон "Лидеры цифровой трансформации - 2024". Привязка космоснимков к подложке  
Задача: привязка отдельного космоснимка к подложке. Космоснимок может иметь существенные искажения. [Репозиторий на github](https://github.com/SlateFlegg/LDT_satellite_task18_2023)

#### Хакатон “Цифровой прорыв”. Классификация агрокультур на основе изменения показателя вегетационных индексов во временной последовательности 
Задача: Классификация агрокультур на основе изменения показателя вегетационных индексов во временной последовательности [https://github.com/SlateFlegg/innopolis_ndvi](https://github.com/SlateFlegg/innopolis_ndvi)


#### Хакатон “Антихакатон от ВкусВилл”
Во время хакатона было проанализировано с помощью python, SQL & PowerBI несколько миллионов строк данных о нахождения точек продаж, покупок, возвратов и т.п.. 
Строгое NDA не разрешает делится результатами, однако было найдено 3 “провисающих” показателя, выдвинуты продуктовые гипотезы. Одна уже была известна заказчику и он принимал риски по ней, две другие не подтвердились.


## Case solving experience
* **Финалист (топ-5)** CupTechnical. Кейс Норникеля: “По разработке эффективной системы мотивации персонала и увеличения производительности труда на Быстринском месторождении”
* **Второе место** Eco solution cup MGIMO goes green
*  **Top-25%** CupTechnical. Кейс: “Проект создания ТОР “Таймырский добычной и промышленный кластер”.
* **High Quality Award** СupMisis. Кейс: “Альтернативные технологии очистки шахтных вод от вредных примесей”
* **Author & judge**. Case-competition Changellenge CupTechnical, 2020
*  [Head talks, Changellenge](https://vk.com/video-25758_456239357) (from 4:43:00)

## Блоги
### Интервью для инженерной школы Forbes
Ролик-интервью про работу в Цифровой лаборатории в инженерной школе Forbes [youtu.be/dQ_atZqOEa4](http://youtu.be/dQ_atZqOEa4)
### Статьи о геологии и образовании
Научно-популярные статье и для “Коалиции авторов Росгеологии”: 
[Мария Смирнова](https://blog.rusgeology.ru/authors/mariya-smirnova)   
Серия статей об образовательной системе ФРГ для “Вестника образования”:
* [Поездка в Германию: из магистратуры в детский сад](https://vogazeta.ru/articles/2018/11/16/international/5229-poezdka_v_germaniyu_iz_magistratury_v_detskiy_sad_chast_1)
* [Квест "Попади в университет"](https://vogazeta.ru/articles/2018/11/21/international/5274-kvest_popadi_v_universitet_obrazovatelnoe_puteshestvie_po_germanii_chast_2)

# Science
**Master thesis** «Olivine and clinopyroxene of the Phanerozoic ultramafic lamprophyres (South-Wes Siberia): composition, zonality, and formation» (in Russian) [[thesis](https://www.dropbox.com/s/djyecsj4f0e5tq0/Master%20thesis%20Smirnova.pdf?dl=0 "https://www.dropbox.com/s/djyecsj4f0e5tq0/Master%20thesis%20Smirnova.pdf?dl=0"); [presentation](https://www.dropbox.com/s/xvxgm8hzw69p7tu/Master%20thesis%20Smirnova%20pres.pdf?dl=0 "https://www.dropbox.com/s/xvxgm8hzw69p7tu/Master%20thesis%20Smirnova%20pres.pdf?dl=0")]

**Bachelor thesis** «Petrology and geochemistry of quaternary Baydara volcanic center, Kamchatka» (in Russian) [[thesis](https://www.dropbox.com/s/xeyylpf95dvxkwc/Bachalor%20thesis%20Smirnova.pdf?dl=0 "https://www.dropbox.com/s/xeyylpf95dvxkwc/Bachalor%20thesis%20Smirnova.pdf?dl=0"); [presentation](https://www.dropbox.com/s/hblgy1p3y0bkgzd/Bachalor%20thesis%20Smirnova%20pres.pdf?dl=0 "https://www.dropbox.com/s/hblgy1p3y0bkgzd/Bachalor%20thesis%20Smirnova%20pres.pdf?dl=0")]

**Papers**:

·         Хамардюк, А. В., Селиверстова, И. В., Cмирнова, М. Д., & Карпова, А. П. (2023). ИСПОЛЬЗОВАНИЕ ЦИФРОВЫХ ТЕХНОЛОГИЙ ПРИ ФОРМИРОВАНИИ ИНФОРМАЦИОННОЙ БАЗЫ АНАЛИЗА КАДРОВОГО РАЗВИТИЯ СФЕРЫ ОБРАЗОВАНИЯ. Вестник Московского городского педагогического университета. Серия: Информатика и информатизация образования, (3 (65)), 41-56. [Страница статьи на сайте журнала.](https://dlt.mgpu.ru/2023/11/01/ispolzovanie-czifrovyh-tehnologij-pri-formirovanii-informaczionnoj-bazy-analiza-kadrovogo-razvitiya-sfery-obrazovaniya/)  
·         Толстых М.Л., Бабанский А.Д., Смирнова М.Д и др. (2023) «Вулканизм начальной фазы заложения северного сегмента субдукции Тихоокеанской плиты (полуостров Камчатка, хребет Кумроч). Вулканология и сейсмология №2 стр. 52-68.

·         Butvina V.G., Smirnova M.D., Safonov O.G., Van K.V. (2019). Experimental modeling of subsolidus parageneses of ultramafic lamprophyres of the Irkeneeva-Chadobets trough, South -Western Siberia, at high PT-parameters. Experiment in GeoSciences 25.1, 51-54 [[paper](https://www.dropbox.com/s/z0e6betbvk0ew8e/Experimental%20modeling%20of.pdf?dl=0 "https://www.dropbox.com/s/z0e6betbvk0ew8e/Experimental%20modeling%20of.pdf?dl=0")]

·         Nosova, A. A., Sazonova, L. V., Kargin, A. V., Smirnova, M. D., Lapin, A. V., & Shcherbakov, V. D. (2018). Olivine in ultramafic lamprophyres: chemistry, crystallisation, and melt sources of Siberian Pre-and post-trap aillikites. Contributions to Mineralogy and Petrology, 173(7), 1-27 [[paper](https://www.researchgate.net/publication/325856415_Olivine_in_ultramafic_lamprophyres_chemistry_crystallisation_and_melt_sources_of_Siberian_Pre-_and_post-trap_aillikites "https://www.researchgate.net/publication/325856415_Olivine_in_ultramafic_lamprophyres_chemistry_crystallisation_and_melt_sources_of_Siberian_Pre-_and_post-trap_aillikites")]

·         Каргин, А. В., Носова, А. А., Постников, А. В., Чугаев, А. В., Постникова, О. В., Попова, Л. П., ... & Смирнова, М. Д. (2016). Девонские ультрамафические лампрофиры Иркинеево-Чадобецкого прогиба юга-запада Сибирской платформы: возраст, состав и значение для прогноза алмазоносности. Геология рудных месторождений, 58(5), 430-450. [[paper](https://www.dropbox.com/s/dydk6czd45jv5xp/%D0%94%D0%B5%D0%B2%D0%BE%D0%BD%D1%81%D0%BA%D0%B8%D0%B5%20%D1%83%D0%BB%D1%8C%D1%82%D1%80%D0%B0%D0%BC%D0%B0%D1%84%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5%20%D0%BB%D0%B0%D0%BC%D0%BF%D1%80%D0%BE%D1%84%D0%B8%D1%80%D1%8B%20%D0%98%D1%80%D0%BA%D0%B8%D0%BD%D0%B5%D0%B5%D0%B2%D0%BE-%D0%A7%D0%B0%D0%B4%D0%BE%D0%B1%D0%B5%D1%86%D0%BA%D0%BE%D0%B3%D0%BE.pdf?dl=0 "https://www.dropbox.com/s/dydk6czd45jv5xp/%D0%94%D0%B5%D0%B2%D0%BE%D0%BD%D1%81%D0%BA%D0%B8%D0%B5%20%D1%83%D0%BB%D1%8C%D1%82%D1%80%D0%B0%D0%BC%D0%B0%D1%84%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5%20%D0%BB%D0%B0%D0%BC%D0%BF%D1%80%D0%BE%D1%84%D0%B8%D1%80%D1")]


**Achievements**

§  April, 2019. Got Early career scientist’s travel support (ECSTS) for European Geosciences Union (EGU) General Assembly.

§  April, 2017. Got Early career scientist’s travel support (ECSTS) for European Geosciences Union (EGU) General Assembly.

§  February, 2017. 4th place in English-language popular geology presentation contest, MSU with “Ontogeny of minerals. The new stage of understanding of natural phenomena”. [[presentation](https://www.dropbox.com/s/89qkjfq9t4lb8h5/Ontogeny%20of%20minerals.pdf?dl=0 "https://www.dropbox.com/s/89qkjfq9t4lb8h5/Ontogeny%20of%20minerals.pdf?dl=0")]

§  December, 2016 «The best presentation at the conference», New in the knowledge of ore formation processes. [[paper](https://www.dropbox.com/s/ruyy2tyss0dw698/IGEM-2016-thesis.pdf?dl=0 "https://www.dropbox.com/s/ruyy2tyss0dw698/IGEM-2016-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/k3kd9ovk8ds0ivy/IGEM-2016-pres.pdf?dl=0 "https://www.dropbox.com/s/k3kd9ovk8ds0ivy/IGEM-2016-pres.pdf?dl=0")]

§  April, 2016. Diploma of the winner. Competition of scientific works of the Faculty of Geology of Moscow State University in the nomination "the best presentation at the XXIII international scientific conference of students, graduate students and young scientists "Lomonosov", section "Geology". [[presentation](https://www.dropbox.com/s/bkvb2j6egxo5sg6/DS-2016-pres.pdf?dl=0 "https://www.dropbox.com/s/bkvb2j6egxo5sg6/DS-2016-pres.pdf?dl=0")]

§  April, 2016. Innovation mining contest “Lomonosov”, final stage.

§  April, 2015. Diploma of the winner. Competition of scientific works of the Faculty of Geology of Moscow State University in the nomination "the best presentation at the XXIII international scientific conference of students, graduate students and young scientists "Lomonosov", section "Geology". [[paper](https://www.dropbox.com/s/s058pe4qw6wqsc1/Lomonosov-2015-thesis.pdf?dl=0 "https://www.dropbox.com/s/s058pe4qw6wqsc1/Lomonosov-2015-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/s058pe4qw6wqsc1/Lomonosov-2015-thesis.pdf?dl=0 "https://www.dropbox.com/s/s058pe4qw6wqsc1/Lomonosov-2015-thesis.pdf?dl=0")]

§  2015, April. Universiade "Lomonosov". Field of knowledge: geology, winner.

**Conferences papers**

·      Использование средств языка Python для автоматической обработки данных результатов диагностик: повыш / М. Д. Смирнова, А. П. Карпова, И. В. Селиверстова, А. В. Хамардюк // Искусственный интеллект и роботизированные системы в образовании : сборник статей Межрегиональной научно-практической конференции, Новосибирск, 30 ноября 2023 года. – Новосибирск: Новосибирский государственный педагогический университет, 2024. – С. 90-95. – EDN NKNHAC. [Текст](https://disk.yandex.ru/i/EKvvhCcs3r9GOg), [видео-презентация](https://rutube.ru/video/f45bd2d25f1331c00518bcb4caf3a65c/)

·      May, 2021. 90th anniversary of IGEM RAS “Petrology and geochemistry features of Baidara massive (Central Kamchatka Depression)” [paper; [presentation](https://www.dropbox.com/s/agp0e8risaofx7y/90%20%D0%BB%D0%B5%D1%82%20%D0%B8%D0%B3%D0%B5%D0%BC%D1%83.pdf?dl=0 "https://www.dropbox.com/s/agp0e8risaofx7y/90%20%D0%BB%D0%B5%D1%82%20%D0%B8%D0%B3%D0%B5%D0%BC%D1%83.pdf?dl=0")]

·      April, 2019 EGU, «Experimental study of paragenesis of ultramafic lamprophyres: aillikites from Southwestern Siberia». [[paper](https://www.dropbox.com/s/0upjtoghmdfxbjd/EGU2019-1027.pdf?dl=0 "https://www.dropbox.com/s/0upjtoghmdfxbjd/EGU2019-1027.pdf?dl=0"); [presentation](https://www.dropbox.com/s/go0wsoccwayts7i/EGU2019-1027-pres.pdf?dl=0 "https://www.dropbox.com/s/go0wsoccwayts7i/EGU2019-1027-pres.pdf?dl=0")]

·      November, 2018. IX Young scientists school “Experimental mineralogy, petrology and geochemistry”. [[paper](https://www.dropbox.com/s/6t06fhg1jwsy7z6/%D0%98%D0%AD%D0%9C_%D0%A1%D0%BC%D0%B8%D1%80%D0%BD%D0%BE%D0%B2%D0%B0_2018.pdf?dl=0 "https://www.dropbox.com/s/6t06fhg1jwsy7z6/%D0%98%D0%AD%D0%9C_%D0%A1%D0%BC%D0%B8%D1%80%D0%BD%D0%BE%D0%B2%D0%B0_2018.pdf?dl=0")]

·      September, 2018. Magmatism of the earth and related strategic metal deposits. «Experimental study of subsolidus parageneses of ultramafic lamprophyres of the irkeneeva-chadobets trough, southwestern Siberia at 5 GPA. [[paper](https://www.dropbox.com/s/blrfj9mxaoe55pa/Magmas-and-metlas-2018-thesis.pdf?dl=0 "https://www.dropbox.com/s/blrfj9mxaoe55pa/Magmas-and-metlas-2018-thesis.pdf?dl=0")] **In English**

·      April, 2017. Lomonosov, «Petrological features of clinopyroxenes from alkaline ultramafic rocks Chadobetsky uplift,southwestern Siberia ». [[paper](https://www.dropbox.com/s/2oginijcacyoodk/Lomonosov-2017-thesis.pdf?dl=0 "https://www.dropbox.com/s/2oginijcacyoodk/Lomonosov-2017-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/lrvxgnse05gvk1m/Lomonosov-2017-pres.pdf?dl=0 "https://www.dropbox.com/s/lrvxgnse05gvk1m/Lomonosov-2017-pres.pdf?dl=0")]

·      September, 2017. Global studies conference, special panel «Impact of the Farakka Dam on the sustainable development of India and Bangladesh Options for dealing with the problem» [[paper](https://www.dropbox.com/s/l8qyb2cn5if1pp2/Global%20studies%20conference-2017-thesis.pdf?dl=0 "https://www.dropbox.com/s/l8qyb2cn5if1pp2/Global%20studies%20conference-2017-thesis.pdf?dl=0")]

·      August, 2017. Magmatism of the Earth and related deposits of strategic metals, «3 types of clinopyroxenes from aillikite, ilbokicheskoe and Chadobets uplifts, South-West Siberia, Russia» [[paper](https://www.dropbox.com/s/2oginijcacyoodk/Lomonosov-2017-thesis.pdf?dl=0 "https://www.dropbox.com/s/2oginijcacyoodk/Lomonosov-2017-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/4yk06xdic37332d/Magmatism-2017-pres.pdf?dl=0 "https://www.dropbox.com/s/4yk06xdic37332d/Magmatism-2017-pres.pdf?dl=0")]

·      August, 2017. International school of earth sciences, «Diffusion in olivine xenocrystfrom ultramafic lamprophyres Chadobetsuplift, South-West Siberia Russia». [[paper](https://www.dropbox.com/s/npskoucq29jq9td/ISES-2017-thesis.pdf?dl=0 "https://www.dropbox.com/s/npskoucq29jq9td/ISES-2017-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/k8p2ii82eug3yw2/ISES-2017-pres.pdf?dl=0 "https://www.dropbox.com/s/k8p2ii82eug3yw2/ISES-2017-pres.pdf?dl=0")] **In English**

·      April, 2017. EGU, «Phenocrysts and megacrysts of olivines from ultramafic lamprophyres of the Chadobets and Il’bokich uplifts, Southwestern Siberia». [[paper](https://www.dropbox.com/s/nd9r91q6me41250/EGU2017-335.pdf?dl=0 "https://www.dropbox.com/s/nd9r91q6me41250/EGU2017-335.pdf?dl=0"); PICO-[presentation](https://www.dropbox.com/s/9staua5pumh0vbu/EGU2017-335%20PICO.pdf?dl=0 "https://www.dropbox.com/s/9staua5pumh0vbu/EGU2017-335%20PICO.pdf?dl=0"); [OSPP-evaluations](https://www.dropbox.com/s/w5kpe6n7nnlbm7t/EGU2017-OSPP-evaluations.pdf?dl=0 "https://www.dropbox.com/s/w5kpe6n7nnlbm7t/EGU2017-OSPP-evaluations.pdf?dl=0")] **In English**

·      December, 2016. New in the knowledge of ore formation processes, «Olivine phenocrysts and megacrysts from ultramafic lamprophyres Chadobetsky and Ilbokish uplifts, SW Siberia». [[paper](https://www.dropbox.com/s/ruyy2tyss0dw698/IGEM-2016-thesis.pdf?dl=0 "https://www.dropbox.com/s/ruyy2tyss0dw698/IGEM-2016-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/k3kd9ovk8ds0ivy/IGEM-2016-pres.pdf?dl=0 "https://www.dropbox.com/s/k3kd9ovk8ds0ivy/IGEM-2016-pres.pdf?dl=0")]

·      November, 2016. Interuniversity conference on the results of practices (MKIP), « Mountain Altai. Field practice». [[paper](https://www.dropbox.com/s/ak6mfqfuklr2kjz/MKIP-2016-thesis.pdf?dl=0 "https://www.dropbox.com/s/ak6mfqfuklr2kjz/MKIP-2016-thesis.pdf?dl=0")]

·      2016, June. VIII International Siberian Early Career Geoscientists Conference, «The origin of rutile and ilminite pseudomorphosis after perovskite in aillikites from Ilbokicheskoe occurrence, SW Siberia». [[paper](https://www.dropbox.com/s/wxchg0hwchfaf0v/SibConf-2016-thesis.pdf?dl=0 "https://www.dropbox.com/s/wxchg0hwchfaf0v/SibConf-2016-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/aq05go3biv7g5t4/SibConf-2016-pres.pdf?dl=0 "https://www.dropbox.com/s/aq05go3biv7g5t4/SibConf-2016-pres.pdf?dl=0")] **In English**

·      2016, May. Alkaline magmatism of the Earth and related deposits of strategic metals, «Carbonates from aillikites, Ilbokicheskoe uplift, SW Siberia». [[paper](https://www.dropbox.com/s/2504zmc3esortbf/AlkilineMagmatisv-2016-thesis.pdf?dl=0 "https://www.dropbox.com/s/2504zmc3esortbf/AlkilineMagmatisv-2016-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/1ak0lbsv3aazc7l/AlkilineMagmatisv-2016-pres.pdf?dl=0 "https://www.dropbox.com/s/1ak0lbsv3aazc7l/AlkilineMagmatisv-2016-pres.pdf?dl=0") **in English**]

·      2016, May. Moscow International school of earth sciences. «Petrography and mineralogy of ultramafic lamprophyre from the Ilbokicheskaya Occurrence, SW Siberia» [[paper](https://www.dropbox.com/s/jvaa2bz5dhniwbs/ISES-2016-thesis.pdf?dl=0 "https://www.dropbox.com/s/jvaa2bz5dhniwbs/ISES-2016-thesis.pdf?dl=0"); [poster](https://www.dropbox.com/s/v2cxp2c5ngmbg5j/ISES-2016-poster.pdf?dl=0 "https://www.dropbox.com/s/v2cxp2c5ngmbg5j/ISES-2016-poster.pdf?dl=0")]

·      April, 2016. Lomonosov. «Evidence of metasomatic parageneses in ailikits of the Irkineevsky trough, Western Siberia» [[paper](https://www.dropbox.com/s/pz0uu24zbo13z1q/Lomonosov-2016-thesis.pdf?dl=0 "https://www.dropbox.com/s/pz0uu24zbo13z1q/Lomonosov-2016-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/s3k45n53ulixaze/Lomonosov-2016-pres.pdf?dl=0 "https://www.dropbox.com/s/s3k45n53ulixaze/Lomonosov-2016-pres.pdf?dl=0")]

·      April, 2016 Day of science, MSU. « Classification of lamprophyres from the Ilbokskaya borehole, SW Siberia» [[presentation](https://www.dropbox.com/s/bkvb2j6egxo5sg6/DS-2016-pres.pdf?dl=0 "https://www.dropbox.com/s/bkvb2j6egxo5sg6/DS-2016-pres.pdf?dl=0")]

·      March 2016. Workshop “Probing magma reservoirs in time and space” at ETH Zurich.

·      2015, November. Interuniversity conference on the results of practices (MKIP), « Baydara volcanic center. New Data» [[paper](https://www.dropbox.com/s/vud35wo7ev9auvm/MKIP-2015-thesis.pdf?dl=0 "https://www.dropbox.com/s/vud35wo7ev9auvm/MKIP-2015-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/lgw6lokzzbp8uj3/MKIP-2015-pres.pdf?dl=0 "https://www.dropbox.com/s/lgw6lokzzbp8uj3/MKIP-2015-pres.pdf?dl=0")]

·      April, 2015. Lomonosov «Petrological and geochemical features of the Quaternary volcanic center Baydara, Kamchatka» [[paper](https://www.dropbox.com/s/s058pe4qw6wqsc1/Lomonosov-2015-thesis.pdf?dl=0 "https://www.dropbox.com/s/s058pe4qw6wqsc1/Lomonosov-2015-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/s058pe4qw6wqsc1/Lomonosov-2015-thesis.pdf?dl=0 "https://www.dropbox.com/s/s058pe4qw6wqsc1/Lomonosov-2015-thesis.pdf?dl=0")]

·      2014, November. Interuniversity conference on the results of practices (MKIP), «Mount Baidara: object of 2014 flied trip». [[paper](https://www.dropbox.com/s/vagzi5ped0aivbd/MKIP_Baidara_thesis.pdf?dl=0 "https://www.dropbox.com/s/vagzi5ped0aivbd/MKIP_Baidara_thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/r9nixvoh5cc9urc/MKIP_Baidara_pres.pdf?dl=0 "https://www.dropbox.com/s/r9nixvoh5cc9urc/MKIP_Baidara_pres.pdf?dl=0")]

·      October, 2012. “Development of a model of interatomic potentials for borates structural modeling”. [[paper](https://www.dropbox.com/s/lv331joz9em7oxm/mssmi-2012-thesis.pdf?dl=0 "https://www.dropbox.com/s/lv331joz9em7oxm/mssmi-2012-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/6of05b1udpp6p73/mssmi-2012-pres.pdf?dl=0 "https://www.dropbox.com/s/6of05b1udpp6p73/mssmi-2012-pres.pdf?dl=0")]

**Field Trips/Practice**

·      2016, June. Altai, «Geology, magmatism and metallogeny of Gorny Altai»

·      2015, August, Kola peninsula. «Alkaline Magmatism of the Kola peninsula and related strategic deposits»

·      2014, Summer, Kamchatka. Geological research Shiveluch area and collecting samples for bachelor paper

·      2014, June (3 weeks). Institute of Experimental Mineralogy RAS «Experimental petrology»

·      2013, Summer (4 weeks). South Ural «Field methods of studying igneous complexes»

·      2013, Summer (6 weeks). Crimea «Field methods (geological including drilling, geophysical and applied physical training)»

·      2012, June-July. Crimea «General Geology»

**Projects**

Found and manage pop-science lectorium «Лекторий молодых учёных», Фестиваль науки 2015 - 2019
