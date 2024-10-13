10. Create After Insert trigger on Employee table which insert records in
viewtable

```sql
CREATE TABLE ViewTable (
  Employee_id int,
  First_Name varchar(20),
  Last_Name varchar(20),
  Salary int,
  Joining_Date date,
  Department varchar(20)
);
```

```sql
DELIMITER //
CREATE TRIGGER add_trg
AFTER INSERT ON employee
FOR EACH ROW
BEGIN
  INSERT INTO ViewTable (Employee_id, First_Name, Last_Name, Salary, Joining_Date, Department)
  VALUES (NEW.Employee_id, NEW.First_Name, NEW.Last_Name, NEW.Salary, NEW.Joining_Date, NEW.Department);
END; 
```

```sql
 insert into employee values(9,"devu","pipaliya",1500000,"2024-10-04","computer");
 
```

```sql
 select *from viewtable;
```






```