# Прогнозирование заказов такси

[HTML](https://github.com/AntonSA888/Portfolio/blob/main/12_time_series_taxi/time_series_taxi.html) [ipynb](https://github.com/AntonSA888/Portfolio/blob/main/12_time_series_taxi/time_series_taxi.ipynb)

## Описание проекта

Построил модель, которая прогнозирует количество заказов такси на следующий час (задача регрессии для временного ряда)

## Навыки и инструменты

- python
- pandas
- matplotlib
- statsmodels.tsa.seasonal
- statsmodels.tsa.stattools
- sklearn.model_selection
- sklearn.tree
- sklearn.linear_model
- sklearn.pipeline
- sklearn.metrics
- sklearn.preprocessing
- sklearn.compose
- lightgbm

## Общий вывод

- Изучили данные, проверили их на предмет аномалий и несоответствий.
- Произвели исследовательский анализ.
- Отобрали нужные признаки для обучения моделей и сгенерировали новые.
- Подготовили данные и обучили 3 модели, используя кроссвалидацию и перебор гиперпараметров с помощью RandomizedSearchCV:
  - LinearRegression;
  - LightGBM;
  - DecisionTree.
- Выбрали лучшую модель и протестировали на тестовой выборке.


