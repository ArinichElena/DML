# DML
#### 1. Напишите запрос по своей базе с регулярным выражением, добавьте пояснение, что вы хотите найти.
> Выводим всех пациентов
<image src="https://github.com/ArinichElena/DML/blob/main/select.png">
  
> Доктора с их специализациями
<image src="https://github.com/ArinichElena/DML/blob/main/select%20left.png">
  
#### 2. Напишите запрос по своей базе с использованием LEFT JOIN и INNER JOIN, как порядок соединений в FROM влияет на результат? Почему?
> INNER JOIN оставляет строки, которые пересекаются в обеих таблицах
<image src="https://github.com/ArinichElena/DML/blob/main/select%20left%202.png">
  
> LEFT JOIN выводит все значения из первой таблицы и находит им сопоставление из второй (данные погут быть пустые). В примере ниже, для 5 и 6 поликлиники нет врачей.
<image src="https://github.com/ArinichElena/DML/blob/main/select%20inner.png">
  
#### 3. Напишите запрос на добавление данных с выводом информации о добавленных строках.
<image src="https://github.com/ArinichElena/DML/blob/main/insert%20returning.png">
  
#### 4. Напишите запрос с обновлением данные используя UPDATE FROM.
<image src="https://github.com/ArinichElena/DML/blob/main/update%20from.png">
<image src="https://github.com/ArinichElena/DML/blob/main/update%20from%202.png">
  
#### 5. Напишите запрос для удаления данных с оператором DELETE используя join с другой таблицей с помощью using.
> Удаляем записи по поликлиникам, где врачи закреплены больше чем за 1 организацией.
<image src="https://github.com/ArinichElena/DML/blob/main/delete%20join.png">
<image src="https://github.com/ArinichElena/DML/blob/main/delete%20join%202.png">

