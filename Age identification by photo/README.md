
## English - name, description of the project and the libraries used

# Age identification by photo

It is required to build a model that can determine the approximate age of a person from a photo.

The customer of the supermarket chain is implementing a computer vision system for processing customer photos. Photo fixation in the checkout area will help determine the age of customers in order to:

* Analyze purchases and offer products that may be of interest to buyers of this age group
* Monitor the integrity of cashiers when selling alcohol

We have at our disposal a set of photos of people with an indication of their age.


### Libraries used in the study
* Matplotlib
* NumPy
* Pandas
* Python
* Tensorflow.Keras

### Conclusion
To achieve the necessary quality results, the Adam optimizer was used with a learning rate of lr=0.0001, the photos were divided into batches of 32 photos per batch and the calculation was performed on different numbers of epochs, but with a maximum number of epochs of 30 pieces, the quality result turned out to be the maximum - MAE of the resulting model 5.5902.

I believe that the resulting model allows us to solve the task set by the business. The MAE quality indicator of the received model is 5.5902 - the model is wrong in the age of the buyer by 5.59 years.
This means that the business will be able to solve the problem:
* Analyze purchases and offer products that may be of interest to buyers of this age group

The model will not be able to help with the second task, because the error is too large for this task:
* Monitor the integrity of cashiers when selling alcohol

## Project status - completed
<br>

## Русский - название, описание проекта и используемые библиотеки

#  Идентификация возраста по фото

Требуется построить модель, которая по фотографии определить приблизительный возраст человека.

Заказчик сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определить возраст клиентов, чтобы:

* Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы
* Контролировать добросовестность кассиров при продаже алкоголя

В нашем распоряжении набор фотографий людей с указанием возраста.


### Используемые библиотеки в исследовании
* Matplotlib
* NumPy
* Pandas
* Python
* Tensorflow.Keras

### Вывод
Чтобы достигнуть необходимых результатов качества использовался оптимизатор Adam со скоростью обучения lr=0.0001, фотографии делились на батчи по 32 фото в батче и расчет производился на разных числах эпох, но с максимальным числом эпох в размере 30 штук результат качества получился у меня максимальным - MAE полученной модели 5.5902.

Считаю, что полученная модель позволяет решить поставленную бизнесом задачу. Показатель качества MAE полученной модели 5.5902 - модель ошибается в возрасте покупателя на 5.59 лет.
Это означает, что бизнес сможет решить задачу:
* Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы

Со второй задачей модель помочь не сможет, т к погрешность слишком большая для данной задачи:
* Контролировать добросовестность кассиров при продаже алкоголя

## Статус проекта - завершен
