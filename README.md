# sql_syllabus

### 1. Database

    A Database is an organized collection of data stored electronically.

 **Example table:**

    Student_ID     Name         Department
    
     101            Suganya       CSE 
     
     102            Divya         IT
     

### 2 DBMS (Database Management System)

    A DBMS is software that allows users to create, store, update, delete, and retrieve data from a database.

    Features: Create databases Insert records Update records Delete records Search data Manage users Examples: FoxPro dBase Microsoft Access
    

### 3. RDBMS (Relational Database Management System)

    An RDBMS is an advanced type of DBMS where data is stored in tables, and relationships are established using Primary Keys and Foreign Keys.

**Example:**

Department Table:

    Dept_ID    Department 
    
     1          CSE 
     
     2          IT


### 4. SQL (Structured Query Language)

    SQL is a standard language used to create, manage, and manipulate data in relational databases.

**Uses of SQL:**
    - Create databases and tables
    - Insert data
    - Retrieve data
    - Update data
    - Delete data
    - Manage users and permissions
    - Create views, indexes, and stored procedures
    
### 5. MYSQL

    MySQL is an open-source RDBMS developed by Oracle Corporation that stores data in tables and uses SQL to perform database operations.

Features of MySQL

    -Open source
    -Fast and reliable
    -Supports multiple users
    -Stores data in tables

    
### CREATE DATABASE

<img width="553" height="82" alt="Screenshot 2026-08-04 192628" src="https://github.com/user-attachments/assets/7a0754a1-924b-450b-874e-8b367ceaa085" />


### CREATE TABLE

**Definition**

    A table is a database object that stores related information in the form of rows (records) and columns (fields).

**Structure of a Table**

    Column (Field): Defines the type of information stored (e.g., employee_id, name, salary).
    
    Row (Record): Represents one complete set of data.

#### CREATE EMPLOYEE1 TABLE

<img width="948" height="383" alt="image" src="https://github.com/user-attachments/assets/2fc6444a-f1fa-4604-a430-5b45cd65e49d" />

#### CREATE ATTENDANCE1 TABLE

<img width="920" height="334" alt="image" src="https://github.com/user-attachments/assets/8e176980-e420-42de-86d0-f206d46be255" />

#### CREATE PAYROLL1 TABLE

<img width="911" height="387" alt="image" src="https://github.com/user-attachments/assets/7517e2c0-6b6e-4978-adbf-0116a57f7f83" />

#### CREATE LEAVE_REQUESTS1 TABLE

<img width="951" height="425" alt="image" src="https://github.com/user-attachments/assets/26f08838-a2fe-41f6-ab86-2091a26b0059" />


### INSERT 

**Definition:**
    
    The INSERT command is used to add one or more new records into a database table. It allows users to store new information in the database.
    

#### INSERT DATAS INTO EMPLOYEE1 TABLE

<img width="1082" height="516" alt="image" src="https://github.com/user-attachments/assets/c100a620-b074-4a39-8dc3-860ac3edb893" />

#### INSERT DATAS INTO ATTENDANCE1 TABLE

<img width="925" height="547" alt="image" src="https://github.com/user-attachments/assets/c6947df7-3078-4adf-a10f-ca47ec516ec6" />

#### INSERT DATAS INTO PAYROLL1 TABLE

<img width="944" height="538" alt="image" src="https://github.com/user-attachments/assets/275dcc4e-abf6-4816-9a2a-a6c5fb01fb97" />

#### INSERT DATAS INTO LEAVE_REQUESTS1 TABLE

<img width="1032" height="523" alt="image" src="https://github.com/user-attachments/assets/04d1cd72-c6f7-4b90-8e0a-aab7266bb097" />


### SELECT 

**Definition:**

    The SELECT command is the most commonly used SQL command. It retrieves data from one or more tables and can be combined with clauses such as WHERE, ORDER BY, GROUP BY, and HAVING to produce meaningful results.
    
