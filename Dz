1.
USE Product;
SELECT price * quantity
FROM Product;
2.
USE Product;
SELECT DATEADD(HOUR, 48, GETDATE());    
SELECT name
FROM Product
WHERE quantity < 20;
3.
USE Product;
SELECT DATEADD(MONTH, 1, GETDATE());    
SELECT name,price
FROM Product
4.
USE Product;
SELECT  name,price
FROM Product
WHERE category LIKE N'%Sweets%'
AND producer NOT LIKE N'%Roshen%';
5.
SELECT name, price
FROM Product
WHERE name LIKE 'K%' and category LIKE '%A%'
ORDER BY name;
6.
SELECT name, price
FROM Product
WHERE name >= 'B' AND name <= 'L'
7.
SELECT name, price, date_of_delivery
FROM Product
WHERE price < 50
AND date_of_delivery = CONVERT(INT, FORMAT(DATEADD(DAY, -7, GETDATE()), 'yyyyMMdd'));
8.
USE Product;
SELECT  name,quantity
FROM Product
WHERE category LIKE N'%Beverages%'
AND quantity > 100 ;
9.
USE Product;
SELECT  name,price
FROM Product
WHERE price >= 100 And price <=200
ORDER BY price ASC;
10.
USE Product;
UPDATE Product
SET price = price * 1.05;
11.
USE Product;
SELECT  name,date_of_delivery
FROM Product
WHERE date_of_delivery LIKE N'%NULL%'
UPDATE Product
SET date_of_delivery = 18012026;
12.
USE Product;
SELECT  name,price,quantity
FROM Product
WHERE quantity <100 AND price > 70
DELETE FROM Product;
13.
USE Product;
SELECT  name,category
FROM Product
WHERE category LIKE N'%Alcohol%' or category LIKE N'%Sweets%'
DELETE FROM Product;
17.
SELECT TOP 5 name, price
FROM Product
ORDER BY price DESC;
18.
SELECT name,producer,discount
FROM Product
WHERE producer LIKE '%NULL%' OR discount < 10;
DELETE FROM Product;
