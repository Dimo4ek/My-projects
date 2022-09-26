
## English - the name, description of the project, libraries and tools used, the output of the project and the status of the project

# Gold ore processing
It is required to prepare a prototype of a machine learning model for an industrial enterprise of the gold mining industry.

The model will help optimize production so as not to launch an enterprise with unprofitable characteristics.

The model should predict the recovery rate of gold from gold-bearing ore. We use data with extraction and purification parameters.

### Used libraries and tools in research
* Matplotlib
* NumPy
* Pandas
* Python
* Seaborn
* Scikit-learn

### Conclusion
On the test sample, the best RandomForestRegressor model showed worse results than on the training and validation samples - 9.2625% and 5.115%, respectively.
At the same time, our model showed the best results of the final sMAPE, when compared with the constant DummyRegressor model, which always predicts the average value of the training set - 9.2625% and 9.8325%, respectively.
Therefore, we can conclude that our model is valid, adequate and can be used to predict the recovery coefficient of gold from gold-bearing ore.

## Project status - completed
<br>

## Русский - название, описание проекта, используемые библиотеки и инструменты, вывод проекта и статус проекта

#  Обработка золотой руды
Требуется подготовить прототип модели машинного обучения для промышленного предприятия золотодобывающей отрасли.

Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. Используем данные с параметрами добычи и очистки. 

### Используемые библиотеки и инструменты в исследовании
* Matplotlib
* NumPy
* Pandas
* Python
* Seaborn
* Scikit-learn

### Вывод
На тестовой выборке лучшая модель RandomForestRegressor показала результат хуже, чем на обучающей и валидационной - 9.2625% и 5.115% соответственно.
При этом наша модель показала лучше результат итогового sMAPE, если сравнивать с константной моделью DummyRegressor, которая всегда предсказывает среднее значение обучающего набора - 9.2625% и 9.8325% соответственно.
Следовательно можно сделать вывод, что наша модель валидна, адекватна и может использоваться для предсказания коэффициента восстановления золота из золотосодержащей руды.

## Статус проекта - завершен
