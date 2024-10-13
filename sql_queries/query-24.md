24. From the following table, write a SQL query to calculate average price
of the items for each company. Return average price and companycode.


```sql
SELECT PRO_COM as "Company Code",
AVG(PRO_PRICE) as "Average Price"
FROM item_mast
GROUP BY PRO_COM
ORDER BY PRO_COM;
```