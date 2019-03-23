![alt text](energystar.jpg)

Проект создан на основе серии статей на medium ['A Complete Machine Learning Project Walk-Through in Python'](https://towardsdatascience.com/a-complete-machine-learning-walk-through-in-python-part-one-c62152f39420).
Задача проекта - построить модель, предсказывающую рейтинг энергоэффективности (Energy Star Score) для зданий в Нью-Йорке.

Часть первая: Очистка и подготовка данных. Генерация и выбор признаков.
 * В первом случае отбор признаков осущствляется без PCA - это подход оригинальной статьи. Позволяет сохранять исходные признаки, делает решение прозрачнее.
 * Во втором случае PCA позволяет сократить число признаков до 3-ех, сохранив 99% диспресии

Часть вторая: Подбор модели, доводка ее параметров через решетчатый поиск

Часть третья:

[Исходные данные](https://data.cityofnewyork.us/Environment/Energy-and-Water-Data-Disclosure-for-Local-Law-84-/8u86-bviy)

