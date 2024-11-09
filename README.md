# course-project

## Задачи
* Разработать на C/C++ программу-клиент и программу-сервер, между которыми с помощью сокетов организован обмен сообщениями

### Задачи программы-клиента

* Программа-клиент должна поддерживать загрузку данных из файлов формата .txt и .csv
* Программа-клиент должна поддерживать выбор операции обработки данных
* Программа-клиент должна поддерживать отправку данных через сокет программе-серверу
* Программа-клиент должна поддерживать получение данных через сокет от программы-сервера
* Программа-клиент должна поддерживать вывод полученных от сервера данных

### Задачи программы-сервера

* Программа-сервер должна поддерживать получение данных через сокет от программы-клиента
* Программа-сервер должна поддерживать анализ полученных от программы-клиента данных
* Программа-сервер должна поддерживать выполнение над полученными данными определённых [алгоритмических операций](
#алгоритмы-реализуемые-сервером)
* Программа-сервер должна поддерживать отправку данных через сокет программе-клиенту.

 ## Алгоритмы, реализуемые сервером

### Алгоритмы поиска
* Алгоритм последовательно поиска
* Алгоритм последовательного поиска с барьером (Sentinel Linear Search)
* Алгоритм бинарного поиска
* Алгоритм последовательного поиска в упорядоченном массиве

Для алгоритмов бинарного поиска и последовательного поиска в упорядоченном массиве исходные данные необходимо предварительно отсортировать по неубыванию
### Алгоритмы сортировки
* Алгоритм сортировки выбором
* Алгоритм сортировки Шелла

Сортировка выполняется по возрастанию

## Тестирование алгоритмов, реализуемых сервером

### Алгоритмы поиска
 
* Для алгоритмов последовательного посика и последовательного поиска с барьером используется одна и та же последовательность исходных данных
* Для алгоритмов бинарного поиска и последовательного поиска в упорядоченном массиве используется одна и та же последовательность исходных данных
* Для массива малой размерности (< 20 элементов, тип ключей исходной последовательности - символы, многократное вхождение запрещено) выполнить поиск искомого значения с использованием каждого из четырёх алгоритмов, проверить случаи, когда значение есть в массиве и когда записи нет в массиве
* Для целочисленного массива большой размерности (> 50 тысяч элементов) выполнить поиск искомого значения с использованием каждого из четырёх алгоритмов. Проверить случаи, когда значение есть в массиве и когда записи нет в массиве

### Алгоритмы сортировки
* Выполнить сортировку заданной случайном образом последовательности из n элементов с помощью двух алгоритмов сортировки
* Отсортировать массив малой размерности (n <= 15 элементов), выводить массив на каждом шаге сортировки, водсчитать число необходимых сравнений и перестановок
* Отсортировать массивы большей размерности (n > 1000, n > 10000, n > 500000 элементов), замерить время выполнения каждого алгоритма, подсчитать число необходимых сравнений и перестановок

## Документация/отчёт

### Содержание документации/отчёта
1. Титульный лист
2. Общая формулировка задания с указанием общего варианта
3. Выполнение задания по [пунктам](#пункт-документацииотчёта)
4. Общие выводы

### Пункт документации/отчёта
1. Задание пункта
2. Описание модуля и функций
3. Описание основных технологий (если необходимо)
4. Блок-схемы основных функций
5. Код (рекомендуется разделить по модулям и функциям)
6. Результаты выполнения (таблицы, диаграммы)
    * Среднее число необходимых сравнений
    * Среднее число необходимых перестановок (для алгоритмов сортировки)
    * Среднее время выполнения (для больших массивов)