#### RETRIVES EMPLOYEE1 TABLE

<img width="689" height="284" alt="image" src="https://github.com/user-attachments/assets/1743c8e2-5321-41e3-acc4-7d8542cab0ce" />

#### RETRIVES ATTENDANCE1 TABLE

<img width="478" height="269" alt="image" src="https://github.com/user-attachments/assets/564f6e3d-09d6-47fd-adf7-25f948cad59c" />

#### RETRIVES PAYROLL1 TABLE

<img width="567" height="291" alt="image" src="https://github.com/user-attachments/assets/f00efe9c-67b2-4766-b7f6-62f6320e3749" />

#### RETRIVES LEAVE_requests1 TABLE

<img width="618" height="275" alt="image" src="https://github.com/user-attachments/assets/5374f930-5057-4bba-afe2-f12b3fd63026" />


### FROM Clause

**Definition:**

    The FROM clause is used to specify the table from which the data will be retrieved. It tells the SQL query where to fetch the records.

**example**
<img width="689" height="284" alt="Screenshot 2026-08-04 201110" src="https://github.com/user-attachments/assets/6664ebe3-fec6-4e8a-930a-a07e2a04320d" />


### WHERE Clause

**Definition:**

    The WHERE clause is used to filter records based on a specified condition. It returns only those rows that satisfy the given condition.

<img width="796" height="176" alt="image" src="https://github.com/user-attachments/assets/79f1727d-1c3a-461b-b70b-4c231703cdf4" />


### ORDER BY Clause

**Definition**

    The ORDER BY clause is used to sort the result set in either ascending (ASC) or descending (DESC) order based on one or more columns.

<img width="675" height="285" alt="image" src="https://github.com/user-attachments/assets/9766f04b-b53d-46e0-8325-00e0b60b30c2" />


### GROUP BY Clause

**Definition:**

    The GROUP BY clause is used to group rows that have the same values in a specified column into summary rows. It is commonly used with aggregate functions such as COUNT(), SUM(), AVG(), MIN(), and MAX().


### 1. COUNT()
**Definition:**

    The COUNT() function is used to count the total number of rows or non-NULL values in a column.

<img width="535" height="318" alt="image" src="https://github.com/user-attachments/assets/1372fa4a-ecab-4271-8b7f-2f3692888a6b" />


### 2. SUM()
Definition:

The SUM() function is used to calculate the total sum of numeric values in a specified column.

<img width="527" height="316" alt="image" src="https://github.com/user-attachments/assets/581c6826-8e8a-4a5b-81d2-482c3021cc05" />


### 3. AVG()
 
**Definition:**

    The AVG() function is used to calculate the average value of a numeric column.

<img width="656" height="320" alt="image" src="https://github.com/user-attachments/assets/a44bbb96-805e-4f34-b789-0ef5f5a53790" 


### 4. MAX()

**Definition:**

    The MAX() function is used to return the highest value from a specified column.

<img width="676" height="312" alt="image" src="https://github.com/user-attachments/assets/772174f8-951b-4fc9-8e6d-acd8c4c70f62" />


### 5. MIN()

**Definition:**

    The MIN() function is used to return the lowest value from a specified column.

<img width="616" height="313" alt="image" src="https://github.com/user-attachments/assets/51a79de9-a03f-4713-9340-dd5edef27e28" />


### HAVING Clause

**Definition:**

    The HAVING clause is used to filter grouped records after the GROUP BY clause has been applied. It is mainly used with aggregate functions.

<img width="601" height="294" alt="image" src="https://github.com/user-attachments/assets/cf104ba7-a6b8-4e66-b0b3-6e54ab6d4889" />


### LIMIT Clause

**Definition:**

    The LIMIT clause is used to restrict the number of rows returned by a query. It is useful when you want to display only a specific number of records.

