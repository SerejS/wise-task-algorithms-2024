Выполнял: Анисимов Кирилл
Тестировал: Деметрашвили Дмитрий

Название модуля: Граф минимальный по стягиванию

Необходимые условия:
    Связность: Проверяется с помощью обхода графа в глубину. Проверяется, что нет вершин, помеченных как непосещенные
    Взвешенность: Проверяется, что у всех ребер ненулевой вес.
    Неотрицательность: Проверяется, что у всех ребер и вершин неотрицательный вес.

Теория:
Стягивающее дерево - Для произвольного связного неориентированного графа G = <V, E> каждое дерево <V, T>, где T принадлежит E, будем назвать стягивающим деревом.
Пусть G - связный нагруженный граф. Задача построения минимального стягивающего дерева заключается в том, чтобы из множества стягивающих деревьев найти дерево, у которого сумма длин ребер минимальна.

Выполнение:

1. Выполняются проверки на связность, взвешенность, неотрицательность, а так же проверка на присутствие вершин и ребер и после вызывается метод isMinimallyContractible
2. Метод isMinimallyContractible реализует алгоритм Прима
3. Возвращается минимальный вес графа после стягивания