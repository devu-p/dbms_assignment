7. Get department wise maximum salary from employee table order by
8. salary ascending?

```sql
SELECT department , max(salary) as "maximum_salary"  from employee group by department order by "maximum_salary" asc;
```