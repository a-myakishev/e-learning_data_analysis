# Расчет метрик и анализ результатов A/B-теста для сервиса онлайн-обучения

## Overview
В этом проекте решено три основных задачи:
1. Расчет метрик и краткий анализ на основе данных из БД
2. Написание функций для автоматического пересчета метрик и отрисовки графиков
3. Анализ результатов A/B-теста и принятие решения: внедрять или не внедрять новую механику оплаты

## Стек
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-blue?logo=seaborn&logoColor=white&style=for-the-badge)
![Scipy](https://img.shields.io/badge/Scipy-blue?logo=Scipy&logoColor=white&style=for-the-badge)
![Clickhouse](https://img.shields.io/badge/clickhouse-B0C4DE?style=for-the-badge&logo=clickhouse&logoColor=FFCC01)

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
1. Анализ результатов A/B-теста показал, что механика оплаты в тестовой группе статистически значимо не повышает метрики. Новую механику оплаты не вводить для всех пользователей.
2. Написанные функции и SQL-код позволят быстро рассчитать нужные метрики, если в будущем нужно будет проводить A/B-тест с похожими данными.