
## English - the name, description of the project, libraries and tools used, the output of the project and the status of the project

# Real estate market of St. Petersburg
We have an archive of ads for the sale of apartments in St. Petersburg and neighboring settlements for several years. You need to learn how to determine the market value of real estate. The task is to set the parameters. This will allow you to build an automated system: it will track anomalies and fraudulent activity.

There are two types of data available for each apartment for sale. The first ones are entered by the user, the second ones are obtained automatically based on cartographic data. For example, the distance to the center, airport, nearest park and reservoir.

### Used libraries and tools in research
* Matplotlib
* Pandas
* Python

### Conclusion
The project investigated the paramtra ads, some in more detail, some in less detail. It is safe to say that most of the parameters affect the cost of the apartment, and some parameters affect each other. To a greater extent, the cost is influenced by the parameters: locality, area, number of rooms, distance from the center, ceiling height, floor, date of publication of the announcement, number of balconies.

Based on the conducted research for the entire region, we observe:

* the direct dependence of the cost of the apartment on the area of the apartment, the larger the area, the more expensive the apartment.
* the direct dependence of the cost of the apartment on the number of rooms, the more rooms, the more expensive the apartment.
* the inverse dependence of the cost of the apartment distance from the center, the further from the center, the cheaper the apartment.
* the dependence on the floor in the categories first, last, other is as follows: the cheapest apartments on the first floors, followed by the last floors and the most expensive apartments in the category of another floor.
* dependence of the price on the day of the week of publication of the announcement: the most expensive ads are posted on Thursday, and the cheapest on Sundays and on weekends in general, cheaper ads are posted than on weekdays.
* the price depends on the month of publication of the ad: January, March, May and August are cheaper ads, and February, June, November and December are more expensive ads.
* price dependence on the year of publication of the ad: the most expensive year is 2017, the cheapest year is 2014.

The study confirms that the cost of the apartment is influenced by all the parameters of the apartment: area, number of rooms, distance from the center, floor category.

The price depends on the day of publication of the announcement, this is especially evident on between weekdays and weekends, because on weekends ads are usually posted by individuals without additional commission and this is ordinary housing, and on weekdays most ads are published by real estate companies, and there the commission of realtors is additionally included in the price and various elite real estate is sold as a rule, too, through realtors, and not independently by the owners of such real estate.

The pattern of increasing the cost of housing from earlier years to more modern ones is also logical, because due to inflation, prices in Russia are constantly rising for everything and the longer the time interval studied, the more the price will increase.

We found out that most of the ads are presented from St. Petersburg, and the highest cost of housing is in the center up to 8 kilometers from the center and conducted additional research only in the center of St. Petersburg:

Based on the conducted research for the Center of St. Petersburg, we observe:

* the direct dependence of the cost of the apartment on the area of the apartment, the larger the area, the more expensive the apartment.
* the direct dependence of the cost of the apartment on the number of rooms, the more rooms, the more expensive the apartment.
* in the center, there is not a direct dependence of the cost of an apartment on the distance from the center, because apartments located from 4 to 6 km are the most expensive.
* the dependence on the floor in the categories first, last, other is as follows: the cheapest apartments on the first floors, followed by the last floors and the most expensive apartments in the category of another floor.
* dependence of the price on the day of the week of publication of the announcement: the most expensive ads are posted on Thursday, and the cheapest on Sundays and on weekends in general, cheaper ads are posted than on weekdays.
* the price depends on the month of publication of the ad: January, April and May are cheaper ads, and February, June, November and December are more expensive ads.
* price dependence on the year of publication of the ad: the most expensive year is 2017, the cheapest year is 2014.

After conducting studies of the parameters affecting the cost of apartments for the whole city and for the center, we can conclude that only the distance from the center parameter, which was highlighted above, differs, because judging by the graph, the dependence is indirect.

All the parameters area, price, number of rooms, ceiling height by which the matrix of scattering diagrams was built affect each other, except for the number of rooms on the ceiling height, there is no dependence.

For the center, there is no linear dependence of the price on the distance from the center, because virtually all apartments are located in the city center, and from 4 to 6 kilometers apartments are more often found and larger in value, because apparently up to 4 kilometers are mostly not residential buildings, but various administrative, public, shopping, etc.

The study confirms that the cost of the apartment is influenced by all the parameters of the apartment: area, number of rooms, distance from the center, floor category.

The price depends on the day of publication of the announcement, this is especially evident on between weekdays and weekends, because on weekends ads are usually posted by individuals without additional commission and this is ordinary housing, and on weekdays most ads are published by real estate companies, and there the commission of realtors is additionally included in the price and various elite real estate is sold as a rule, too, through realtors, and not independently by the owners of such real estate.

The pattern of increasing the cost of housing from earlier years to more modern ones is also logical, because due to inflation, prices in Russia are constantly rising for everything and the longer the time interval studied, the more the price will increase.
## Project status - completed
<br>

## Русский - название, описание проекта, используемые библиотеки и инструменты, вывод проекта и статус проекта

# Рынок недвижимости Санкт-Петербурга и ЛО
У нас имеется архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма. 

### Используемые библиотеки и инструменты в исследовании
* Matplotlib
* Pandas
* Python


