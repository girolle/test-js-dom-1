# Задание 2 (JS)

### Задание, которое получает студент

Напишите функцию `roman` для обработки римских и арабских цифр. Функция принимает в качестве аргумента число, записанное римскими или арабскими цифрами. Затем:

- определяет, использованы ли римские или арабские цифры;
- арабские преобразует в римские, а римские — в арабские;
- возвращает результат преобразования.

Функция должна сообщить о трёх видах ошибок:

- `TYPE_ERROR` — если в аргументе не строка и не число;
- `RANGE_ERROR` — если число выходит за диапазон от 1 до 3999;
- `UNKNOWN_SYMBOLS` — если аргумент содержит данные, которые не могут быть обработаны. Например, знаки пунктуации, неподходящие буквы латиницы или `NaN`.
![image](https://pictures.s3.yandex.net:443/resources/01_num_1628241863.png)

### Структура этого репозитория

В папке `pre` лежит начальный код студента. В папке `post` — конечный код (код верно решённого задания). Ваш код должен быть написан в файле `__test__/index.js`.

### Ваше задание

1. Написать список того, что необходимо проверить в коде студента;
2. Написать код, который это проверял бы.

Вся ваша работа должна быть в файле `__test__/index.js`. В нём в массив `errors` должны добавляться ошибки студента. Формат ошибок — произвольная строка (например: "Функция alert не вызвана"). Если код в файле `index.ts` верный — массив после проверок должен быть пустым. Если неверный, в массиве должны быть ошибки.

### FAQ

* Тесты должны работать в Node v10.21.0