Написан модуль, который занимается фильтрацией набора перелетов согласно различным правилам.

1. Правил фильтрации может быть очень много.
2. Наборы перелетов также могут быть очень большими.
3. Правила могут выбираться и задаваться динамически в зависимости от контекста выполнения операции фильтрации.

Метод main() исключает из тестового набора перелёты по следующим правилам:
1. Вылет до текущего момента времени.
2. Сегменты с датой прилета раньше даты вылета.
3. Перелеты, где общее время, проведенное на земле, превышает два часа (время на земле — это интервал между прилетом одного сегмента и вылетом следующего за ним).