### Вывод
В проекте были исследованы парамтры объявлений, некоторые более подробно, некоторые менее подробно. С уверенностью можно сказать, что большинство параметров влияет на стоимость квартиры, а некоторые параметры влияют друг на друга. В более значительной степени на стоимость влияют параметры: населённый пункт, площадь, число комнат, удалённость от центра, высота потолков, этаж, дата публикации объявления, число балконов.

На основании проведённого исследования для всего региона мы наблюдаем:

* прямая зависимость стоимости квартиры от площади квартиры, чем больше площадь, тем дороже квартиры.
* прямая зависимость стоимости квартиры от числа комнат, чем больше комнат, тем дороже квартиры.
* обратная зависимость стоимости квартиры удалённости от центра, чем дальше от центра, тем дешевле квартиры.
* зависимость от этажа по категориям первый, последний, другой такая: самые дешёвые квартиры на первых этажах, далее идут последние этажи и самые дорогие квартиры в категории другой этаж.
* зависимость цены от дня недели публикации объявления: в четверг выкладываются самые дорогие объявления, а самые дешёвые по воскресеньям и в целом по выходным выкладываются более дешёвые объявления, чем в будни.
* зависимость цены от месяца публикации объявления: январь, март, май и август - более дешёвые объявления, а февраль, июнь, ноябрь и декабрь - более дорогие объявления.
* зависимость цены от года публикации объявления: самый дорогой год - 2017, самый дешёвый год - 2014.

Исследование подтверждает, что на стоимость квартиры влиют все параметры квартиры: площадь, число комнат, удалённость от центра, категория этажа.

Цена имеет зависимость от дня публикации объявления, особенно сильно это видно на между будними днями и выходными, тк в выходные дни выкладываются объявления как правило частными лицами без дополнительной комиссии и это обычное жильё, а в будни дни большинство объявлений публикуется риэлторскими компаниями, а там дополнительно в цену закладывается комиссия риелторов и различная элитная недвижимость продаётся как правило тоже через риелторов, а не самостоятельно владельцами такой недвижимости.

Закономерность повышения стоимости жилья от более ранних годов к более современным тоже логична, тк из-за инфляции цены в России постоянно растут на всё и чем больше изучаемый временной интервал, тем сильнее будет увеличиваться цена.

Мы выяснили, что большинство объявлений представлены из Санкт-Петербурга, а наибольшая стоимость жилья идёт в центре до 8 километра от центра и провели дополнительное исследование только по центру Санкт-Петербурга:

На основании проведённого исследования для цетра Санкт-Петербурга мы наблюдаем:

* прямая зависимость стоимости квартиры от площади квартиры, чем больше площадь, тем дороже квартиры.
* прямая зависимость стоимости квартиры от числа комнат, чем больше комнат, тем дороже квартиры.
* в центре наблюдается не прямая зависимость стоимости квартиры удалённости от центра, тк квартиры находящиеся от 4 до 6 км самые дорогие.
* зависимость от этажа по категориям первый, последний, другой такая: самые дешёвые квартиры на первых этажах, далее идут последние этажи и самые дорогие квартиры в категории другой этаж.
* зависимость цены от дня недели публикации объявления: в четверг выкладываются самые дорогие объявления, а самые дешёвые по воскресеньям и в целом по выходным выкладываются более дешёвые объявления, чем в будни.
* зависимость цены от месяца публикации объявления: январь, апрель и май - более дешёвые объявления, а февраль, июнь, ноябрь и декабрь - более дорогие объявления.
* зависимость цены от года публикации объявления: самый дорогой год - 2017, самый дешёвый год - 2014.

Проведя исследования параметров влияющих на стоимость квартир для всего города и для центра можно сделать вывод, что отличается только параметр удалённость от центра, который выделили выше, тк судя по графику зависимость непрямопропоцианальная.

Все параметры площадь, цена, число комнат, высота потолков по которым строили матрицу диаграмм рассеяния влияют друг на друга, кроме числа комнат на высоту потолков, тут нет зависимости.

Для центра нет прямолинейной зависимости цены от удалённости от центра, тк фактически все квартиры находятся в центре города, а с 4 по 6 километр квартиры получаеются более часто встречаются и большие по стоимости, тк видимо до 4 километра в основном находятся не жилые здания, а различные административные, общественные, торговые и тд.

Исследование подтверждает, что на стоимость квартиры влиют все параметры квартиры: площадь, число комнат, удалённость от центра, категория этажа.

Цена имеет зависимость от дня публикации объявления, особенно сильно это видно на между будними днями и выходными, тк в выходные дни выкладываются объявления как правило частными лицами без дополнительной комиссии и это обычное жильё, а в будни дни большинство объявлений публикуется риэлторскими компаниями, а там дополнительно в цену закладывается комиссия риелторов и различная элитная недвижимость продаётся как правило тоже через риелторов, а не самостоятельно владельцами такой недвижимости.

Закономерность повышения стоимости жилья от более ранних годов к более современным тоже логична, тк из-за инфляции цены в России постоянно растут на всё и чем больше изучаемый временной интервал, тем сильнее будет увеличиваться цена.
## Статус проекта - завершен
