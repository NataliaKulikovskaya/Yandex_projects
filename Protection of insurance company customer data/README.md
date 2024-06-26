# Защита данных клиентов страховой компании
Необходимо защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы. Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.

* Приведены данные клиентов страховой компании (признаки: пол, возраст, размер зарплаты, кол-во членов семьи, кол-во страховых выплат за 5 лет), с целью является разработки метода преобразования данных, по которым было бы сложно восстановить персональную информацию.
* Анализ данных показал, что в выборке предоставлены данные примерно в равной степени о мужчинах и оженщинах. Так же большая часть данных о людях в возрасте от 18 до 35 лет, большая часть которых получают зарплату около 40 тыс. рублей. В таблице приведены данные в большей степени либо про одинких людей, либо о семьях из 2х человек. Это коррелирует с данными о возрасте, так как многие люди заводят детей после 30-35 лет.
* Было установлено, что при умножении на обратимую матрицу, качество линейной регресии не изменится.
* Предложен алгоритм защиты персональных данных клиентов.Для этого признаки умножаются на случайную квадратную обратимую матрицу с размером равным количеству столбцов в выборке с признаками.
* Проверили алгоритм. Метрика средней квадратичной ошибки при этом не ухудшилась.

`Pandas`, `Scikit-learn`, `NumPy`
