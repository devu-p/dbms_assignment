17. All customers excluding those with rating <= 100 unless they are
locatedinRome


```sql
SELECT * FROM customer WHERE rating > 100 OR city = 'roe';
```