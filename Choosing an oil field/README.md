
## English - the name, description of the project, libraries and tools used, the output of the project and the status of the project
# Choosing an oil field
The customer is an oil producing company. We need to decide for them where to drill a new well.

We were provided with oil samples in three regions: in each 100,000 fields, where the quality of oil and the volume of its reserves were measured. It is required to build a machine learning model that will help determine the region where mining will bring the greatest profit. It is required to analyze the possible profits and risks with the Bootstrap technique.

Steps to select a location:

* Deposits are being searched for in the selected region, the values of the signs are determined for each;
* Build a model and estimate the volume of stocks;
* The deposits with the highest value estimates are selected. The number of deposits depends on the company's budget and the cost of developing one well;
* The profit is equal to the total profit of the selected fields.

Task conditions:

* Only linear regression is suitable for training the model (the rest are not predictable enough).
* During the exploration of the region, 500 points are explored, from which 200 best ones are selected for development using machine learning.
* The budget for the development of wells in the region is 10 billion rubles.
* At current prices, one barrel of raw materials brings 450 rubles of income. The income from each unit of the product is 450 thousand rubles, since the volume is indicated in thousands of barrels.
* After assessing the risks, you need to leave only those regions in which the probability of losses is less than 2.5%. Among them, the region with the highest average profit is chosen.

Synthetic data: details of contracts and characteristics of deposits are not disclosed.


### Libraries used in the study
* Matplotlib
* NumPy
* Pandas
* Python
* Scikit-learn
* SciPy

### Conclusion
Based on the conducted research and calculations, I propose to develop deposits in the second region.

Justifications for choosing a region:
Despite the fact that in this region the profit on the top 200 wells is the smallest of the three regions and amounts to 2415086696.68 rubles, but in this region we have the least risk of making a loss.
The risk of loss in the second region is only 0.3%, which is about 20 times lower than the risks of the first and third regions.
Such low risks are associated with the fact that in the second region the square root of the average quadratic error is only 0.89 thousand barrels, which is 40-45 times less than in the first and third regions.

## Project status - completed
<br>

## Русский - название, описание проекта, используемые библиотеки и инструменты, вывод проекта и статус проекта.

#  Выбор месторождения нефти
Заказчик - нефтедобывающая компания. Нужно решить для них, где бурить новую скважину.

Нам предоставлены пробы нефти в трёх регионах: в каждом 100 000 месторождений, где измерили качество нефти и объём её запасов. Требуется построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Требуется проанализировать возможную прибыль и риски техникой Bootstrap.

Шаги для выбора локации:

* В избранном регионе ищут месторождения, для каждого определяют значения признаков;
* Строят модель и оценивают объём запасов;
* Выбирают месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
* Прибыль равна суммарной прибыли отобранных месторождений.

Условия задачи:

* Для обучения модели подходит только линейная регрессия (остальные — недостаточно предсказуемые).
* При разведке региона исследуют 500 точек, из которых с помощью машинного обучения выбирают 200 лучших для разработки.
* Бюджет на разработку скважин в регионе — 10 млрд рублей.
* При нынешних ценах один баррель сырья приносит 450 рублей дохода. Доход с каждой единицы продукта составляет 450 тыс. рублей, поскольку объём указан в тысячах баррелей.
* После оценки рисков нужно оставить лишь те регионы, в которых вероятность убытков меньше 2.5%. Среди них выбирают регион с наибольшей средней прибылью.

Данные синтетические: детали контрактов и характеристики месторождений не разглашаются.


### Используемые библиотеки в исследовании
* Matplotlib
* NumPy
* Pandas
* Python
* Scikit-learn
* SciPy

### Вывод
На основании проведённого исследования и расчётов предлагаю производить разработку месторождений во втором регионе.

Обоснования выбора региона:
Не смотря на то, что в данном регионе прибыль на 200 лучших скважинах наименьшая из трёх регионов и составляет 2415086696.68 рублей, но в данном регионе мы имеем наименьшие риски получить убыток.
Риск убытка во втором регионе составляет всего 0,3%, что примерно в 20 раз ниже рисков первого и третьего регионов.
Такие низкие риски связаны с тем, что во втором регионе квадратный корень из средней квадратичной ошибки составляет всего 0.89 тыс. баррелей, что 40-45 раз меньше, чем в первом и третьем регионе.

## Статус проекта - завершен
