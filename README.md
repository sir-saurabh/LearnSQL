# All MySQL query using command prompt
Date: 05/04/2025

# Basics
1. Command to login as root user in the MySQL using command prompt<br>
`mysql -u root -p`

2. List all the databases. <br> `show databases;`
3. To create new database. <br> `create database Your_database_name;`
4. To use a database.<br> `use Your_database_name;`
5. To create a table in a database. <br> `create tabel Your_table_name(Col1 data_type, col2 data_type, ... , coln data_type);` <br> Example till now: <br> `create database cse;`<br> `use cse;` <br> `create table student(Name varchar(30), Roll int not null primary key, Goal varchar(30));` 
6. To insert element into the table. <br>
  `insert Your_table_name values (Val1 data_type,... ,Valn data_type);`
   <br> For example: `insert student("Saurabh", 32, "GATE");`

7. To delete a database:<br> `DROP database Your_database_name;`
8. To delete a table:<br> `DROP table Your_table_name;`
9. To show a table:<br> `select * from Your_table_name;`
10. To show the list of tables within the database: <br> `show tables;`

## Command Line Screen Sort
1. Start and Login: <br> <img src = ''>
2. Show databases: <br> <img src = ''>
3. Create and use databases: <br> <img src = ''>
4. Create tables: <br> <img src = ''>
5. Inserting data in tables: <br> <img src = ''>
6. Show the table contents: <br> <img src = ''>
7. Deleting table and database: <br> <img src = ''>
8. 
