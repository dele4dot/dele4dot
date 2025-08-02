```sql
SELECT: Initiates the SQL command to retrieve data. (age, age + 10,)
column1, column2, ...: Specifies the columns you want to retrieve. Use * to select all columns.
FROM: Identifies the table containing the data. (db.table_name)
WHERE
ORDER BY DESC|ASC
;: Ends the SQL statement
```
- PEMDAS
- Wildcard Characters [%,_]: % (any number of random characters) e.g SELECT * FROM employees WHERE surname LIKE "s%" OR "%r) || _ook OR ____-01-__
-  WHERE amount > 100;  WHERE event_date BETWEEN '2023-01-01' AND '2023-12-31'; WHERE name LIKE '%pro%' AND price >= 50;
-  Logical Operator (AND, OR, NOT)

## Data Manipulation Language
Data Manipulation Language (DML) is used to manage and manipulate data stored in the database.
DML statements allow you to perform various operations like inserting new data, updating existing data, or deleting unwanted data. It provides a way to interact with the actual data in the database.

```SQL
Create Database School;
USE School;

CREATE TABLE Student(
id INT PRIMARY KEY AUTO_INCREMENT,
name VARCHAR(50),
age INT
)

INSERT INTO STUDENT(name, age)
VALUES ('segun Odoo',50}, ('Maxwell Fish', 45)
```
