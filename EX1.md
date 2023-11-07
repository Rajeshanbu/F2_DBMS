# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE:04/08/23
## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```sql
create table student(rollno int,name varchar(20),age int,address varchar(20),phoneno int);
```
### OUTPUT:
![ex1](https://github.com/Rajeshanbu/F2_DBMS/assets/118924713/8074871a-32fc-49dd-8b49-35f13b6f14f6)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
alter table student add(department varchar(20));
```
### OUTPUT:
![ex02](https://github.com/Rajeshanbu/F2_DBMS/assets/118924713/a846e4b4-b33b-4048-840d-ac2e846bdffa)


### 3) Drop the student table
 
### SQL QUERY: 
```sql
drop table student;
```
### OUTPUT:
![ex3](https://github.com/Rajeshanbu/F2_DBMS/assets/118924713/2b87897d-48ec-471f-8ff2-368035d0c93c)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```sql
truncate table student;
```
### OUTPUT:

![ex4](https://github.com/Rajeshanbu/F2_DBMS/assets/118924713/954e3b01-3d35-496c-abf3-2cc6bbe26fb0)


### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
alter table student rename to myystudent;
```
### OUTPUT:
![ex5](https://github.com/Rajeshanbu/F2_DBMS/assets/118924713/fef777f7-b1d5-42d8-a707-69993ea78ff8)
