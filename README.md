Шпаргалки по командам.
Команда select:
![Команда select:](https://github.com/777Artem-Led/333/blob/main/2025-05-10_13-22-01.png)
Команда where:
![Команда select:](https://github.com/777Artem-Led/333/blob/main/2025-05-10_15-45-27.png)
Команда And и Or: 
![Команда select:](https://github.com/777Artem-Led/333/blob/main/2025-05-10_15-56-56.png)
Команда Order by:
![Команда select:](https://github.com/777Artem-Led/333/blob/main/2025-05-10_16-18-02.png)
Команда Limit и Offset:
![Команда select:](https://github.com/777Artem-Led/333/blob/main/2025-05-10_16-24-33.png)
Команда update:
![Команда select:](https://github.com/777Artem-Led/333/blob/main/2025-05-10_16-40-14.png)
Команда set:
![Команда select:](https://github.com/777Artem-Led/333/blob/main/2025-05-10_16-46-57.png)
Команда truncate:
![Команда select:](https://github.com/777Artem-Led/333/blob/main/2025-05-10_16-55-58.png)
Команда delete:
![Команда select:](https://github.com/777Artem-Led/333/blob/main/2025-05-10_17-12-25.png)
Команда insert:
![Команда select:](https://github.com/777Artem-Led/333/blob/main/2025-05-10_17-23-37.png)
CREATE TABLE users (
id INT(10)UNSIGNED NOT NULL PRIMARY KEY,
first_name VARCHAR (50) NULL,
last_name VARCHAR (50) NULL,
birthday DATE NULL );
INSERT INTO users (id, first_name, last_name, birthday)
VALUES (1,'Дмитрий','Иванов',NULL),
(2,'Анатолий','Белый',NULL),
(3,'Денис','Давыдов','1995-09-08');

create table orders (
id int unsigned not null primary key auto_increment,
state varchar (8),
amount decimal (8,2)
);
insert into orders (state, amount)
values ('new', 1000.50),
('new', 3400.10),
('delivery', 7300.00)
