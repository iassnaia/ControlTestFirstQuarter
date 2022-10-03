# ControlTestFirstQuarter
for GeekBrains


**Задача**: Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

**Примеры**:

*["hello", "2", "world", ":-)"] -> ["2", ":-)"]

*["1234", "1567", "-2", "computer science"] -> ["-2"]

*["Russia", "Denmark", "Kazan"] -> []

### Решение задачи

* *Объявляются два массива:
   **первый** и **второй** такой же длины. 
* Затем метод **SecondArrayWithIF**, в котором цикл соразмерен длине массива.
* Внутри цикла проверка условия ( <=3 ), если да  -> элемент первого массива заносится в **count** элемент второго массива.
* Переменная **count** вводится, чтобы поочередно закидывать из первого массива во второй, и чтобы потом не было пробелов. 
* После присвоения увеличивается переменная **count** на 1 и возвращается к циклу **for** в котором *i* увеличивается на 1. 
* И так проверяется до конца.
* Для наглядности выводим результат на экран с помощью метода **PrintArray**.


### Блок-схема
![block diagram](https://user-images.githubusercontent.com/110601635/193623381-e13d3076-8826-4123-9739-4c16c16ec943.jpg)
