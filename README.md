# Проекты
## Сравнение поведения пользователей Яндекс Музыки из Москвы и Санкт-Петербурга

На данных Яндекс.Музыки c помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей Москвы и Санкт-Петербурга.

## Исследование надежности заемщиков банка

На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок.

## Предсказание коэффициента восстановления золота
Подготовка прототипа модели машинного обучения для компании «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.
Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. Предоставлены данные с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

## Исследование объявлений о продаже квартир
Используя данные сервиса Яндекс.Недвижимость (архива объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет) нужно научиться определять рыночную стоимость объектов недвижимости. 

## Определение возраста покупателей по фотографиям
Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя. Строится модель, которая по фотографии определит приблизительный возраст человека. В распоряжении набор фотографий людей с указанием возраста.

## Прогнозирование оттока клиентов телеком компании
Компания стремится создать модель, которая помогла бы выявлять клиентов, которые могут решить перейти к другому оператору, с целью предлагать им специальные промокоды и условия. Главная цель заказчика заключается в том, чтобы удерживать своих текущих клиентов и увеличивать прибыль за счет этого.

## Обучение модели классификации комментариев
Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.
`nltk` `tf-idf`

## Прогнозирование количества заказов такси на следующий час
Компания такси собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Необходимо построить модель для такого предсказания. `Scikit-learn` `statsmodels`

## Определение выгодного тарифа для телеком компании
Проведен предварительный анализ использования тарифов на выборке клиентов,
проанализировано поведение клиентов при использовании услуг оператора и
рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка
данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и
различии выручки абонентов из Москвы и других регионов.
`Matplotlib` `NumPy` `SciPy` `описательная статистика` `проверка статистических гипотиз`

## Иссдование закономерностей определяющих успешность игры
Исслледование для интернет-магазина, который продаёт по всему миру компьютерные игры. Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. `Matplotlib` `NumPy` `SciPy` `описательная статистика` `проверка статистических гипотиз`

## Рекомендация тарифов мобильной связи
Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра». Предоставлены данные о поведении клиентов, которые уже перешли на эти тарифы.
Необходимо построить модель с максимально большим значением accuracy.   `sklearn`  `RandomForestClassifier` `LogisticRegression` `DecisionTreeClassifier`

## Прогнозирование оттока клиента банка
Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. `sklearn`  `RandomForestClassifier` `LogisticRegression` `DecisionTreeClassifier` `Matplotlib` `seaborn` `NumPy`

## Выбор локации для скважины
Компания «ГлавРосГосНефть» занимается добычей нефти. Нужно решить, где бурить новую скважину.
Предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Нужно построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль.
`Pandas`, `Scikit-learn`, `бутстреп`

## Защита данных клиентов страховой компании
Необходимо защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.
`Pandas`, `Scikit-learn`, `NumPy`
 ## [Предсказание стоимости автомобиля] (https://github.com/NataliaKulikovskaya/Yandex_projects/tree/main/Car%20value%20predictio/)
 Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля.
 `Pandas`, `Scikit-learn`, `lightgbm`
