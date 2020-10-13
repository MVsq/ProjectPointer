# Примеры работ

Список последних проектов в хронологической последовательности

---

## Спортивный анализ данных. Kaggle in-class соревнование

### [Репозиторий курса](https://github.com/Nickel-nc/GU_Sport_DS)

Полный цикл анализа данных, генерация, тестирование признаков и выстраивание пайплайна обработки данных.

**Технологии**: OOP, EDA, Feature engineering, Feature selection (shap, PI, WOE, AUC), Model ensembling, xgb, catboost, lgbm 

---

## Введение в NLP. Проект по созданию telegram Чат-бота 

### [Репозиторий курса](https://github.com/Nickel-nc/GU_NLP)
Практический курс по обработке естесственного языка. По итогу написан чат-бот-болталка. Функционал: поддержика разговора за счёт small-talk из DialogFlow, основной режим болталки реализован на парсинге "ответов mailru" (1.5 kk строк). За фактологическими ответами программа использует запросы в яндекс-поисковик.

**Технологии, использованные в курсе**: Word2vec, Fasttext, Annoy, pymorpy, nltk, keras Conv1d, SimpleRNN, LSTM, GRU, seq2seq, Attention Transformer, Bert

---

## Рекомендательные системы. Проект создания RecSys в ритейле 

### [Репозиторий курса](https://github.com/Nickel-nc/GU_Rec_Systems)
Практический курс по рекомендательным системам. Разработаны 1 и 2-х уровневые модели для рекомендаций (в итоге использована 1-уровневая модель). Решение представлено в виде python-модулей, развернутого jupiter-блокнота, и docker-контейнера.

**Технологии, использованные в курсе**: implicit ItemItemRecommender, lightgbm, docker

---

## ParkOn projcet. Computer vision проект по детектированию парковки автомобилей 

### [Репозиторий проекта](https://github.com/Nickel-nc/ParkOn_proj)
Самостоятельный проект в области computer vision (object detection). Командный проект в области создания MVP продукта, подготовленный в рамках кросс-функциональной стажировки, видео ряд для модели брался с ip веб-камеры команды. Общая схема реализации: подключение к камере по rtsp-потоку в реальном времени, кадры с заданным интервалом подаются в модель MaskRCNN на детектирования автомобилей в заданной области, расчитывается пересечение с областью парковки, результат кодируется и передается в базу MongoDB для дальнейшей передачи во front end, реализованный на flask. В модуле также реализован threading для подключения дополнительных камер.

В качестве бейзлайн решения использована предтренерованная модель на весах *coco*, реализованная на архитектуре MaskRCNN от matterport. Модель была адаптирована для запуска на tensorflow 2.x, написан алгоритм подсчета мест в заданной области, а также вспомогательные модули для тестирования и покадровой сборки видео. Также есть более стабильный сниппет для модели Yolo-4 на darknet от AlexeyAB.

**Технологии, использованные и тестированные в проекте**: MRCNN, YOLO-4, YOLO-5, MongoDB, Flask, threading

---

## Практический курс Computer Vision 

### [Репозиторий курса](https://github.com/Nickel-nc/GU_Deep_Learning_In_Computer_Vision)
Практический курс, покрывающий основные задачи машинного зрения. По сути, это low-level implementation и тестирование рабочих примеров, продолжение курса deep learning

**Технологии, использованные в курсе**: tensorflow-gpu, tensorflow api, keras, Object Detection, Semantic Segmentation, Metric Learning, Video classification, GAN

---

## Практический курс Deep Learning

### [Репозиторий курса](https://github.com/Nickel-nc/GU_Introduction_To_Neural_Networks)
Вводный курс в технологии глубокого обучения. Здесь представлена имплементация основных архитектур для решения задач DL. 

**Технологии, использованные в курсе**: tf, keras, классификация изображений, Semantic Segmentation, Text Generation, Image Generation

---

## Курсовой проект - кейс от компании Мегафон

### [Блокнот с решением](https://github.com/Nickel-nc/GU_Megafon_Case/blob/master/YN_Megafon_Project.ipynb)
#### [Презентация к проекту](https://github.com/Nickel-nc/GU_Megafon_Case/blob/master/Project_Description.pdf)
Задача классификации на определение вероятности приобретения услуг компании по профилю потребления абонента на обезличенных данных. Практика обработки больших объемов данных.

**Технологии**: dask, luigi, catboost, ADASYN, shap

---

## Курс ML в Production. Курсовой проект - задача оттока для игровой online индустрии

### [Страница проекта](https://github.com/Nickel-nc/GU_ML_In_Production/tree/master/ChurnedPlayersPredictionModel)
Модульная реализация модели на консольном управлении с режимами сборки, обучения/тюнинга и предсказания c отслеживанием логов и кастомной настройкой на xgboost.

**Технологии**: xgboost, logger, GridSearch, Feature Selection (WOE, PI)

---

## Практический курс по сбору данных в интернете. Parcing, Scrapping, Crawling 

### [Репозиторий с решениями](https://github.com/Nickel-nc/GU_PSC/tree/PSC_Task_7)
В рамках курса опробованы ключевые технологии по сбору данных: подключение по api к различным сервисам; парсеры вакансий для hhru и superjob; краулер по сбору объявлений с изображениями с avito; сбор почты из яндекс-ящика 

**Технологии**: API’s, scrapy, Beatiful Soup, Selenium, db’s - sql, mongo, curl, postman
