# first
Необычный консольный калькулятор, тестовое задание для КАТА академии

Условия тестового задания:
Описание
Создайте функцию calculate. Функция должна принимать арифметические операции двух чисел в виде строки и возвращать строку с результатом их выполнения.
Функция принимает данные из аргументов и возвращает с помощью return.

Требования
Решение должно пройти все тесты.
Калькулятор умеет выполнять операции сложения, вычитания, умножения и деления с двумя числами: a + b, a - b, a * b, a / b. Данные передаются в виде одной строки!
Калькулятор умеет работать как с арабскими (1,2,3,4,5…), так и с римскими (I,II,III,IV,V…) числами. Оба операнда должны быть либо арабскими, либо римскими.
Операнды должны лежать в диапазоне от 1 до 10 включительно, без ноля. Ответ может быть больше 10.
Калькулятор умеет работать только с целыми числами, принимает и возвращает.
Результат на выходе всегда строка с целым числом. В делении учитываем только целую часть - десятичную отбрасываем, например 2 / 4 = 0,5 - вернём 0.
Калькулятор умеет работать только с арабскими или римскими цифрами одновременно, при вводе пользователем строки вроде 3 + II калькулятор должен выбросить исключение (ошибку) и прекратить свою работу.
Поскольку в римской системе счисления нет нуля и отрицательных чисел, то вместо них возвращаем пустую строку. (например I - II = '')
При вызове калькулятора с неподходящими числами, функция выбрасывает исключение и завершает свою работу.
При вызове калькулятора со строкой, которая не является математическим примером с одной из арифметических операций, описанных в требовании, приложение выбрасывает исключение и завершает свою работу.
