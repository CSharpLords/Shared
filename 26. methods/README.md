1. Открой `PairSymbols`. Тебе наверняка часто встречались ошибки, когда программа не запускалась из-за того, что ты забыл закрыть круглую или фигурную скобку. В этой задаче ты реализуешь аналогичную функциональность поиска непарных скобок или других символов. 
   - Напиши функцию `CheckPairs`, которая принимает параметрами строку с исходным текстом и пару открывающий/закрывающий символы. Функция выводит в консоль текст `Все в порядке`, если каждому открывающему символу есть пара. И текст `Найдены ошибки` в противном случае

2. Открой `CalcPower`. Исправь код функции `Power`, которая должна возвращать параметр `number`, возведенный в степень `exponent`. Например, `Power(2, 3)` должен возвращать 8. Код метода `Main` менять не следует

   - Для вычисления следует использовать цикл, а не `Math.Pow()`

3. Открой `Spaces`. Напиши функцию `CountSpaces`, которая принимает параметром строку текста и возвращает количество пробелов в этой строке. Код метода `Main` менять не следует

4. Открой `UpgradedSpaces`. Обрати внимание, что в предыдущей задаче слово `пробелов` не всегда правильно согласуется с их количеством. Исправь эту проблему

   - Для этого напиши функцию `GetSpacesForm`, которая принимает параметром число (количество пробелов) и возвращает правильную форму слова `пробел`. Например, для 1: пробел; для 2: пробела; для 5: пробелов и тд

5. Открой `Mathematics`. Довольно часто одни функции используют результаты других. Здесь в функцию `Sum()` (сложить) передается результат вызова функции `Multiply()` (умножить). Напиши эти функции, чтобы в консоль выводилось верное значение
