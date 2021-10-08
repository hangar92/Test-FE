# Task

> Реализовать таблицу, которая отображает, данные с data.json. Таблица должна иметь вид:  
> | User | 1 | 2 | 3 | ... | 31 | Monthly total |  
> Где 1, 2, 3 - это дни месяца.  
> Для каждой строки в дни месяца отобразить количество времени который провел пользователь в этот день, если данных за этот день нет, то отобразить 0.  
> В колонку Monthly total отобразить все количество времени пользователя за месяц.  
> При нажатии на день месяца в хедере таблицы отобразить в модальном окне погоду в городе Екатеринбург за этот день. Можно взять любой доступный для этого API.

## Features
-   Первая и последняя колонка (User and Monthly total) должны быть приклеены к своим сторонам, то есть при горизонтальном скролле они не должны скрываться;
-   Таблица должна поддерживать Drag to scroll. Но при нажатии на текст, нужно выделять текст, скролл не должен производиться;
-   Колонки таблицы должны быть resizeable;
-   Для каждого колонки реализовать сортировку по возрастанию и убыванию;
-   Реализовать поиск (фильтрация) по имени пользователя;
-   Реализовать пагинацию по 10 элелемнтов
