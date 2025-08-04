## emp_noが40000の従業員の1996年~1997年にかけての給料を教えてください。

### 答え
65185

### SQL
```sql
    SELECT salary
    FROM salaries
    WHERE emp_no = 40000
    AND from_date <= '1997-08-20'
    AND to_date >= '1996-08-20'
    ORDER BY from_date ASC
    LIMIT 1;
```
