# Защита данных клиентов страховой компании

Нужно защитить данные клиентов страховой компании. Необходимо разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию, при этом качество моделей машинного обучения не должно ухудшиться. 

## Данные

Признаки: пол, возраст и зарплата застрахованного, количество членов его семьи.
Целевой признак: количество страховых выплат клиенту за последние 5 лет.

## Задача

Разработка модели анонимизации персональных данных

## Используемые библиотеки
*pandas, numpy, scikit-learn*

## Результаты
Предложен способ преобразования данных, основанный на свойствах умножения матриц. Качество модели при этом не страдает.
