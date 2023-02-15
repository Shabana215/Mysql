# Mysql
### SQL COMMANDS
* SQL commands are instructions. It is used to communicate with the database. It is also used to perform specific tasks, functions, and queries of data.
* SQL can perform various tasks like create a table, add data to tables, drop the table, modify the table, set permission for users.
### Types of SQL COMMANDS
> There are five types of SQL commands: DDL, DML, DCL, TCL, and DQL.
![](https://static.javatpoint.com/dbms/images/dbms-sql-command.png)

**1. Data Definition Language (DDL)**
* DDL changes the structure of the table like creating a table, deleting a table, altering a table, etc.
* All the command of DDL are auto-committed that means it permanently save all the changes in the database.
```
Here are some commands that come under DDL:

1. CREATE
1. ALTER
1. DROP
1. TRUNCATE
```

**1. CREATE:**
**CREATE** It is used to create a new table in the database.

**Syntax:**
`CREATE TABLE TABLE_NAME (COLUMN_NAME DATATYPES[SIZE]); `

**Example**
`CREATE TABLE EMPLOYEE(Name VARCHAR(20), Email VARCHAR(100), DOB DATE); `

**2. ALTER:**
 It is used to alter the structure of the database. This change could be either to modify the characteristics of an existing attribute or probably to add a new attribute.
 
 **Syntax:**
 
 To add a new column in existed table
 
 `ALTER TABLE table_name ADD column_name COLUMN-definition;  `

To modify existing column in the table

 `ALTER TABLE table_name MODIFY(column_definitions....);`
 
 **Examples**

` ALTER TABLE STU_DETAILS ADD(ADDRESS VARCHAR(20));`

` ALTER TABLE STU_DETAILS MODIFY (NAME VARCHAR(20));  `

 **3. Drop:**
 It is used to delete both the structure and record stored in the table.
 
 **Syntax:**
 `DROP TABLE table_name;  `
 
 **Example:**
 `DROP TABLE EMPLOYEE;`
 
 **4. Truncate:**
 It is used to delete all the rows from the table and free the space containing the table.
 
 **Syntax:**
 `TRUNCATE TABLE table_name;  `
 
 **Example:**
 `TRUNCATE TABLE EMPLOYEE;`


**2. Data Manipulation Language**
- DML commands are used to modify the database. It is responsible for all form of changes in the database.
- The command of DML is not auto-committed that means it can't permanently save all the changes in the database. They can be rollback.
```
Here are some commands under DML
1. Insert
2. Update
3. Delete
```

**1. Insert:**
The INSERT statement is a SQL query. It is used to insert data into the row of a table.

**Syntax:**

```
INSERT INTO TABLE_NAME    
(col1, col2, col3,.... col N)  
VALUES (value1, value2, value3, .... valueN); 
```
**OR**

```
INSERT INTO TABLE_NAME    
VALUES (value1, value2, value3, .... valueN);    
```

**Example:**
INSERT INTO EMPLOYEE (Regd_No, Name) VALUES ("101", "Sonoo");  

**2. Update:**

**3. Delete:**


**3. Data Control Language**
DCL commands are used to grant and take back authority from any database user.

Here are some commands that come under DCL:
1. Grant
2. Revoke
**4. Transaction Control Language**

TCL commands can only use with DML commands like INSERT, DELETE and UPDATE only.

These operations are automatically committed in the database that's why they cannot be used while creating tables or dropping them.

Here are some commands that come under TCL:
1. Commit
2. Rollback
3. Savepoint

**5. Data Query Language**

DQL is used to fetch the data from the database.

> It uses only one command:

1.  SELECT



