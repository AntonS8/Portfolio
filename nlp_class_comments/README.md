# Классификация комментариев интернет-магазина

[HTML](https://github.com/AntonS8/Portfolio/blob/main/nlp_class_comments/nlp_class_comments.html) [ipynb](https://github.com/AntonS8/Portfolio/blob/main/nlp_class_comments/nlp_class_comments.ipynb)

## Описание проекта

Построили модель, которая классифицирует комментарии на позитивные и негативные.

## Навыки и инструменты

- python
- pandas
- matplotlib
- sklearn.model_selection
- sklearn.dummy
- sklearn.tree
- sklearn.linear_model
- sklearn.feature_extraction.text
- sklearn.pipeline
- sklearn.metrics 
- catboost
- nltk
- spacy

## Общий вывод

- Изучили данные, проверили их на предмет аномалий и несоответствий.
- Подготовили данные и обучили 3 модели, используя кроссвалидацию и перебор гиперпараметров с помощью GridSearchCV:
  - LogisticRegression;
  - DecisionTreeClassifier;
  - CatBoostClassifier.
- Выбрали лучшую модель и проверили на тестовой выборке.


