# Исследование корреляции знаков зодиака студентов ФГГТ с выбранным (или предполагаемым) направлением их обучения

Проект посвящён исследованию взаимосвязи знаков зодиака студентов факультета Географии и геоинформационных технологий с выбором их будущей специальности, избираемой по окончании 2 курса. Изначальная идея проекта была построена на замечании, что многие ребята, которые выбирают для себя физическую географию в качестве дальнейшего направления обучения, являются представителями знака зодиака козерог (земная стихия). Это и натолкнуло авторов этого проекта выяснить: правда ли это? А также узнать какие знаки зодиака преобладают на других направлениях (ГИС, общественная география).

## Датасет
Первичные данные были собраны в результате опроса студентов, по средствам гугл-формы, в которой участникам проекта предлагалось указать:
1) Курс обучения
2) Дату рождения
3) Выбранное (или предполагаемое) направление обучение

В результате удалось собрать данные 99 опрошенных, которые впоследствии и использовались нами.

## Задачи

1) Сбор данных (создание гугл-формы и таблицы, в которую записывались результаты опроса)
2) Первичная обработка собранных данных (перевод формата гугл-таблицы в txt и последующие преобразования в python)
3) Дробление данных для отдельного рассмотрения ответов младших курсов (1-2), которые ещё находятся в стадии выбора направления, и страших (3-4 + выпускники), уже определившихся с интересующей отраслью в географии
4) Создание встроенных кортежей (для определения временных границ каждого знака зодиака и дат рождения студентов)
5) Создание вложенных списков 
6) Основная часть кода
7) Визуализация полученных данных с помощью библиотеки Matplotlib
8) Анализ итоговых результатов

## Список авторов

Смирнова Анна - *опытный программист и астролог со стажем*

Широкова Мария - *таролог и идейный вдохновитель*