<img width="613" height="222" alt="image" src="https://github.com/user-attachments/assets/5f1c37c0-452b-4a61-b9cf-98d1631d2db1" />




### ALTER 

**definition:**

    MySQL ALTER statement is used when you want to change the name of your table or any table field.
    
    It is also used to add or delete an existing column in a table.
    
    The ALTER statement is always used with "ADD", "DROP" and "MODIFY" commands according to the situation.
    
<img width="1972" height="228" alt="image" src="https://github.com/user-attachments/assets/4e6c586a-cd18-4f2a-ae09-b3294c407e5a" />


#### Add a new column

<img width="708" height="335" alt="image" src="https://github.com/user-attachments/assets/4948ff53-af3c-4a13-b5cb-e4ca7046204f" />

#### Modify a column datatype

<img width="682" height="318" alt="image" src="https://github.com/user-attachments/assets/9840ea2b-0d4a-4c29-ae75-49199c1b6e94" />

#### Change column name and datatype

<img width="651" height="347" alt="image" src="https://github.com/user-attachments/assets/39ce6df2-5827-45aa-879d-fda288a8e927" />

#### Rename a column

<img width="699" height="345" alt="image" src="https://github.com/user-attachments/assets/02b6c15e-3531-4f1b-af57-f5b4eb8826a5" />


### UPDATE 

**Definition:**

    The UPDATE command is used to modify the existing records in a table. It can update one or multiple rows based on a specified condition.
    
<img width="702" height="495" alt="image" src="https://github.com/user-attachments/assets/e1bf28d5-d5dd-4f1d-9168-bf24fa6adf4b" />


### DELETE

**Definition:**

    The DELETE command is used to remove one or more records from a table. It supports conditions to delete only the required records while keeping the table structure unchanged.

<img width="802" height="280" alt="image" src="https://github.com/user-attachments/assets/0012cc45-dce6-4b94-8b9f-c270685a7f88" />


### TRUNCATE

**Definition:**

    The TRUNCATE command is used to remove all records from a table while preserving the table structure, columns, indexes, and constraints. It is faster than the DELETE command because it removes all rows at once.

<img width="720" height="215" alt="image" src="https://github.com/user-attachments/assets/afaffec3-1bc3-46a2-829a-995172eb790c" />


### DROP

**Definition:**

    The DROP command is used to permanently remove a database object, such as a table or database, along with all its data, structure, indexes, and constraints. Once dropped, the object cannot be used unless it is created again.

<img width="605" height="222" alt="image" src="https://github.com/user-attachments/assets/9b6e45b4-fa9c-432e-bce0-e98604f5c9bb" />

### INNER JOIN

**Definition:**

    INNER JOIN is used to retrieve only the records that have matching values in both tables. If there is no matching record in either table, it is not included in the result.

**Key Point:** Returns only matching rows from both tables.

<img width="630" height="355" alt="image" src="https://github.com/user-attachments/assets/7f1e62bd-4a5a-4220-a2db-86641956f980" />

### LEFT JOIN (LEFT OUTER JOIN)

**Definition:**

    LEFT JOIN is used to retrieve all records from the left table and the matching records from the right table. If there is no matching record in the right table, the result displays NULL values for the right table's columns.

**Key Point:** Returns all rows from the left table and only the matching rows from the right table.

<img width="649" height="356" alt="image" src="https://github.com/user-attachments/assets/b14b3f13-71f5-425d-ba45-c2edd832a802" />

### RIGHT JOIN (RIGHT OUTER JOIN)

**Definition:**

    RIGHT JOIN is used to retrieve all records from the right table and the matching records from the left table. If there is no matching record in the left table, the result displays NULL values for the left table's columns.

**Key Point:** Returns all rows from the right table and only the matching rows from the left table.

<img width="662" height="348" alt="image" src="https://github.com/user-attachments/assets/c919b5c3-92f0-40f3-b7e4-b2b90e20135c" />










