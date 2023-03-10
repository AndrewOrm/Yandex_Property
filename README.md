# Yandex_Property    
Проект 3 "Анализ рынка недвижимости Санкт-Петербурга".    
Задача проекта: используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир.     
Инструменты: Pandas, Python, Matplotlib, исследовательский анализ данных, предобработка данных.    
Ключевые навыки: обработка данных, histogram, boxplot, категоризация, scatterplot.    
Статус: завершён

Итоговый вывод и рекомендации:    

В исходном датафрейме имелись данные в 22 столбцах.

На этапе предобработки данных мы устранили нарушения стиля, пропущенные, лишние и аномальные значения, округлили даты, изменили типы данных и хаотичное расположение столбцов с близким смыслом.

После чего рассчитали несколько дополнительных показателей и добавили их в таблицу: цена квадратного метра; день недели, месяц и год публикации объявления; этаж квартиры (первый, последний, другой); соотношение жилой и общей площади, а также отношение площади кухни к общей. Получили таблицу с 29 столбцами.

Проведённый исследовательский анализ показал, что стоимость квартиры больше всего зависит от её общей площади и количества комнат, стоимость снижается по мере удаления от центра. Кроме того, на стоимость продажи квартиры влияет день и месяц размещения объявления, имеется также годовая динамика (с пиком в 2017 году).

Нам удалось рассчитать средние и медианные значения всех факторов, определить среднее время продажи квартиры, среднюю цену кв.м в основных населённых пунктах, вычислить радиус центральной локации и сравнить параметры квартир в центре с общими параметрами по всей выборке.

Мы выяснили, что 2/3 объявлений подано в Санкт-Петербурге. Там и самая высокая средняя цена кв.м - почти 115 тыс.руб. Наименее дорогое жильё в городах Выборге, Всеволожске и Гатчине - менее 70 тыс.руб. за кв.м.

Наш анализ показал, что существует чёткая граница между центром Петербурга и остальной частью города - на расстоянии 7 км от нулевой точки отсчёта.

Цена квартиры в центре в среднем выше в 2,26 раза - 14,7 млн.руб. против 6,5 млн.руб. (схожая картина и с медианными значениями). Площадь квартиры в центре в среднем выше в 1,5 раза - 92,3 кв.м против 60,3 кв.м. Выше количество комнат и высота потолка, ниже этажность и выше дни экспозиции - 245 дней против 180 дней.
