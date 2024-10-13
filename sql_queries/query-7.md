7. Get department wise maximum salary from employee table order by
8. salaryascending?

```sql
SELECT department , max(salary) as maximum_salary  from employee group by department order by salary asc;
```