# ML-project

Итоговый проект курса "Машинное обучение в бизнесе"

Стек:

ML: sklearn, pandas, numpy
API: flask
Данные: с kaggle - https://www.kaggle.com/ealaxi/paysim1

Задача: предсказать, является ли операция мошеннической (целевая переменная 'isFraud' - 1). Бинарная классификация

Используемые признаки:

- type_CASH_IN (int) 
- type_CASH_OUT (int) 
- type_DEBIT (int) 
- newbalanceDest (int) 
- isFlaggedFraud (int)


Преобразования признаков: RandomOverSampler, StandardScaler

Модель: SGDClassifier

### Клонируем репозиторий и создаем образ
```
$ git clone https://github.com/AntonKhmelev/ML-project.git
```
