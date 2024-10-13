1. Create Table Name : Student and Exam

```sql
CREATE table student (Rollno int PRIMARY KEY, Name varchar(50) , Branch varchar(50));
```
```sql
INSERT INTO student VALUES (1, "Jay", "Computer Science"),(2, "Suhani", "Electronic and Com"),(3, "Kriti", "Electronic and Com");
```
```sql
CREATE TABLE Exam (Rollno int, S_code varchar(20), Marks int , P_code varchar(10),FOREIGN key (Rollno) REFERENCES student(Rollno));
```
```sql
INSERT INTO exam VALUES (1 , "CS11" , 50 , "CS"),
(1 , "CS12" , 60 , "CS"),
(2 , "EC101" , 66 , "EC"),
(2 , "EC102" , 70 , "EC"),
(3 , "EC101" , 45 , "EC"),
(3 , "EC102" , 50 , "EC");
```