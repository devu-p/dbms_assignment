9. Select first_name, incentive amount from employee and incentives table
forthose employees who have incentives and incentive amount greater than
3000


```sql
select employee.first_name , incentive.Incentive_amount from employee inner join incentive on employee.Employee_id = incentive.Eployee_ref_id where incentive.Incentive_amount > 3000;
```