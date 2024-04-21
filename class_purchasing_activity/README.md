# Прогнозирование покупательской активности интернет-магазина

[HTML](https://github.com/AntonSA888/Portfolio/blob/main/class_purchasing_activity/class_purchasing_activity.html) [ipynb](https://github.com/AntonSA888/Portfolio/blob/main/class_purchasing_activity/class_purchasing_activity.ipynb)

## Описание проекта

Построил модель, которая предсказывает вероятность снижения покупательской активности клиента в следующие три месяца (задача классификации). Выделил сегменты покупателей и разработал для них персонализированные предложения.

## Навыки и инструменты

- python
- pandas
- numpy
- matplotlib
- sklearn.neighbors
- sklearn.tree
- sklearn.linear_model
- sklearn.svm
- sklearn.metrics
- sklearn.pipeline
- sklearn.preprocessing
- sklearn.compose
- sklearn.impute
- seaborn
- shap


## Общий вывод

- Изучили данные, проверили их на предмет аномалий и несоответствий.
- Произвели исследовательский анализ и предобработку данных.
- Подготовили данные и обучили 4 модели, используя кроссвалидацию и перебор гиперпараметров с помощью RandomizedSearchCV:
  - KNeighborsClassifier;
  - DecisionTreeClassifier;
  - LogisticRegression;
  - SVC.
- Выбрали лучшую модель и произвели анализ важности признаков.
- Произвели анализ целевой группы.


