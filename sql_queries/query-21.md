21. From the following table, write a SQL query to calculate the average
price for a manufacturer code of 16. Return avg.


```sql
SELECT AVG(PRO_PRICE) AS "Average Price"
FROM item_mast
WHERE PRO_COM = 16;
```