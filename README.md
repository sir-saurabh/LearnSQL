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
1. Start and Login: <br> <img src = 'Screenshot 2025-04-07 221315.png'>
2. Show databases: <br> <img src = 'Screenshot 2025-04-07 221337.png'>
3. Create and use databases, Create table: <br> <img src = 'Screenshot 2025-04-07 221458.png'>
4. Inserting data in tables: <br> <img src = 'Screenshot 2025-04-07 221524.png'>
5. Show the Databases and Tables: <br> <img src = 'Screenshot 2025-04-07 221549.png'>
6. Show Table contents and Deleting table and database: <br> <img src = 'Screenshot 2025-04-07 221616.png'>
