http://localhost/phpmyadmin/index.php?route=/sql&pos=0&db=homework_1&table=cars

- CREATE DATABASE homework_1

- CREATE TABLE cars (

id int,
name varchar(255),
color varchar(210),
price varchar(240)

)

- INSERT INTO `cars`(`id`, `name`, `color`, `price`)
  VALUES ('1','Mazda','black','22000'),
  ('2','Fiat','red','15100'),
  ('3','Bmw','green','34250'),
  ('4','Subaro','blue','17046'),
  ('5','Honda','yellow','11090')

// פקודות

- SELECT `name` FROM `cars`;

- SELECT \* FROM `cars` WHERE name = 'Mazda';

- SELECT name,price FROM cars OREDER BY price;

- SELECT COUNT(name) FROM cars;
