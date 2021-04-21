# web-tasks

## Полезные ссылки
Общие ссылки, более полно раскрывают то, о чем говорили на лекции:

https://learn.javascript.ru/first-steps

https://learn.javascript.ru/data-types

Статья про интерполяцию строк, пригодится в задаче «Thanks»:

https://ru.code-basics.com/languages/javascript/lessons/interpolation#:~:text=%D0%98%D0%BD%D1%82%D0%B5%D1%80%D0%BF%D0%BE%D0%BB%D1%8F%D1%86%D0%B8%D1%8F%20%2D%20%D1%81%D0%BF%D0%BE%D1%81%D0%BE%D0%B1%20%D1%81%D0%BE%D0%B5%D0%B4%D0%B8%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%81%D1%82%D1%80%D0%BE%D0%BA,%D1%81%D1%82%D1%80%D0%BE%D0%BA%D1%83%2D%D1%88%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD%20%D1%81%20%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D1%8C%D1%8E%20%D1%84%D0%B8%D0%B3%D1%83%D1%80%D0%BD%D1%8B%D1%85%20%D1%81%D0%BA%D0%BE%D0%B1%D0%BE%D0%BA.

## Ваши задания

Заготовки для заданий смотри в репозитории. Запустить можно на сайте https://replit.com/languages/nodejs.

Для вывода результата функции воспользуйтесь командной console.log();

Пример вывода результата функции convertStringToNumber:

console.log(convertStringToNumber(1));

### Farengeight

Допиши функцию convertCelsiusToFahrenheit, которая принимает на вход число — количество градусов в шкале Цельсия и возвращает число — количество градусов в шкале Фаренгейта. 

Для перевода градусов Цельсия в градусы Фаренгейта, воспользуйся формулой:
_f = (c × 9/5) + 32_, где __f__ — градусы Фаренгейта, __c__ — градусы Цельсия.

### String convertor

Напиши функцию, которая принимает на вход строку, и, если строка приводится к числу, то возвращает это число, иначе возвращает _false_.

### NaN

Напиши функцию, возвращающую NaN, который должен получаться из строки 'abc' с помощью бинарного или унарного оператора.

### Thanks

Напиши функцию, которая принимает имя пользователя и оценку — число от 1 до 5, и возвращает строку: "{Имя пользователя} оценил нас на {оценка} из 5. Спасибо, {Имя пользователя}!".

### ZeroCheck

Напиши функции, которые возвращают значение a, если a не равен нулю и строку 'Все плохо', если a равен 0. Сделай это при помощи:

- конструкции if-else
- тернарного оператора
- логического "или" (||)

### SumSquares

Напиши функцию, которая принимает на вход границы диапазона чисел (нижнюю - min, и верхнюю - max) и возвращает сумму квадратов всех чисел, входящих в диапазон

Например:

(5,6) → (25 + 36) → 61

(1,4) → (1 + 4 + 9 + 16) → 30

### SumArray

Напиши функцию, которая принимает на вход массив и возвращает сумму элементов массива. Входной массив может содержать в себе числа и вложенные массивы, если элемент — массив, то к общей сумме должна прибавиться сумма элементов подмассива.

Например:

[1, 2, 3] → 6

[1, [2], [[[3]]]] → 6

[1, [2, [3, [4]]]] → 10
