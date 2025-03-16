# SQL

Connect to a MySQL database
```bash
mysql -h <host> -u <username> -p <password>
```

Create a database
```sql
CREATE DATABASE <database_name>; 
```

Use database
```sql
CREATE DATABASE <database_name>; 
```

Select data from a table
```sql
SELECT * FROM <table_name>;
```

Filter results with WHERE
```sql
SELECT * FROM <table_name> WHERE <condition>;
```

Sort results
```sql
SELECT * FROM <table_name> ORDER BY <column_name> ASC|DESC;
```

Insert data into a table
```sql
INSERT INTO table_name (column1, column2, column3,...columnN)
VALUES (value1, value2, value3,...valueN);
```

Update data in a table
```sql
UPDATE <table_name> SET column1 = value1 WHERE <condition>;
```

Delete data from a table
```sql
DELETE FROM <table_name> WHERE <condition>;
```

Create a new table
```sql
CREATE TABLE <table_name> (
 column1 datatype,
 column2 datatype,
 ...
);
```

Add a column to an existing table
```sql
ALTER TABLE <table_name> ADD COLUMN <column_name> <datatype>;
```

Drop a table
```sql
DROP TABLE <table_name>;
```