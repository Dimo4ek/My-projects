
## English - the name, description of the project, libraries and tools used, the output of the project and the status of the project

# Mobile tariff recommendation
The mobile operator found out that many customers use archive tariffs. They want to build a system capable of analyzing customer behavior and offering users a new tariff: "Smart" or "Ultra".

You have at your disposal data on the behavior of customers who have already switched to these tariffs. You need to build a model for the classification task that will choose the appropriate tariff.

Build a model with the highest possible accuracy value. To pass the project successfully, you need to bring the proportion of correct answers to at least 0.75.

### Libraries used in the study
* NumPy
* Pandas
* Python
* Scikit-learn

### Conclusion
We have built several models for the classification task that will choose the appropriate tariff.

In the terms of reference, the accuracy requirement was 0.75.

The models that were trained earlier were tested on the test sample - a training tree, a random forest and logistic regression.

They all had accuracy above 0.75.

In the test sample, the random forest model with the index `accuracy - 0.79` turned out to be the most accurate.

At the same time, on the validation sample, the logistic regression model gave an accuracy of less than 0.75, therefore it should not be used for classification.

For classification, you can use the training tree and random forest models, but the random forest model had the highest accuracy in the validation and test sample.

## Project status - completed

<br>

## Русский - название, описание проекта, используемые библиотеки и инструменты, вывод проекта и статус проекта

#  Рекомендация мобильного тарифа
Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

В вашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы. Нужно построить модель для задачи классификации, которая выберет подходящий тариф.

Постройте модель с максимально большим значением точность. Чтобы сдать проект успешно, нужно довести долю правильных ответов по крайней мере до 0.75.

### Используемые библиотеки в исследовании
* NumPy
* Pandas
* Python
* Scikit-learn

### Вывод
Мы построили несколько моделей для задачи классификации, которые выберут подходящий тариф. 

В техническом задании требование к точности составляло 0.75.

На тестовой выборке были проверены модели, которые обучали ранее - обучающее дерево, случайный лес и логистическая регрессия.

У них у всех точность была выше 0.75.

На тестовой выборке самой точной оказалась модель случайный лес с показателем `accuracy - 0.79`.

При этом на валидационной выборке модель логистической регрессии выдавала точность менее 0.75, следовательно её не стоит исспользовать для классификации.

Для классификации можно взять модели обучающее дерево и случайный лес, но самая высокая точность на валидационной и тестовой выборке была у модели случайный лес.

## Статус проекта - завершен
