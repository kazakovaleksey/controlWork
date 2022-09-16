# controlWork
Контрольная работа по итогам первого блока

Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Решение задачи
1. Запрос у пользователя каким образом заполнить массив строк.

2. CheckArray - Метод подсчёта количества элементов, размер которых меньше lengthLimit
Подсчёт осуществляется перебором элементов массива arrayOfStrings и сравнением количества их элементов с переменной lengthLimit.
Результат выводится в переменную numbersItems.
Инициализируется новый массив строк newArrayOfStrings, размером, равным переменной numbersItems.

3. FillNewArray - Метод формирования нового массива строк
Формирование осуществляется перебором элементов массива arrayOfStrings, сравнением количества их элементов с переменной lengthLimit и добавлением в массив newArrayOfStrings элемента, удовлетворяющего условию.
На выходе метода получается заполненный массив строк newArrayOfStrings, удовлетворяющий условию, что и является решением задачи.

4. Выводим на экран с помощью метода PrintArray.