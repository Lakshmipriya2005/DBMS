# EXP NO 2: DATA DEFINITION LANGUGE COMMANDS 
### DATE
## AIM:
To create a student database and execute DDL queries using SQL.


## THEORY
### DDL (Data Definition Language)

* DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema.
* It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database.
* DDL is a set of SQL commands used to create, modify, and delete database structures but not data.
* These commands are normally not used by a general user, who should be accessing the database via an application.

 
### List of DDL commands: 
1. CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
2. DROP: This command is used to delete objects from the database.
3. ALTER: This is used to alter the structure of the database.
4. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
5. RENAME: This is used to rename an object existing in the database.

## Query:
### 1) Create a database studentdb

### SQL QUERY:
'''
create database studentdb;
'''

### OUTPUT:
![Screenshot 2023-10-18 132226](https://github.com/DrUmaRaniV/DBMS/assets/115525361/a3e6353a-d59e-4f9f-98c8-4e66401f40ac)


### 2) Create a table student with the following fieds RegisterNumber,Name,Age,Address,Phone number

### SQL QUERY: 


### OUTPUT:
![Screenshot 2023-10-18 132258](https://github.com/DrUmaRaniV/DBMS/assets/115525361/240a8aab-3b54-44a0-94ac-40113eb12427)


### 3) Alter the above student table by adding another attribute department

### SQL QUERY: 

### OUTPUT:
![Screenshot 2023-10-18 132314](https://github.com/DrUmaRaniV/DBMS/assets/115525361/f381586a-1f6d-466d-a653-e8e21797fab4)



### 4) Drop the student table
 
### SQL QUERY: 


### OUTPUT:


![drop](https://github.com/DrUmaRaniV/DBMS/assets/115525361/565279e8-4b21-402f-b065-d31c3910f4e9)






### 5) Delete the student table using truncate keyword

### SQL QUERY: 


### OUTPUT:

![truncate](https://github.com/DrUmaRaniV/DBMS/assets/115525361/5ad9e0b1-8f28-4bf1-807a-7d7ef820ab14)




### 6) Rename the student table to mystudent

### SQL QUERY: 



### OUTPUT:
![Screenshot 2023-10-18 132403](https://github.com/DrUmaRaniV/DBMS/assets/115525361/964f23c8-7901-4de3-80b1-630ebad06fa1)



## Result:
         Thus the basic DDL commands in SQL are executed. 


