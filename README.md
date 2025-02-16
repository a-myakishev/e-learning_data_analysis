# Расчет метрик и анализ результатов A/B-теста для сервиса онлайн-обучения

## Overview
В этом проекте решено три основных задачи:
1. Расчет метрик и краткий анализ на основе данных из БД
2. Написание функций для автоматического пересчета метрик и отрисовки графиков
3. Анализ результатов A/B-теста и принятие решения: внедрять или не внедрять новую механику оплаты

## Стек
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=FFA500)
![Seaborn](https://img.shields.io/badge/Seaborn-444876?logo=seaborn&logoColor=white&style=for-the-badge)
![Scipy](https://img.shields.io/badge/Scipy-003786?logo=Scipy&logoColor=white&style=for-the-badge)
![Clickhouse](https://img.shields.io/badge/clickhouse-FFF?style=for-the-badge&logo=Clickhouse&color=333333)

## Проделанная работа
### Анализ результатов A/B-теста:
+ Провел EDA и проверил данные на наличие ошибок
+ Подготовил данные для работы
+ Подобрал метрики для анализа
+ Провел расчет метрик на основе данных
+ Изучил различия в метриках между группами
+ Подобрал статистические тесты, чтобы проверить статзначимость различий
+ Проверил статзначимость различий между группами с помощью Bootstrap
+ Сделал вывод по результатам анализа
### Расчет метрик на основе данных из БД:
+ Написал SQL-код для подсчета количества наиболее активных студентов
+ Написал SQL-код для расчета метрик ARPU, ARPAU и CR в покупку
### Написание функций для пересчета метрик и отрисовки графиков
+ Написал и продемонстрировал работу обеих функций

## Результаты
1. Проанализировал результаты A/B-теста. Анализ показал, что механика оплаты в тестовой группе статистически значимо не повышает метрики, поэтому новую механику оплаты не нужно вводить.
2. Написал функции и SQL-код для перерасчета метрик. Это позволит быстро рассчитать нужные метрики, если в будущем нужно будет проводить A/B-тест с похожими данными.
