# Олимпиадная задача: Попытка к бегству

## Описание
Узник пытается бежать из замка, который состоит из MN квадратных комнат, расположенных в виде прямоугольника M×N. Между любыми двумя соседними комнатами есть дверь , однако некоторые комнаты закрыты и попасть в них нельзя. В начале узник находится в угловой комнате и для спасения ему надо попасть в противоположную угловую комнату. Времени у него немного, всего он может побывать не более, чем в M+N-1 комнате, включая начальную и конечную комнату на своем пути, то есть с каждым переходом в соседнюю комнату расстояние до выхода из замка должно уменьшаться. От вас требуется найти количество различных маршрутов, ведущих к спасению.

### Входные данные
Первая строчка входных данных содержит натуральные числа M и N, не превосходящих 1000. Далее идет план замка в виде M строчек из N символов в каждой. Один символ соответствует одной комнате: если символ равен 1, то в комнату можно попасть, если он равен 0, то комната закрыта. Первоначальное положение узника – левый нижний угол (первый символ последней строки), выход находится в правом верхнем углу (последний символ первой строки, оба этих символа равны 1).
Входные данные подобраны таким образом, что искомое число маршрутов не превосходит 2.000.000.000.

### Выходные данные
Программа должна напечатать количество маршрутов, ведущих узника к выходу и проходящих через M+N-1 комнату, или слово impossible, если таких маршрутов не существует.

## Тестирование
### Тест №1
Входные данные:
```
3 5
11111
10101
11111
```
Выходные данные:
```
3
```

### Тест №2
Входные данные:
```
3 5
11101
10101
10111
```
Выходные данные:
```
impossible
```
