---
title: PHP Variables
localeTitle: Переменные PHP
---### Типы PHP-Vaiables

Вариблеры - это основной способ хранения информации в середине программы PHP. Все переменные в PHP передаются с помощью знака доллара, как `$variable_name` . Переменные присваиваются `= operator` , с переменной в левой части и выражением, которое должно быть оценено справа.

### Переменные имена

Правила для именования переменной перечислены ниже:

1.  Имена переменных должны начинаться с буквы или символа подчеркивания. 2. Имя переменной может состоять из цифр, букв, подчеркиваний, но вы не можете использовать символы, такие как `+ , - , % , ( , ) . &` в его названии. 3. Переменные имена чувствительны к регистру, т.е. `($age and $AGE are two different variables)` .

### Создание (объявление) переменных PHP

В PHP переменная начинается с знака $, а затем имя переменной. Ниже приведен фрагмент кода, приведенный ниже.

`shell <?php $txt = "Hello world!"; $x = 6; $y = 10.5; ?>`