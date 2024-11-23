#### The components of a DBMS(Database Management System)
1. **Hardware**: This is the physical component of the system, such as hard disks, I/O
devices which are channels for data.
2. **Software**: The programs that control and manage the database.
3. **Data**: Raw facts and information that are stored, processed, and accessed by the DBMS.
4. **Procedures** : The instructions and rules that govern how the DBMS is used and designed
5. **Database Access Language**: The language used to access, update, and  delete data in the database
6. **Query Processor**: Transforms user queries into a series of low-level instructions
7. **Run Time Database Manager**:  Interfaces with user queries and application programs, and handles database access at run time

**A Relational database** is a database that organizes data into tables with rows and columns, and each piece of data is related to other data within the database through defined relationships.
**Examples** MySQL, PostgreSQL, Oracle Database

#### Classifications of SQL
1. **Data Defination Language(DDL)** - Commands are used to define and modify the structure of a database, including creating, altering, and dropping tables, indexes, and views<br>
   **Key Commands**: CREATE, ALTER, DROP, TRUNCATE
2. **Data Manipulation Language (DML)** - DML commands are used to manipulate data within existing tables, such as inserting new records, updating existing ones, and deleting records<br>
   **Key Commands**: SELECT, INSERT, UPDATE, DELETE
3. **Data Control Language (DCL)** - DCL commands manage user access and permissions to database objects, allowing administrators to grant or revoke privileges for specific users.<br>
   **key Commands**:  GRANT, REVOKE

#### Difference between a Primary Key and a Foreign Key
Primary key uniquely identifies a record in a single table, while a foreign key links data in one table to a primary key in another table.

**ERD** is a visual representation that shows how different entities (people, objects, or concepts) relate to each other within a system.

#### Advantages of  relational databases
1. Capability for multiple users to collaborate on the same data.
2. Efficient data management for large volumes.
3. Ease of complex querying with SQL.
4. Structured data storage.
5. Data integrity through relationships between tables.

#### Types of data type used to store data in tables
**Char**: Stores character values enclosed in single quotes. examples CHAR, VARCHAR
**Number**: Stores numbers, both integers and decimals. Examples INT, FLOAT, DECIMAL
**Date and Time Data Types**: Stores temporal data like dates and times. Examples DATE, TIME
**Boolean Data Type**: Stores logical values representing true/false conditions.

#### Purpose of a database management system (DBMS)
1. Data storage and  organization
2. Data retrival and querying
3. Data security and access control
4. Data backup and recovery
5. Data integrity and consistency
   
