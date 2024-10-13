14.Names and cities of all salespeople in London with commission above 0.12

```sql
 SELECT SNAME, CITY 
FROM salesperson 
WHERE city = 'london' AND comm >= 0.12;
```