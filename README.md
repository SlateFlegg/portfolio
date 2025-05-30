# Мария Смирнова. Портфолио


## Оглавление
* [Machine Learning](#ML)
* [Python](#python)
* [Геология](#геология)
* [ГеоИнформационные системы](#гис)
* [Управление продуктом](#управление-продуктом)
* [Управления проектами](#управления-проектами)
* [Case solving experience](#case-solving-experience)
* [Блоги](#блоги)
* [Science portfolio](#science)


## ML
### Хакатоны

#### 🥉 Хакатон “Норникель: Интеллектуальные горизонты”. Трек "Флотомашина времени", 2024
Задача: Оптимизировать извлечение руды из пулы, находя наиболее эффективные диапазоны при заданных ограничениях. Данные цифрового двойника флотационного цеха.   
Моя роль: teamlead - собрала команду; анализ данных, выявление их особенностей и постановка задачи для ML. Поиск альтернативных подходов - например, отдельной модели для первой флотомашины.  
Решение: [Github](https://github.com/fkurushin/Norilskiy-Nickel-Hackathon/tree/master), [Презентация и код на Я.диске](https://disk.yandex.ru/d/Fx0k5GjONqfIOA)  
Результат: 3 место  

#### Хакатон "Геомодель-2025", 2025  
Задача: Синтез сейсмических откликов, полученных в ходе численного моделирования, на основании численного моделирования с меньшим разрешением (в частности на высоких частотах).  
Моя роль: индивидуальное участие  
Решение: [github](https://github.com/SlateFlegg/Geomodel_hack/tree/main), были опробованы разнообразные свёртки, в том числе свёртки на графах и LSTM. Итоговая модель модицифицированная Unet (с большим ядром свёртки, 3 "этажами" + учёт расстояния и положения сенсора).  
Результат: ожидается  

#### Хакатон "Цифровой прорыв" Подбор кандидатов на вакансию по типу личности
Задача: Определение типа личности (по OCEAN) по видео-визитке и перевод в типы личности по MBTI. Датасет видео с разметкой типа личности по OCEAN с расшифровкой речи (в основном английский язык.)  
Моя роль: DS - аналитика данных, подготовка мультимодальной модели (общий пайплайн, звук, NLP (в финальной реализации не использовали)), демонстрационная часть интерфейса.  
Решение: [Github](https://github.com/SlateFlegg/it-hatters_hacks_ai_24/tree/main)  
Результат: 5 по метрике, 9 по метрике + решение бизнес задачи  

#### Хакатон “Цифровой прорыв”. Infrastructure object recognition using satellite data, 2023
Задача: Создание бинарной маски - здание/не здание. Ключевая метрика F1-score восьмая по лидерборду на финальном сете.
Моя роль: тимлид - собрала команду; аналитика данных, подходы к обработке космоснимков (маски по индексам), DS - пайплайн и обучение модели.  
Решение: [Github](https://github.com/SlateFlegg/Infrastructure_object_recognition)    
Результат: 8 по метрике, 14 по метрике + решение бизнес задачи  
#### Хакатон "Лидеры цифровой трансформации - 2024". Привязка космоснимков к подложке  
Задача: привязка отдельного космоснимка к подложке. Космоснимок может иметь существенные искажения.    
Моя роль: поиск алгоритма (ORB, ближайшие соседи по маскам авторазметки, расчёт графа соседствующих классов).  
Подходы к решению: [Github](https://github.com/SlateFlegg/LDT_satellite_task18_2023)  
Результат: алгоритм не реализовали  
#### Хакатон “Цифровой прорыв”. Классификация агрокультур на основе изменения показателя вегетационных индексов во временной последовательности, 2022   
Задача: Классификация агрокультур на основе изменения показателя вегетационных индексов во временной последовательности
Моя роль: индивидуальное участие  
Решение: [Github](https://github.com/SlateFlegg/innopolis_ndvi)  
### Другое  
#### Домашки ML-тренировок Яндекса по CV  
*[Страница курса](https://yandex.ru/yaintern/training/ml-training)* Автор курса:[Радослав Нейчев](https://www.linkedin.com/in/radoslav-neychev/), [girafe_ai](https://t.me/s/girafe_ai)  
Репозиторий на gitflic. Примеры:
* [03_hw_sobel_and_simple_hog.ipynb](https://gitflic.ru/project/petitmx/ya_ml_3_homeworks/blob/?file=03_hw_sobel_and_simple_hog.ipynb&branch=master) - реализация операции Собеля и HoG на `numpy`  
* [06_.ipynb](https://gitflic.ru/project/petitmx/ya_ml_3_homeworks/blob/?file=06_.ipynb&branch=master) - восстановление параметров свётрки для сети с тремя светками, две из которых известны
* [07_modules.ipyn](https://gitflic.ru/project/petitmx/ya_ml_3_homeworks/blob/?file=07_modules.ipynb&branch=master) - написание сети с только с помощью numpy (полносвязный слой, функции потерь, нормирование батчей)  
#### Финальный проект Я.Практикума  
Задача: оптимизация параметров "внепечного этапа"  доведения до целевого химического состава. Временные ряды.  
Решение: [Github](https://github.com/SlateFlegg/yandex_practicum_ml/tree/main/final_project)

## Python
### Проекты  
- Телеграм-бот опросник. На основании ответов пользователя, ему предлагаются рекомендации (по матрице рекомендаций) по развитию компетенций. Бот написан с использованием асинхронной библиотеки `aiogram`. [Проект на gitflic.](https://gitflic.ru/project/petitmx/teachers_recommendation_bot)   
- Веб-страница "социометрия" для разворачивания в локальной сети. [Проект на gitflic](https://gitflic.ru/project/petitmx/form_socialmetry). Процессинг данных, полученных из формы (построение графов, визуализация): [Проект на gitflic](https://gitflic.ru/project/petitmx/socialmetry_proccessing)  
- Веб-страница об оценки качества. Требовалось организовать оценку качества мероприятия без использования внешних сервисов - было решено установить планшеты, на которых открыть страницу созданную с помощью `plotly.Dash`. [Проект на gitflic](https://gitflic.ru/project/petitmx/quality_evaluation) доработанный 
### Работа с данными  
#### Тетрадки
- Проектная работа со школьником по анализу данных и сбора ученического порфтолио. [Репозиторий проекта]([url](https://gitflic.ru/project/alladan08/nastavnik_conf))   
- Тетрадка-шпоргалка про работу с изображениями с помощью python. [Тетрадка на github](https://github.com/SlateFlegg/BasicImageManipulation)
- Тетрадки для подготовки к олимпиаде по анализу данных ДАНО ВШЭ для школьников. [Репозиторий на github](https://github.com/SlateFlegg/training_dano_olymp)
- Материалы для вовлечения школьников в разработку системы анализирующую и формирующую протфолио учащихся. Канал на [rutube](https://rutube.ru/plst/599878/), репозиторий на [gitflic](https://gitflic.ru/project/petitmx/nastavnik_by_1944).
#### Хакатон “Антихакатон от ВкусВилл”
Во время хакатона было проанализировано с помощью python, SQL & PowerBI несколько миллионов строк данных о нахождения точек продаж, покупок, возвратов и т.п.. 
Строгое NDA не разрешает делится результатами, однако было найдено 3 “провисающих” показателя, выдвинуты продуктовые гипотезы. Одна уже была известна заказчику и он принимал риски по ней, две другие не подтвердились.

### Публикации
* Использование средств языка python для автоматической обработки данных результатов диагностик [elibrary](https://www.elibrary.ru/item.asp?id=65116449), [запись выступления](https://rutube.ru/video/f45bd2d25f1331c00518bcb4caf3a65c/)
* Использование цифровых технологий при формировании информационной базы анализа кадрового развития сферы образования [текст](https://dlt.mgpu.ru/wp-content/uploads/sites/7/2023/11/mcu-journal-of-informatics-2023-3-65.pdf#page=40)
* Статья на хабр [Как подсветить временные отрезки на графиках](https://habr.com/ru/post/710530/)


## Геология  
### Научные публикации  
Представлены в разделе [Science portfolio](#science). Обобщая: основная тема исследований петрология и геохимия вулканитов (бакалаврская работа: *Петролого-геохимические особенности четвертичного
вулканического центра Байдара, Камчатка*) и ультрамафитов (магистерская работа: *Оливин и клинопироксен из палеозойских ультрамафических лампрофиров Юго-Западной Сибири: состав, зональность и происхождение*).  
### Научно-популярное направление    
* Сосоставитель заданий и принимающий на очном туре Московской открытой олимпиады по геологии по направлению эндогенных процессов.
* Публикации в “Коалиции авторов Росгеологии”:  [Мария Смирнова](https://blog.rusgeology.ru/authors/mariya-smirnova)
* Составление вопросов для [теста на день геолога](https://geolog23.rusgeology.ru/) и [ко дню космонавтики](https://vk.com/slateflegg?w=wall-105527557_14463) от Росгеологии. 
* Статьи в подписочную часть и несколько постов в сообщесво "[Геологи](https://vk.com/geologi)" в ВК.  
* Составление задачи по геохимии для [Пост о задаче в сообщество "Геологи"](https://vk.com/slateflegg?w=wall-129276619_27263)

Также участие в разработке ИИ-инструметов по распознанию керна в качестве геолога-эксперта и написанию инструкций по разметке датасетов (шлифы в скрещенных и параллельных николях).

## ГИС  
### QGIS
Прошла практический курс ["Основы геоинформатики: практикум в QGIS"](https://aentin.github.io/qgis-course/): освоила работу с векторными, растровыми данными, shape-, geoJSON-, GeoPackage файлами, а также модулями `QuickOSM`, `QNEAT3`, `SAGA`, `GDAL`. Ознакомиться с выполнеными работами можно на [Я.Диске](https://disk.yandex.ru/d/6AEpJNYDZSg7Hw).  
Пример: поиск места проведения практического тура по географии ВОШ-2025:  
![image](https://github.com/user-attachments/assets/fb5168ae-e9d8-44c9-baa8-b205b51af79d)

### Google earth engine  
Проекты с использованием базы данных и библиотеки GEE. Система позволяет обращаться к широкому спектру спутниковых снимков и данных. Имеет как свою среду разработки ([code.earthengine.google.com](https://code.earthengine.google.com/)), так и библиотеку для `python`. Мои проекты можно посмотреть в [репозитории на github](https://github.com/SlateFlegg/GoogleEarthEngineScripts).

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
- Педагогический кейс-чемпионат «Мы - команда» (~ 2 тыс. человек). В качестве поставщиков кейсов выступали профессиональные сообщества Москвы. Кейсы первого этапа доступны на [я.диске](https://disk.yandex.ru/d/X42_mgUvrNUpBw), запись финальных выступлений команд в [ВК](https://vk.com/video-210962420_456239614). Для чемпионата были проведены 3 метадических стрима по стратегическому планированию и решению кейсов - [плей-лист на rutube](https://rutube.ru/plst/342528/).   
- «Фестиваль педагогического мастерства» (~ 2 тыс. человек) - при анализе конкурсов для профессионального роста, был выявлен дефицит внимания к дошкольной ступени образования. Чтобы его восполнить и был организован фестиваль. Для методической поддержки был отснят мини-курс по работе с презентациям и экселем, [плей-лист на rutube](https://rutube.ru/plst/343173/). Так же проведены 2 стрима - [плей-лист на rutube](https://rutube.ru/plst/346786/).  
- тг-канал [«Москва.ЦНППМ»](https://t.me/mos_cnppm/196), развился с нуля до 1 тыс. подписчиков за 4 месяца.
### Профобучение без границ
Онлайн обучение детей старших классов с инвалидностью дистантным-профессиям (SMM, веб-дизайн, бисероплетение).
Моя задача полное сопровождение проекта от получения гос.задания до найма преподавателей и организации обучения.
Охват - 30 учеников, одного удалось трудоустроить.
### В сфере горной добычи
* Умное хвостохранилище - проект развиваемый на базе хвостохранилища КГМК и занявший 3е место 🏆 среди проектов диджитл-трансформации горнодобывающей отрасли Minex-2019: [Презентация](https://disk.yandex.ru/i/Jm8j6mEsaHiKVQ)
* Разработка робота-маркшейдера. Был создан прототип и представлена задача от Норникеля на кейс-чемпионат  Changellenge CupTechnical-2019, по результатам которого одна из команд продолжила развитие идеи.


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
### Статьи о геологии
* Научно-популярные статьи для “Коалиции авторов Росгеологии”:  [Мария Смирнова](https://blog.rusgeology.ru/authors/mariya-smirnova)
* Составление вопросов для [теста на день геолога](https://geolog23.rusgeology.ru/) и [ко дню космонавтики](https://vk.com/slateflegg?w=wall-105527557_14463) от Росгеологии. 
* Статьи в подписочную часть и несколько постов в сообщесво "[Геологи](https://vk.com/geologi)" в ВК.  
* Составление задачи по геохимии для [Пост о задаче в сообщество "Геологи"](https://vk.com/slateflegg?w=wall-129276619_27263)  
### Статьи об образовании
* [Анализ педагогического рынка труда](https://corp-univer.ru/zcnppm/our-publications/2-gde-ishchut-rabotnikov-dlya-moskovskih-shkol/). Анализ данных из тематических чатов и hh в 4-х частях.
* [Что мотивирует педагогов к профессиональному росту](https://corp-univer.ru/zcnppm/our-publications/zametki-na-polyah-neskolko-slov-o-motivah-pedagogov-k-professionalnomu-razvitiyu/). Результаты проведенного ЦНППМ социологического исследования.
Серия статей об образовательной системе ФРГ для “Вестника образования”:
* [Поездка в Германию: из магистратуры в детский сад](https://vogazeta.ru/articles/2018/11/16/international/5229-poezdka_v_germaniyu_iz_magistratury_v_detskiy_sad_chast_1)
* [Квест "Попади в университет"](https://vogazeta.ru/articles/2018/11/21/international/5274-kvest_popadi_v_universitet_obrazovatelnoe_puteshestvie_po_germanii_chast_2)



# Science
## Оглавление
[Thesises](#thesises)  
[Peer reviewed papers](#papers)  
[Achievements](#achievements)  
[Conferences papers](#conferences-papers)  
[Field Trips/Practice](#field-tripspractice)  
[Projects](#projects)  

### thesises
**Master thesis** «Olivine and clinopyroxene of the Phanerozoic ultramafic lamprophyres (South-Wes Siberia): composition, zonality, and formation» (in Russian) [[thesis](https://www.dropbox.com/s/djyecsj4f0e5tq0/Master%20thesis%20Smirnova.pdf?dl=0 "https://www.dropbox.com/s/djyecsj4f0e5tq0/Master%20thesis%20Smirnova.pdf?dl=0"); [presentation](https://www.dropbox.com/s/xvxgm8hzw69p7tu/Master%20thesis%20Smirnova%20pres.pdf?dl=0 "https://www.dropbox.com/s/xvxgm8hzw69p7tu/Master%20thesis%20Smirnova%20pres.pdf?dl=0")]

**Bachelor thesis** «Petrology and geochemistry of quaternary Baydara volcanic center, Kamchatka» (in Russian) [[thesis](https://www.dropbox.com/s/xeyylpf95dvxkwc/Bachalor%20thesis%20Smirnova.pdf?dl=0 "https://www.dropbox.com/s/xeyylpf95dvxkwc/Bachalor%20thesis%20Smirnova.pdf?dl=0"); [presentation](https://www.dropbox.com/s/hblgy1p3y0bkgzd/Bachalor%20thesis%20Smirnova%20pres.pdf?dl=0 "https://www.dropbox.com/s/hblgy1p3y0bkgzd/Bachalor%20thesis%20Smirnova%20pres.pdf?dl=0")]

### Papers

·         Хамардюк, А. В., Селиверстова, И. В., Cмирнова, М. Д., & Карпова, А. П. (2023). ИСПОЛЬЗОВАНИЕ ЦИФРОВЫХ ТЕХНОЛОГИЙ ПРИ ФОРМИРОВАНИИ ИНФОРМАЦИОННОЙ БАЗЫ АНАЛИЗА КАДРОВОГО РАЗВИТИЯ СФЕРЫ ОБРАЗОВАНИЯ. Вестник Московского городского педагогического университета. Серия: Информатика и информатизация образования, (3 (65)), 41-56. [Страница статьи на сайте журнала.](https://dlt.mgpu.ru/2023/11/01/ispolzovanie-czifrovyh-tehnologij-pri-formirovanii-informaczionnoj-bazy-analiza-kadrovogo-razvitiya-sfery-obrazovaniya/)  

·         Толстых М.Л., Бабанский А.Д., Смирнова М.Д и др. (2023) «Вулканизм начальной фазы заложения северного сегмента субдукции Тихоокеанской плиты (полуостров Камчатка, хребет Кумроч). Вулканология и сейсмология №2 стр. 52-68.

·         Butvina V.G., Smirnova M.D., Safonov O.G., Van K.V. (2019). Experimental modeling of subsolidus parageneses of ultramafic lamprophyres of the Irkeneeva-Chadobets trough, South -Western Siberia, at high PT-parameters. Experiment in GeoSciences 25.1, 51-54 [[paper](https://www.dropbox.com/s/z0e6betbvk0ew8e/Experimental%20modeling%20of.pdf?dl=0 "https://www.dropbox.com/s/z0e6betbvk0ew8e/Experimental%20modeling%20of.pdf?dl=0")]

·         Nosova, A. A., Sazonova, L. V., Kargin, A. V., Smirnova, M. D., Lapin, A. V., & Shcherbakov, V. D. (2018). Olivine in ultramafic lamprophyres: chemistry, crystallisation, and melt sources of Siberian Pre-and post-trap aillikites. Contributions to Mineralogy and Petrology, 173(7), 1-27 [[paper](https://www.researchgate.net/publication/325856415_Olivine_in_ultramafic_lamprophyres_chemistry_crystallisation_and_melt_sources_of_Siberian_Pre-_and_post-trap_aillikites "https://www.researchgate.net/publication/325856415_Olivine_in_ultramafic_lamprophyres_chemistry_crystallisation_and_melt_sources_of_Siberian_Pre-_and_post-trap_aillikites")]

·         Каргин, А. В., Носова, А. А., Постников, А. В., Чугаев, А. В., Постникова, О. В., Попова, Л. П., ... & Смирнова, М. Д. (2016). Девонские ультрамафические лампрофиры Иркинеево-Чадобецкого прогиба юга-запада Сибирской платформы: возраст, состав и значение для прогноза алмазоносности. Геология рудных месторождений, 58(5), 430-450. [[paper](https://www.dropbox.com/s/dydk6czd45jv5xp/%D0%94%D0%B5%D0%B2%D0%BE%D0%BD%D1%81%D0%BA%D0%B8%D0%B5%20%D1%83%D0%BB%D1%8C%D1%82%D1%80%D0%B0%D0%BC%D0%B0%D1%84%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5%20%D0%BB%D0%B0%D0%BC%D0%BF%D1%80%D0%BE%D1%84%D0%B8%D1%80%D1%8B%20%D0%98%D1%80%D0%BA%D0%B8%D0%BD%D0%B5%D0%B5%D0%B2%D0%BE-%D0%A7%D0%B0%D0%B4%D0%BE%D0%B1%D0%B5%D1%86%D0%BA%D0%BE%D0%B3%D0%BE.pdf?dl=0 "https://www.dropbox.com/s/dydk6czd45jv5xp/%D0%94%D0%B5%D0%B2%D0%BE%D0%BD%D1%81%D0%BA%D0%B8%D0%B5%20%D1%83%D0%BB%D1%8C%D1%82%D1%80%D0%B0%D0%BC%D0%B0%D1%84%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5%20%D0%BB%D0%B0%D0%BC%D0%BF%D1%80%D0%BE%D1%84%D0%B8%D1%80%D1")]


### Achievements

§  April, 2019. Got Early career scientist’s travel support (ECSTS) for European Geosciences Union (EGU) General Assembly.

§  April, 2017. Got Early career scientist’s travel support (ECSTS) for European Geosciences Union (EGU) General Assembly.

§  February, 2017. 4th place in English-language popular geology presentation contest, MSU with “Ontogeny of minerals. The new stage of understanding of natural phenomena”. [[presentation](https://www.dropbox.com/s/89qkjfq9t4lb8h5/Ontogeny%20of%20minerals.pdf?dl=0 "https://www.dropbox.com/s/89qkjfq9t4lb8h5/Ontogeny%20of%20minerals.pdf?dl=0")]

§  December, 2016 «The best presentation at the conference», New in the knowledge of ore formation processes. [[paper](https://www.dropbox.com/s/ruyy2tyss0dw698/IGEM-2016-thesis.pdf?dl=0 "https://www.dropbox.com/s/ruyy2tyss0dw698/IGEM-2016-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/k3kd9ovk8ds0ivy/IGEM-2016-pres.pdf?dl=0 "https://www.dropbox.com/s/k3kd9ovk8ds0ivy/IGEM-2016-pres.pdf?dl=0")]

§  April, 2016. Diploma of the winner. Competition of scientific works of the Faculty of Geology of Moscow State University in the nomination "the best presentation at the XXIII international scientific conference of students, graduate students and young scientists "Lomonosov", section "Geology". [[presentation](https://www.dropbox.com/s/bkvb2j6egxo5sg6/DS-2016-pres.pdf?dl=0 "https://www.dropbox.com/s/bkvb2j6egxo5sg6/DS-2016-pres.pdf?dl=0")]

§  April, 2016. Innovation mining contest “Lomonosov”, final stage.

§  April, 2015. Diploma of the winner. Competition of scientific works of the Faculty of Geology of Moscow State University in the nomination "the best presentation at the XXIII international scientific conference of students, graduate students and young scientists "Lomonosov", section "Geology". [[paper](https://www.dropbox.com/s/s058pe4qw6wqsc1/Lomonosov-2015-thesis.pdf?dl=0 "https://www.dropbox.com/s/s058pe4qw6wqsc1/Lomonosov-2015-thesis.pdf?dl=0"); [presentation](https://www.dropbox.com/s/s058pe4qw6wqsc1/Lomonosov-2015-thesis.pdf?dl=0 "https://www.dropbox.com/s/s058pe4qw6wqsc1/Lomonosov-2015-thesis.pdf?dl=0")]

§  2015, April. Universiade "Lomonosov". Field of knowledge: geology, winner.

### Conferences papers

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

### Field Trips/Practice

·      2016, June. Altai, «Geology, magmatism and metallogeny of Gorny Altai»

·      2015, August, Kola peninsula. «Alkaline Magmatism of the Kola peninsula and related strategic deposits»

·      2014, Summer, Kamchatka. Geological research Shiveluch area and collecting samples for bachelor paper

·      2014, June (3 weeks). Institute of Experimental Mineralogy RAS «Experimental petrology»

·      2013, Summer (4 weeks). South Ural «Field methods of studying igneous complexes»

·      2013, Summer (6 weeks). Crimea «Field methods (geological including drilling, geophysical and applied physical training)»

·      2012, June-July. Crimea «General Geology»

### Projects

Found and manage pop-science lectorium «Лекторий молодых учёных», Фестиваль науки 2015 - 2019
