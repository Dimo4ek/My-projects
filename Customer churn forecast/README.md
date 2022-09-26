
## English - the name, description of the project, libraries and tools used, the output of the project and the status of the project

# Customer churn forecast
Customers began to leave the customer's bank. The departure is not massive, but the rate of customer outflow has become greater than before. Bank marketers have calculated that it is cheaper to retain current customers than to attract new ones.

It is necessary to predict whether the client will leave the bank in the near future or not. You are presented with historical data on the behavior of customers and the termination of contracts with the bank.

It is necessary to build a model with an extremely large value of the F1-measure. The metric must be at least 0.59.

Additionally, you need to measure AUC-ROC, compare its value with the F1-measure.

Data source: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

### Libraries used in the study
* Matplotlib
* NumPy
* Pandas
* Python
* Scikit-learn

### Conclusion
As a result, the most successful Random Forest model with parameters max_depth=13, n_estimators=53, when training on validation and training samples with increasing samples to equalize the balance of classes, gave the value of F1-measure 0.611 and AUC-ROC 0.856.
The value of the F-measure is lower than on the same model with the same parameters, but where only a training sample was used for training, there the F1-measure value is 0.619, and the AUC-ROC value is 0.853.

## Project status - completed
<br>

## Русский - название, описание проекта, используемые библиотеки и инструменты, вывод проекта и статус проекта

#  Прогноз ухода клиентов
Из банка заказчика стали уходить клиенты. Уход не массовый, но скорость оттока клиентов стала больше, чем раньше. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам представлены исторические данные о поведении клиентов и расторжении договоров с банком.

Нужно построить модель с предельно большим значением F1-меры. Метрика должна быть не меньше 0.59.

Дополнительно нужно измерять AUC-ROC, сравнивайте её значение с F1-мерой.

Источник данных: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling



### Используемые библиотеки в исследовании
* Matplotlib
* NumPy
* Pandas
* Python
* Scikit-learn

### Вывод
В результате самая успешная модель Случайного леса с параметрами max_depth=13, n_estimators=53 при обучении на валидационной и обучающей выборке с увеличением выборок, чтобы сравнять баланс классов выдало значение F1-меры 0.611 и AUC-ROC 0.856.
Значение F-меры является более низким, чем на такой же модели с такимиже параметрами, но где для обучения использовалась только обучающая выборка, там значение F1-меры 0.619, а значение AUC-ROC равно 0.853.

## Статус проекта - завершен
