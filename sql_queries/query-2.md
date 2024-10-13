2. Create table given below: Employee and IncentiveTable


```sql
CREATE TABLE Employee(Employee_id int, First_name varchar(20),Last_name varchar(20), Salary int , Joining_date date , Department varchar(50));
```
```sql
INSERT INTO employee VALUES
(1 , "John" , "Abraham", 1000000 , "2013-1-01" , "Banking"),
(2 , "Michael", "Clarke",800000, "2013-1-01" , "Insurance"),
(3 , "Roy", "Thomas",700000, "2013-2-01" , "Banking"),
(4 , "Tom", "Jose",600000, "2013-2-01" , "Insurance"),
(5 , "Jerry", "Pinto",650000, "2013-2-01" , "Insurance"),
(6 , "Philip", "Mathew",750000, "2013-1-01" , "Services"),
(7 , "TestName1", 123,800000, "2013-1-01" , "Services"),
(8 , "TestName2", "Lname%",600000, "2013-2-01","Insurance");
```

```sql
CREATE TABLE Incentive (Eployee_ref_id int,Incentive_date date, Incentive_amount int);
```

```sql
INSERT INTO incentive VALUES (1 , "2013-2-1",5000),
(2 , "2013-2-1",3000),
(3 , "2013-2-1",4000),
(1 , "2013-1-1",4500),
(2 , "2013-1-1",3500);  
```