# Mysql
### SQL COMMANDS
* SQL commands are instructions. It is used to communicate with the database. It is also used to perform specific tasks, functions, and queries of data.
* SQL can perform various tasks like create a table, add data to tables, drop the table, modify the table, set permission for users.
### Types of SQL COMMANDS
> There are five types of SQL commands: DDL, DML, DCL, TCL, and DQL.
![](https://static.javatpoint.com/dbms/images/dbms-sql-command.png)
1. **Data Definition Language (DDL)**
* DDL changes the structure of the table like creating a table, deleting a table, altering a table, etc.
* All the command of DDL are auto-committed that means it permanently save all the changes in the database.
```
Here are some commands that come under DDL:

1. CREATE
2. ALTER
3. DROP
4.  TRUNCATE
```
2. **Data Manipulation Language**
- DML commands are used to modify the database. It is responsible for all form of changes in the database.
- The command of DML is not auto-committed that means it can't permanently save all the changes in the database. They can be rollback.
```
Here are some commands under DML
* Insert
* Update
* Delete
```
3. **Data Control Language**
DCL commands are used to grant and take back authority from any database user.

Here are some commands that come under DCL:
* Grant
* Revoke
4. **Transaction Control Language**

TCL commands can only use with DML commands like INSERT, DELETE and UPDATE only.

These operations are automatically committed in the database that's why they cannot be used while creating tables or dropping them.

Here are some commands that come under TCL:
* Commit
* Rollback
* Savepoint
5. **Data Query Language**

DQL is used to fetch the data from the database.

> It uses only one command:

*  SELECT



