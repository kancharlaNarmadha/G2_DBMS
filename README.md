# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
# AIM:
To create a student database and execute DDL queries using SQL.

# DDL (Data Definition Language)
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
# List of DDL commands:
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.
# Query:
# 1) Create a table student with the following fieds rollno,name,age,address,phoneno.
SQL QUERY:
 create table student(rollno int,name char(20),age int,address varchar(20),phoneno int);
OUTPUT:
![image](https://github.com/kancharlaNarmadha/G2_DBMS/assets/119559316/30a46a53-7411-4c2b-9e8e-f0d5560a9814)


2) Change the above student table by adding another attribute department
SQL QUERY:
alter table student add department char(30);
OUTPUT:
![image](https://github.com/kancharlaNarmadha/G2_DBMS/assets/119559316/bc2d96ac-3a8a-413d-a462-ea0bc4a081e6)


3) Drop the student table
SQL QUERY:
drop table student;
OUTPUT:
![image](https://github.com/kancharlaNarmadha/G2_DBMS/assets/119559316/d08c2635-bbe2-444f-a062-be2a639e519c)


4) Delete the student table using truncate keyword
SQL QUERY:
truncate table student;
OUTPUT:
![image](https://github.com/kancharlaNarmadha/G2_DBMS/assets/119559316/ff2ecbe2-67a6-49d1-9126-918ef7e529a5)


5) Rename the student table to mystudent
SQL QUERY:
alter table student rename to mystudent;
OUTPUT:
![image](https://github.com/kancharlaNarmadha/G2_DBMS/assets/119559316/4ac58148-044b-4790-8763-4f5930cf53ad)


RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
