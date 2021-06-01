1.Составить 3 SQL запроса с пояснением 
2.Сделать в них одну ошибку


1. Составить запрос на создание таблицы 
2. Составить запрос на добавление записи
3. Составить запрос на изменение записи

1. CREATE TABLE Users(
id int, name varchar(30), company varchar(30), city varchar(30), 
state varchar(30))

2. INSERT Users(name, company, city, state) VALUES (‘Trevor’, ‘Apple’, ‘New York’, ‘America’)

3. UPDATE table name="Michel", city=Estonia WHEERE user_id
