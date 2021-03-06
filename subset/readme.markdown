﻿Подмножества данного множества из n элементов, пронумерованных от 1 до n, можно закодировать в виде вектора из n единиц и нулей, i-ый элемент которого равен 1, если i-ый элемент множества присутствует в подмножестве, и равен 0 иначе. 

Автор: Никита Карагодин.

OEIS: [A000079](https://oeis.org/A000079).

Ссылки:
[MathWorld](http://mathworld.wolfram.com/Subset.html),
[Википедия](https://en.wikipedia.org/wiki/Bit_array).

n = 62 &mdash; максимальное число,
для которого количество битовых векторов длины n помещается в `int64_t`.

Функция `total`: O(1).

Функция `generate_all`: O(n * 2^n).

Функция `is_valid`: O(n).

Функция `number_by_object`: O(n).

Функция `object_by_number`: O(n).

Функция `prev`: O(n), амортизировано за O(1).

Функция `next`: O(n), амортизировано за O(1).