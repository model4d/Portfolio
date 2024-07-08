<h1 align="center"> Анализ бизнес-показателей приложения Procrastinate Pro+ </h1>

[ipynb](https://github.com/aq2003/Portfolio/blob/main/Taxi%20Service/P12_Portfolio.ipynb)

<h3> Описание: </h3>

В нашем распоряжении находятся данные о пользователях развлекательного приложения Procrastinate Pro+, привлеченных в период с 1 мая по 27 октября 2019 года:
* лог сервера с данными об их посещениях;
* выгрузка их покупок за этот период;
* рекламные расходы.

Чтобы увеличить количество пользователей и выручку, компания вкладывает значительные средства в рекламу. Тем не менее, выручка от продаж в приложении последние несколько месяцев оказывается ниже затрат на рекламу.

<h3> Цель: </h3>

Найти причины неэффективности рекламных расходов и дать рекомендации отделу маркетинга для исправления ситуации.
    
<h3> Порядок выполнения исследования: </h3>

* загрузка и предобрабока предоставленных данных;
* задание функций для расчета и анализа метрик (LTV, CAC, ROI, удержание, конверсия) и их визуализации;
* получение профилей пользователей, определение минимальной и максимальной даты привлечения клиентов;
* определение стран пользователей, абсолютного и относительного количества платящих пользователей из этих стран;
* определение устройств, которые предпочитают пользователи, доли платящих для каждого устройства;
* определение рекламных источников, абсолютного и относительного числа платящих для каждого канала привлечения;
* подсчет общих расходов на маркетинг и по отдельным рекламным источникам;
* визуализация изменения расходов за неделю и за месяц для каждого рекламного канала;
* визуализация динамики привлечения клиентов для каждого рекламного канала;
* определение средней стоимости привлечения отдельного пользователя (САС) для каждого источника;
* анализ окупаемости рекламы за две недели лайфтайма для среднего пользователя;
* проверка конверсии и удержания для среднего пользователя;
* анализ окупаемости рекламы с разбивкой по устройствам, странам и рекламным каналам;
* анализ окупаемости рекламы отдельно для пользователей из Европы и США;
* исследование затрат на самый убыточный рекламный канал;
* формулирование итоговых выводов проведенного анализа и рекомендаций для отдела маркетинга.

<h3> Библиотеки: </h3>

* pandas;
* numpy;
* datetime;
* matplotlib.