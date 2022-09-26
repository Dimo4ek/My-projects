## English - the name, description of the project, libraries and tools used, the output of the project and the status of the project

# Forecast of the number of taxi orders
It is required to develop a model to predict the number of orders for the next hour for a taxi. The customer provided historical data on taxi orders at airports. The customer needs the results of the study in order to attract more drivers during peak load and not lose orders.

The value of the RMSE metric in the test sample should be no more than 48.



### Libraries used in the study
* CatBoost
* Lightdm
* Matplotlib
* NumPy
* Pandas
* Python
* Scikit-learn
* Statsmodels

### Conclusion
On the test sample, the results were significantly worse than on the validation sample due to the fact that the time series is non-stationary.
On the validation sample, we were able to achieve the necessary results of the average error of the RMSE model less than 48 on five models out of five models under consideration. All models gave the desired RMSE result.

At the same time, only 3 out of 5 models were able to achieve the required RMSE result in the test sample.
The best results were obtained by the LGBMRegressor model(n_estimators=50) with indicators:

* MSE of the best model in the validation sample: 1905.35
* Average model error(RMSE): 43.66

## Project status - completed
<br>

## Русский - название, описание проекта, используемые библиотеки и инструменты, вывод проекта и статус проекта

#  Прогноз количества заказов такси
Требуется разработать модель для прогнозирования числа заказов на следующий час для такси. Заказчик предоставил исторические данные о заказах такси в аэропортах. Результаты исследования нужны заказчику, чтобы привлекать больше водителей в период пиковой нагрузки и не терять заказы.

Значение метрики RMSE на тестовой выборке должно быть не больше 48.



### Используемые библиотеки в исследовании
* CatBoost
* Lightdm
* Matplotlib
* NumPy
* Pandas
* Python
* Scikit-learn
* Statsmodels

### Вывод
На тестовой выборке результаты получились значительно хуже, чем на валидационной из-за того, что временной ряд нестационарный.
На валидационной выборке мы смогли достичь необходимых результатов средней ошибки модели RMSE меньше 48 на пяти моделях из пяти рассматриваемых моделей. Все модели дали нужные результат RMSE.

При этом на тестовой выборке только 3 модели из 5 смогли достичь необходимого результата RMSE.
Лучшие результаты дала модель LGBMRegressor(n_estimators=50) с показателями:

* MSE наилучшей модели на валидационной выборке: 1905.35
* Средняя ошибка модели(RMSE): 43.66
 
## Статус проекта - завершен
