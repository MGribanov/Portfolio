# Проекты Data Science
Здесь представлены выполненные мной учебные проекты Яндекс Практикум
---
## Аналитика
<details open>
<summary>Проекты по теме</summary>

|#|Проект|Тема проекта|Описание проекта|Задача проекта|Стек|
|-|------|------------|----------------|--------------|----|
|1.|[Исследование надёжности заёмщиков](001_research_on_the_reliability_of_borrowers)|Предобработка данных|Заказчик — кредитный отдел банка. Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга.|Определить, как влияет семейное положение и количество детей клиента на факт погашения кредита в срок.|`pandas`, `numpy`, `matplotlib`, `seaborn`|
|2.|[Исследование объявлений о продаже недвижимости](002_research_of_real_estate_listings)|Исследовательский анализ данных|Данные представляют собой архив объявлений сервиса Яндекс Недвижимость о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет.|Выявить зависимости существующие на рынке недвижимости для построения автоматизированной системы отслеживания аномалий и мошеннической деятельности.|`pandas`, `numpy`, `matplotlib`, `seaborn`|
|3.|[Определение перспективного тарифа сотовой связи](003_definition_of_promising_cellular_tariff)|Статистический анализ данных|Федеральный оператор сотовой связи предлагает клиентам два тарифных плана. Необходимо понять, какой тариф приносит больше денег и куда направить рекламный бюджет. Предоставлены данные пользователей за 2018-й год.|Провести анализ поведения клиентов и сделать вывод - какой тариф лучше, чтобы скорректировать рекламный бюджет.|`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`|
|4.|[Прогноз продаж в интернет-магазине](004_sales_forecast_in_the_online_store)| Сборный проект 1|Провести анализ данных, полученных из открытых источников до 2016 года, о продажах игр различных жанров для разных платформ, их оценки пользователями и экспертами.|Определить закономерности, определяющие успешность игры и найти потенциально популярный продукт для планирования рекламной компании.|`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `statsmodels`|
</details>

## Регрессия
<details open>
<summary>Проекты по теме</summary>
  
|#|Проект|Тема проекта|Описание проекта|Задача проекта|Стек|
|-|------|------------|----------------|--------------|----|
|1.|[Выбор локации для бурения скважины](005_selecting_location_for_drilling_well)|Машинное обучение в бизнесе|Добывающей компании нужно решить, где бурить новую скважину. Предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов.|Построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль, проанализировать возможную прибыль и риски.|`pandas`, `numpy`, `matplotlib`, `tqdm`, `scikit-learn`: `LinearRegression`, `Pipeline`, `StandardScaler`|
|2.|[Определение стоимости автомобилей с пробегом](006_defining_the_cost_of_used_cars)|Численные методы|Сервис по продаже автомобилей разрабатывает приложение, в котором можно быстро узнать рыночную стоимость своего автомобиля на основании исторических данных: технические характеристики, комплектации и цены автомобилей.|Построить модель для определения стоимости автомобиля.Заказчику важны: качество предсказания, скорость предсказания, время обучения.|`pandas`, `numpy`, `matplotlib`, `CatBoost`: `CatBoostRegressor`, `LightGBM`, `scikit-learn`: `RandomForestRegressor`, `LinearRegression`, `OneHotEncoder`, `OrdinalEncoder`, `MinMaxScaler`, `GridSearchCV`,`Pipeline`| 
|3.|[Модель машинного обучения для золотодобывающей компании](007_machine_learning_model_for_gold_mining_company)|Сборный проект 2|Для промышленной компании необходимо разработать прототип модели, которая поможет оптимизировать производство, чтобы не запускать предприятия с убыточными характеристиками.В распоряжении данные с параметрами добычи и очистки золотоносной руды.|Подготовить прототип модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды.|`pandas`, `numpy`, `matplotlib`, `sweetviz`, `scikit-learn`: `RandomForestRegressor`, `LinearRegression`, `DecisionTreeRegressor`, `MinMaxScaler`, `GridSearchCV`,`Pipeline`|
|4.|[Прогнозирование заказов такси](008_predicting_taxi_orders)|Временные ряды|Сделать прогноз количества заказов такси на следующий час, используя исторические данные о заказах такси в аэропортах, чтобы привлекать больше водителей в период пиковой нагрузки.|Построить модель для предсказания заказов такси на следующий час с определенным значение метрики.|`pandas`, `numpy`, `matplotlib`, `CatBoost`: `CatBoostRegressor`, `LightGBM`, `scikit-learn`: `RandomForestRegressor`, `TimeSeriesSplit`, `GridSearchCV`, `statsmodels`: `seasonal decompose`|
</details>

## Классификация
<details open>
<summary>Проекты по теме</summary>
  
|#| Название проекта | Тема проекта |	Описание проекта | Задача проекта |	Стек |
|-|------------------|--------------|------------------|----------------|------|
|1.|[Рекомендация тарифов мобильной связи](009_recommend_mobile_communication_tariffs)|Машинное обучение в бизнесе|Построить модель, способную проанализировать поведение клиентов и предложить пользователям новый тариф. В распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы.|Построить модель с определенными метриками, которая выберет для клиента подходящий тариф.|`pandas`, `matplotlib`, `sklearn`: `LogisticRegression`, `RandomForestClassifier`, `DecisionTreeClassifier`, `GridSearchCV`| 
|2.|[Прогнозирование оттока клиентов банка](https://github.com/MGribanov/Portfolio/tree/main/project_10)|Машинное обучение в бизнесе|Дать прогноз, уйдёт клиент из банка в ближайшее время или нет.Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.Предоставлены исторические данные о поведении клиентов.|Построить модель с определенными метриками, которая определит уйдет или останется клиент.|`pandas`, `matplotlib`, `sklearn`: `LogisticRegression`, `RandomForestClassifier`, `DecisionTreeClassifier`, `DummyClassifier`, `GridSearchCV`|
</details>

## Защита данных
<details open>
<summary>Проекты по теме</summary>
  
|#| Название проекта | Тема проекта |	Описание проекта | Задача проекта |	Стек |
|-|------------------|--------------|------------------|----------------|------|
|1.|[Защита персональных данных клиентов страховой компании](https://github.com/MGribanov/Portfolio/tree/main/project_11)|Линейная алгебра|Нужно защитить данные клиентов страховой компанию.|Разработать метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию|`pandas`, `numpy`, `matplotlib`, `sklearn`: `LinearRegression`|
</details>
  
## Машинное обучение для текстов
<details open>
<summary>Проекты по теме</summary>

|#| Название проекта | Тема проекта |	Описание проекта | Задача проекта |	Стек |
|-|------------------|--------------|------------------|----------------|------|
|1.|[Оценка токсичности комментариев для интернет-магазина](https://github.com/MGribanov/Portfolio/tree/main/project_12)|Машинное обучение для текстов|Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.В распоряжении набор данных с разметкой о токсичности правок.|Обучить модель классифицировать комментарии на позитивные и негативные.|`pandas`, `numpy`, `matplotlib`, `tqdm`, `sklear`n: `LogisticRegression`, `RandomForestClassifier`, `SVC`, `TfidfVectorizer`, `CountVectorizer`, `nltk`: `stopwords`, `WordNetLemmatizer`|
</details>

## Компьютерное зрение
<details open>
<summary>Проекты по теме</summary>
  
|#| Название проекта | Тема проекта |	Описание проекта | Задача проекта |	Стек |
|-|------------------|--------------|------------------|----------------|------|
|1.|[Оценка возраста покупателя сетевого супермаркета по фотографии](https://github.com/MGribanov/Portfolio/tree/main/project_13)|Компьютерное зрение|Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы, контролировать добросовестность кассиров при продаже алкоголя.|Построить модель, которая по фотографии определит приблизительный возраст человека|`pandas`,`numpy`, `matplotlib`, `os`,`seaborn`, `tensorflow`: `keras`, `ResNet50`|
</details>
