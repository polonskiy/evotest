Условия
-------
В файлах `dataset-big.csv` и  `dataset-small.csv` содержатся списки транзакций (трат) которые совершили пользователи.
Нужно написать скрипт, который находит список пользователей, потративших сумму выше или равную заданному порогу и дату, когда это событие наступило.

Требования
----------
1. Скрипт должен быть написан на чистом PHP
2. Дополнительное решение при помощи bash или SQL будет плюсом
3. Скрипт должен запускаться из командной строки
4. Скрипт должен принимать 2 аргумента: 1-й - имя файла, 2-й - пороговая сумма

Проверка
------------
Допустим, ваш скрипт называется `solution.php`.
Результат запуска `./solution.php dataset-small.csv 25` должен совпадать с содержимым файла `result-small-25.csv`.
Результат запуска `./solution.php dataset-big.csv 2000` должен совпадать с содержимым файла `result-big-2000.csv`.

Критерии оценки
---------------
1. Корректность работы
2. Понятность кода
3. Производительность
4. Требовательность к ресурсам
