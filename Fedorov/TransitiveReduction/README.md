# Транзитивное сокращение

## Определение
R транзитивное сокращение на множестве X отношения G на множестве X, если:
1) Транзитивное замыкание R на множестве X рано транзитивному замыканию G на множестве X
2) R - минимальное на множестве X

## Алгоритм
1. Для выделенного подграфа найдём транзитивное замыкание.
2. Сравним его с транзитивным замыканием исходного графа.
3. Проверим, что подграф минимальный (то есть нет ребра, при удалении которого из подграфа, транзитивное замыкание не изменится).

## *Примечания:*
1. *Проверяемый подграф задаётся раскраской рёбер (цвет любой).*
2. *Если используется несколько цветов для выделения рёбер, рассматриваются все цвета по отдельности.*
3. *Каждый цвет считается за отдельный подграф.*
