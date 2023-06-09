# Оглавление:

## Lesson_1.
### Урок 1. Установка СУБД, подключение к БД, просмотр и создание таблиц.
**Домашнее задание:**

- Создайте таблицу с мобильными телефонами, используя графический интерфейс. Заполните БД данными.

- Выведите название, производителя и цену для товаров, 
количество которых превышает 2 (SQL - файл, скриншот, либо сам код)

- Выведите весь ассортимент товаров марки “Samsung”

- Выведите информацию о телефонах, где суммарный чек больше 100 000 и меньше 145 000*

- С помощью регулярных выражений найти товары, в которых есть упоминание "Iphone"

- С помощью регулярных выражений найти "Galaxy"

- С помощью регулярных выражений найти товары, в которых есть ЦИФРЫ

- С помощью регулярных выражений найти товары, в которых есть ЦИФРА "8"  

## Lesson_2.
### Урок 2. SQL – создание объектов, простые запросы выборки
**Домашнее задание:**

***Обязательные задачи:***
- Используя операторы языка SQL, создайте табличку “sales”. Заполните ее данными

- Сгруппируйте значений количества в 3 сегмента — меньше 100, 100-300 и больше 300.

- Создайте таблицу “orders”, заполните ее значениями. Покажите “полный” статус заказа, используя оператор CASE

***Необязательные задачи:***

- Используя оператор ALTER TABLE, установите внешний ключ в одной из таблиц.

- Без оператора JOIN, верните заголовок публикации, текст с описанием, идентификатор клиента, опубликовавшего публикацию и логин данного клиента.

- Выполните поиск по публикациям, автором которых является клиент "Mikle".

## Lesson_3.
### Урок 3. SQL – выборка данных, сортировка, агрегатные функции
**Домашнее задание:** 


- Отсортируйте данные по полю заработная плата (salary) в порядке: убывания; возрастания.

- Выведите 5 максимальных заработных плат (saraly).

- Посчитайте суммарную зарплату (salary) по каждой специальности (роst).

- Найдите кол-во сотрудников с специальностью (post) «Рабочий» в возрасте от 24 до 49 лет включительно.

- Найдите количество специальностей.

- Выведите специальности, у которых средний возраст сотрудников меньше 30 лет включительно.

## Lesson_4.
### Урок 4. Урок 4. SQL – работа с несколькими таблицами
**Домашнее задание:**

https://drive.google.com/file/d/1TZzW8ZlDdvIfDC9C46bUeILey6opQjdu/view?usp=share_link 

- Используя JOIN-ы, выполните следующие операции:


1. Вывести всех котиков по магазинам по id (условие соединения shops.id = cats.shops_id)

2. Вывести магазин, в котором продается кот “Мурзик” (попробуйте выполнить 2 способами)

3. Вывести магазины, в которых НЕ продаются коты “Мурзик” и “Zuza”

https://drive.google.com/file/d/1TZzW8ZlDdvIfDC9C46bUeILey6opQjdu/view?usp=share_link


- Вывести название и цену для всех анализов, которые продавались 5 февраля 2020 и всю следующую неделю.

- Есть таблица анализов Analysis:
an_id — ID анализа;
an_name — название анализа;
an_cost — себестоимость анализа;
an_price — розничная цена анализа;
an_group — группа анализов.

- Есть таблица групп анализов Groups:
gr_id — ID группы;
gr_name — название группы;
gr_temp — температурный режим хранения.

- Есть таблица заказов Orders:
ord_id — ID заказа;
ord_datetime — дата и время заказа;
ord_an — ID анализа.

## Lesson_5.

### Урок 5. SQL – оконные функции

**Домашнее задание:**

***Задание -1:***


Файл - https://docs.google.com/spreadsheets/d/1bKCfz2tMENAISBxU7XRevge1qraNuPoN/edit?usp=share_link&ouid=112631188905352530754&rtpof=true&sd=true 

- Создайте представление, в которое попадут автомобили стоимостью  до 25 000 долларов.


- Изменить в существующем представлении порог для стоимости: пусть цена будет до 30 000 долларов (используя оператор ALTER VIEW).


- Создайте представление, в котором будут только автомобили марки “Шкода” и “Ауди”.
***Задание -2:***

- Добавьте новый столбец под названием «время до следующей станции».

## Lesson_6.

### Урок 6. SQL – Транзакции. Временные таблицы, управляющие конструкции, циклы

**Домашнее задание:**

***Задание -1:***

- Создайте функцию, которая принимает кол-во сек и форматирует их в кол-во дней, часов, минут и секунд.


**Пример: 123456 ->'1 days 10 hours 17 minutes 36 seconds '**

***Задание -2:***

- Выведите только четные числа от 1 до 10 включительно. (Через функцию / процедуру)
Пример: 2,4,6,8,10 (можно сделать через шаг +  2: х = 2, х+=2)
