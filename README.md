# Определение возраста покупателей

## Описание проекта
Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:

* Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
* Контролировать добросовестность кассиров при продаже алкоголя.

## Задача
Необходимо постройть модель, которая по фотографии определит приблизительный возраст человека и добиться значения MAE на тестовой выборке не больше 8. В нашем распоряжении набор фотографий людей с указанием возраста.


## Вывод
Лучше всего себя показала модель `Xception` т.к. у нее самые "плавные" графики сходимости и наименьший `MAE` из рассмотренных моделей.

При обучении `Xception` мы добились значения `MAE` $2.5498$ на обучающей выборке и $5.7452$ на тестовой.
