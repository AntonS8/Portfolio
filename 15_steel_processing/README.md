# Исследование надежности заемщиков

[HTML](https://github.com/AntonSA888/Portfolio/blob/main/15_steel_processing/steel_processing.html) [ipynb](https://github.com/AntonSA888/Portfolio/blob/main/15_steel_processing/steel_processing.ipynb)

## Описание проекта

Построили модель, которая предсказывает конечную температуру стального сплава (задача регрессии).

## Навыки и инструменты

- python
- pandas
- numpy
- matplotlib
- lightgbm
- sklearn.model_selection
- sklearn.dummy
- sklearn.tree
- sklearn.linear_model
- sklearn.pipeline
- sklearn.metrics
- sklearn.preprocessing
- sklearn.compose
- seaborn
- shap
- phik

## Общий вывод

- Изучили данные, проверили их на предмет аномалий и несоответствий.
- Произвели исследовательский анализ и предобработку данных.
- Отобрали нужные признаки для обучения моделей и сгенерировали новые.
- Подготовили данные и обучили 3 модели, используя кроссвалидацию и перебор гиперпараметров с помощью GridSearchCV:
  - LinearRegression;
  - LightGBM;
  - DecisionTree.
- Выбрали лучшую модель и произвели анализ важности признаков.


