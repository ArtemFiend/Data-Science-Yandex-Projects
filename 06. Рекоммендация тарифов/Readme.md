# Рекомендация тарифов

Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

## Цель исследования:

Постройте модель с максимально большим значением *accuracy*. Чтобы сдать проект успешно, нужно довести долю правильных ответов по крайней мере до 0.75. Проверьте *accuracy* на тестовой выборке самостоятельно.v

## Итог исследования:

Лучшие показатели на тестовой выборке показала модель случайного леса с точностью `0.8`.

Для предсказаний, стоит пользоваться моделью случайного дерева с параметрами: 
* количество деревьев - `26`
* глубина - `7`

## Стек технологий:

Pandas, matplotlib, numpy, seaborn, scikit-learn, logistic regression.
