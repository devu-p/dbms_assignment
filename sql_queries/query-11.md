11.Create table given below: Salesperson and Customer


```sql
CREATE TABLE salesperson( pk_SNo int , SNAME varchar(20), CITY varchar(20) , COMM decimal(10,2) );

```

```sql
insert into salesperson VALUES (1001 , "Peel" , "London" , 0.12),
(1002 , "Serres" , "San Jose" , 0.13),
(1004 , "Motika" , "London" , 0.11),
(1007 , "Rafkin" , "Barcelona" , 0.15),
(1003 , "Axelrod" , "New York" , 0.1);
```

```SQL
CREATE TABLE customer (PK_CNM int , CNAME VARCHAR(25) , CITY VARCHAR(20), RATING INT, FK_SNo INT);
```

```sql
INSERT INTO CUSTOMER VALUES 
(201,"Hoffman", "London" , 100 , 1001),
(202,"Giovanne", "Roe" , 200 , 1003),
(203,"Liu", "San Jose" , 300 , 1002),
(204,"Grass", "Barcelona" , 100 , 1002),
(206,"Clemens", "London" , 300 , 1007),
(207,"Pereira", "Roe" , 100 , 1004);
```