# Ex-01:
## SQL QUERY TO FETCH "FIRTS-NAME" FROM THE WORKER TABLE USING THE ALIAS NAME FROM THE SAMPLE DATA
### AIM:
To fetch first name from the worker table using alias from the sample data using SQL query.
### ALGORITHM:
1. Create a table named "worker" with required columns.
2. Insert the sample data into the "worker" table.
3. Fetch the first names by executing the SQL query: "SELECT name AS FIRST_NAME FROM worker;".
4. Retrieve the result set containing the first names from the query execution.
5. Display or process the retrieved first names as needed.
### PROGRAM:
```sql
CREATE TABLE worker (
    id INT,
    name VARCHAR(50),
    age INT,
    salary DECIMAL(10, 2)
);
INSERT INTO worker (id, name, age, salary)
VALUES
    (1, 'John', 30, 5000.00),
    (2, 'Jane', 25, 4500.00),
    (3, 'Mike', 35, 6000.00),
    (4, 'Sarah', 28, 5500.00),
    (5, 'David', 32, 5200.00);
SELECT name AS FIRST_NAME
FROM worker;
```
### OUTPUT:
![1](https://github.com/KeerthikaNagarajan/EX-01-SQL/assets/93427089/5e6f957a-8373-49eb-b2d4-574ab85a8b2c)

### RESULT:
Thus, a sql query to fetch first name from worker table using alias from sample data is executed successfully.

