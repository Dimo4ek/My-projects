
## English - the name, description of the project, libraries and tools used, the output of the project and the status of the project

# Identifying negative user comments
It is required to train the model to classify comments into positive and negative.
The customer is an online store that launches a new service. Now users can edit and supplement product descriptions, as in wiki communities. That is, clients offer their edits and comment on the changes of others.
The store needs a tool that will search for toxic comments and send them for moderation.
At your disposal is a data set with markup on the toxicity of edits.
The requirement for the model is that the value of the F1 quality metric is not less than 0.75.


### Libraries used in the study
* CatBoost
* Lightdm
* nltk
* NumPy
* Pandas
* Python
* Scikit-learn
* re
* Space
* Torch
* Transformers

### Conclusion
The best results of the F1-score metric were obtained on the length of texts in 1000 characters.
I've done some experiments with the length of texts 5000, 2000, 1000, 500, 300, 220, 200, 190, 180, 150 and 100 characters.
We have an imbalance of classes.
I tried to use models with class balance and without balance.
The best result of the model was achieved in the Light GBL model with TF-IDF without class balance, the value of F1-score = 0.756317.
According to the terms of reference, it was necessary to reach the value of F1-score = 0.75.
The remaining models did not reach the desired indicator, both with a balance of classes and without a balance.

## Project status - completed
<br>

## Русский - название, описание проекта, используемые библиотеки и инструменты, вывод проекта и статус проекта

#  Определение негативных комментариев пользователей
Требуется обучить модель классифицировать комментарии на позитивные и негативные.
Заказчик - это интернет-магазин, который запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других.
Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.
В вашем распоряжении набор данных с разметкой о токсичности правок.
Требование к модели - значением метрики качества F1 не меньше 0.75.


### Используемые библиотеки в исследовании
* CatBoost
* Lightdm
* nltk
* NumPy
* Pandas
* Python
* Scikit-learn
* re
* Space
* Torch
* Transformers

### Вывод
Наилучшие результаты метрики F1-score получились на длине текстов в 1000 символов.
Я провел несколько экспериментов с длиной текстов 5000, 2000, 1000, 500, 300, 220, 200, 190, 180, 150 и 100 символов.
У нас наблюдается дисбаланс классов.
Модели пробовал применять с балансом классов и без баланса.
Лучший результат модели был достигнут в модели Light GBL с TF-IDF без баланса классов, значение F1-score = 0.756317.
По техническому заданию нужно было достигнуть значения F1-score = 0.75.
Остальные модели не достигли нужного показателя, как с балансом классов, так и без баланса.

## Статус проекта - завершен
