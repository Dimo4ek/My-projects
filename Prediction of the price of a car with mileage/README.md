
## English - the name, description of the project, libraries and tools used, the output of the project and the status of the project

# Prediction of the price of a car with mileage
We need to build a model to determine the cost of cars. The service for the sale of used cars is developing an application to attract new customers. In it, you can quickly find out the market value of your car. Historical data is at your disposal: technical specifications, complete sets and prices of cars.

### Used libraries and tools in research
* CatBoost
* Lightdm
* Matplotlib
* NumPy
* Pandas
* Python
* Seaborn
* Scikit-learn

### Conclusion
The best quality result is the average model error(RMSE) of the CatBoostRegressor model (loss_function="RMSE", iterations=1000, depth=10, random_state=12345), its prediction speed is also very high, but it takes a long time to learn.
The LGBMRegressor model has the second quality result(n_estimators=100, num_leaves=20, class_weight='balanced', random_state=12345), the prediction speed and training time are slightly higher than the best quality model.
The third result is the quality of the LinearRegression() model, although the quality is already much worse than the best quality model, the prediction speed is the fastest, but the training time is also significant.
Models RandomForestClassifier(class_weight='balanced', max_depth=6, n_estimators=1, random_state=12345) and DecisionTreeClassifier(class_weight='balanced', max_depth=3, random_state=12345) the quality is almost 3 times worse than the CatBoost model.
I think CatBoost is the most optimal model for the task, because the quality result is the highest, the prediction time is the second fastest, and the training time is not so long to give up the first two more significant advantages.

## Project status - completed
<br>

## Русский - название, описание проекта, используемые библиотеки и инструменты, вывод проекта и статус проекта

#  Предсказание цены машины с пробегом
Нам нужно построить модель для определения стоимости автомобилей. Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В вашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей.

### Используемые библиотеки и инструменты в исследовании
* CatBoost
* Lightdm
* Matplotlib
* NumPy
* Pandas
* Python
* Seaborn
* Scikit-learn

### Вывод
Наилучший результат качества - средняя ошибка модели(RMSE) у модели CatBoostRegressor(loss_function="RMSE", iterations=1000, depth=10 , random_state=12345), скорость предсказания у неё тоже очень высокая, но долгое время обучения.
Второй результат по качеству у модели LGBMRegressor(n_estimators=100, num_leaves=20, class_weight='balanced', random_state=12345), скорость предсказания и время обучения немного выше, чем у лучшей модели по качеству.
Третий результат по качеству у модели LinearRegression(), хотя качество уже значительно хуже, чем у лучшей модели по качеству, скорость предсказания самая быстрая, но время обучения тоже значительное.
Моделей RandomForestClassifier(class_weight='balanced', max_depth=6, n_estimators=1, random_state=12345) и DecisionTreeClassifier(class_weight='balanced', max_depth=3, random_state=12345) качество хуже модели CatBoost в почти в 3 раза.
Самой оптимальной моделью для поставленной задачи считаю CatBoost, тк результат качества самый высокий, время предсказания второе по скорости, а время обучение не столь большое, чтобы отказываться от первый двух более значительных плюсов.

## Статус проекта - завершен
