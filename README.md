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
    
#### RETRIVE EMPLOYEE1 TABLE

<img width="689" height="284" alt="image" src="https://github.com/user-attachments/assets/1743c8e2-5321-41e3-acc4-7d8542cab0ce" />

#### RETRIVE ATTENDANCE1 TABLE

<img width="478" height="269" alt="image" src="https://github.com/user-attachments/assets/564f6e3d-09d6-47fd-adf7-25f948cad59c" />

#### RETRIVE PAYROLL1 TABLE

<img width="567" height="291" alt="image" src="https://github.com/user-attachments/assets/f00efe9c-67b2-4766-b7f6-62f6320e3749" />

#### RETRIVE LEAVE_requests1 TABLE

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

<img width="656" height="320" alt="image" src="https://github.com/user-attachments/assets/a44bbb96-805e-4f34-b789-0ef5f5a53790" />


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

### DISTINCT

**Definition**

    DISTINCT is a SQL keyword used to remove duplicate values from the result set and return only unique (different) records from one or more columns.

    It is commonly used when a table contains repeated values and you want to display each value only once.

<img width="608" height="233" alt="image" src="https://github.com/user-attachments/assets/32d8ed41-cfd2-413b-ac9b-bd09c6ae31ca" />

### ARITHMETIC OPERATORS:

**Definition:**

    Arithmetic operators are used to perform mathematical calculations on numeric values in SQL.

##### + (Addition):

     Adds two numeric values.

<img width="678" height="440" alt="image" src="https://github.com/user-attachments/assets/de74f059-3591-4db7-81f3-4b99a4c5690e" />

#### Subtraction (-)
 
    Subtracts one numeric value from another.
    
<img width="827" height="426" alt="image" src="https://github.com/user-attachments/assets/638baccb-c81c-4bd4-9177-42c5268f8eb1" />

#### * (MULTIPLICATION)

    Multiplies two numeric values.

<img width="693" height="384" alt="image" src="https://github.com/user-attachments/assets/5e2689f9-b36e-4827-8667-81ccbddbd6b9" />

#### /  (DIVITION)

    Divides one numeric value by another.

<img width="648" height="372" alt="image" src="https://github.com/user-attachments/assets/bff3312b-ca86-455d-8f13-90a751c839dc" />


### COMPARITION OPERATORS

**Definition:**

    Comparison operators are used to compare two values. They return TRUE if the condition is satisfied; otherwise, they return FALSE.

	
#### = (equal to)

     Checks if two values are equal.

<img width="867" height="242" alt="image" src="https://github.com/user-attachments/assets/382253d7-2f93-4d04-92e3-3d228079bf46" />

     
#### != or <> (not equal to)

    Checks if two values are not equal.

<img width="823" height="278" alt="image" src="https://github.com/user-attachments/assets/72010598-c531-432e-b213-ffb5da97ec56" />


    
#### > (greater then)

       Checks if the left value is greater than the right value.

<img width="740" height="274" alt="image" src="https://github.com/user-attachments/assets/e816c6b7-e5d8-45af-91df-209bd3044a24" />

       
#### < (lesser then)	

    Checks if the left value is less than the right value.

<img width="832" height="227" alt="image" src="https://github.com/user-attachments/assets/1ee83ec9-e301-4e44-8213-9352184adc9e" />

#### >= (greater then or equal to)

       	Checks if the left value is greater than or equal to the right value.

<img width="825" height="322" alt="image" src="https://github.com/user-attachments/assets/61f1c458-7d01-4369-940a-841f63a70ecf" />

        
#### <= (lesser then or equal to)	

    Checks if the left value is less than or equal to the right value.

<img width="827" height="289" alt="image" src="https://github.com/user-attachments/assets/d692460f-9609-4ac2-9f0a-be39ec0ab421" />



### LOGICAL OPEARATOR

**Definition:**

    Logical operators are used to combine multiple conditions in a SQL query.


#### AND	

    Returns TRUE only if all conditions are TRUE.

<img width="678" height="308" alt="image" src="https://github.com/user-attachments/assets/e9ea64aa-6181-493d-b0bf-118d4669aec8" />

	
#### OR	
    Returns TRUE if at least one condition is TRUE.

<img width="696" height="317" alt="image" src="https://github.com/user-attachments/assets/71521f6e-fc2e-4c9f-80ec-0062ade3bb93" />

	
#### NOT	

    Reverses the result of a condition (TRUE becomes FALSE and FALSE becomes TRUE).

<img width="657" height="330" alt="image" src="https://github.com/user-attachments/assets/e61d2fdc-997c-4f18-bc34-b0f8f0975b89" />


### SPECIAL OPEARATORS

**Definition:**

    Special operators are used to perform special types of comparisons and filtering in SQL queries.

#### BETWEEN	

    Selects values within a specified range (inclusive).

<img width="671" height="242" alt="image" src="https://github.com/user-attachments/assets/a9e81905-0784-46e7-ab3d-65910f45441f" />

#### IN	

    Checks whether a value matches any value in a given list.

<img width="788" height="307" alt="image" src="https://github.com/user-attachments/assets/22305ea5-57fb-45a6-8168-57fa31346036" />

	
#### NOT IN	

    Checks whether a value does not match any value in a given list.

<img width="711" height="243" alt="image" src="https://github.com/user-attachments/assets/b45ef5a8-3c98-4697-9904-4a111e47326b" />

	
#### LIKE

     Searches for a specified pattern in a column.
	 
<img width="793" height="293" alt="image" src="https://github.com/user-attachments/assets/bbf4cad5-5383-4537-bbe7-bc8993c8a1f2" />


	 
#### IS NULL	

    Checks whether a column contains NULL values.

<img width="810" height="272" alt="image" src="https://github.com/user-attachments/assets/828f3f0d-1d72-4c43-bb94-b8c7c8fe283b" />

#### IS NOT NULL	

    Checks whether a column contains non-NULL values.

<img width="753" height="338" alt="image" src="https://github.com/user-attachments/assets/1746cde9-13fc-44ea-85e5-1059fd4283b7" />

### STRING FUNCTIONS

**Definition:**

    String functions are built-in SQL functions used to manipulate and process text (character) data.

#### CONCAT()	

    Combines two or more strings into a single string.

<img width="690" height="393" alt="image" src="https://github.com/user-attachments/assets/1aedf951-6c31-4a6c-bf33-7507ee59e395" />

#### UPPER()	

    Converts all characters in a string to uppercase.

<img width="739" height="336" alt="image" src="https://github.com/user-attachments/assets/25ab55f3-bdaa-4aca-8e30-cf8ee68e0a48" />

#### LOWER()

    Converts all characters in a string to lowercase.

<img width="651" height="376" alt="image" src="https://github.com/user-attachments/assets/b9cd175d-2147-4139-bbd0-da5fa9c60223" />

#### LENGTH()	

    Returns the number of bytes in a string.

<img width="615" height="341" alt="image" src="https://github.com/user-attachments/assets/7b2a60c2-0786-457f-99a2-684148621dae" />

#### CHAR_LENGTH()	

    Returns the number of characters in a string.

<img width="798" height="381" alt="image" src="https://github.com/user-attachments/assets/5a586a2a-e9af-416d-8299-19888fdb0c3f" />

#### SUBSTRING()	

    Extracts a specified part of a string.

<img width="610" height="377" alt="image" src="https://github.com/user-attachments/assets/2898ac61-7686-4bb8-9682-a31d7f12443d" />


#### LEFT()	

    Returns the leftmost specified number of characters from a string.

<img width="734" height="450" alt="image" src="https://github.com/user-attachments/assets/13c8cb2d-4f0f-449e-bab5-3df33dad051f" />

#### RIGHT()

    Returns the rightmost specified number of characters from a string.

<img width="700" height="378" alt="image" src="https://github.com/user-attachments/assets/b4224f17-d669-4dc4-9d23-bb275cfb9816" />

#### REPLACE()

    Replaces all occurrences of a specified substring with another substring.

<img width="630" height="309" alt="image" src="https://github.com/user-attachments/assets/5f5e2e48-833f-40bd-8890-0c768840a708" />

#### TRIM()

    Removes leading and trailing spaces from a string.

<img width="698" height="230" alt="image" src="https://github.com/user-attachments/assets/38f0580a-1bcb-4b54-bfbb-32b968228f04" />

#### REVERSE()	

    Reverses the characters in a string.

<img width="700" height="343" alt="image" src="https://github.com/user-attachments/assets/a5328837-2caf-4514-8d7c-39b7841a1dea" />



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

### SUB QUERY

**Definition:**

    A subquery is a query written inside another SQL query. It is used to obtain a result that is then used by the outer query
	.
#### Employees whose CTC is greater than average CTC

<img width="818" height="352" alt="image" src="https://github.com/user-attachments/assets/e716d2db-563c-41ff-be61-4846addabbcc" />

#### Employees who have attendance status Absent

<img width="930" height="339" alt="image" src="https://github.com/user-attachments/assets/cb6a2696-1f2c-43fc-ab9e-c97a80f70c18" />


### CTE (COMMON TABLE EPRESSION)

**Definition:**

    CTE (Common Table Expression) is a temporary named result set created using the WITH keyword. It makes complex queries easier to read and reuse.

	
#### Calculate net salary using CTE

<img width="635" height="543" alt="image" src="https://github.com/user-attachments/assets/a765ac18-91de-444f-b28e-984ecc8dcdc8" />

#### CTE with attendance

<img width="639" height="353" alt="image" src="https://github.com/user-attachments/assets/f4660bea-b561-49c2-be9d-b210f432f189" />


### WINDOW FUNCTIONS

**Definition:**

    A window function performs calculations across a set of related rows without combining those rows into a single row.

    Unlike GROUP BY, a window function keeps the individual rows.
**
Common window functions:**

    ROW_NUMBER()
    RANK()
    DENSE_RANK()
    SUM()
    AVG()
    MIN()
    MAX()
    LAG()
    LEAD()

#### ROW_NUMBER()

**Definition:**

    ROW_NUMBER() assigns a unique sequential number to each row based on the specified ordering.

#### Rank employees according to CTC:


<img width="672" height="467" alt="image" src="https://github.com/user-attachments/assets/4fa71044-6a41-4096-9582-535eeecd7a55" />

#### RANK()

**Definition:**

    RANK() assigns a rank to each row based on the specified ordering. If two rows have the same value, they receive the same rank, and the next rank is skipped.


<img width="626" height="448" alt="image" src="https://github.com/user-attachments/assets/c6f76cee-3bc4-4b4d-8577-4506fadac3c0" />


#### DENSE_RANK()

**Definition:**

    DENSE_RANK() assigns the same rank to equal values, but unlike RANK(), it does not skip the next rank.

<img width="635" height="456" alt="image" src="https://github.com/user-attachments/assets/8511df5c-2180-4ae4-8f1d-04c48ef4881b" />


### PARTITION BY

**Definition:**

    PARTITION BY divides the rows into groups before applying a window function.


<img width="676" height="550" alt="image" src="https://github.com/user-attachments/assets/682aa976-084a-424b-8da3-27866c975610" />


### LEAD()

**Definition:**

    LEAD() retrieves the value from the next row in the specified order.

<img width="633" height="423" alt="image" src="https://github.com/user-attachments/assets/cf6f53a1-3808-401a-a3d4-66d7f6825fc8" />


### LAG()

**Definition:**

    LAG() retrieves the value from the previous row in the specified order.

<img width="689" height="431" alt="image" src="https://github.com/user-attachments/assets/a3f8866d-93c5-4627-990f-e70611087485" />


### VIEW

**definition:**

     A VIEW in SQL is like a virtual table. It doesn’t store data itself but shows the result of a query as if it were a table. You can query a view just like a normal table.

<img width="473" height="220" alt="image" src="https://github.com/user-attachments/assets/6d7fde00-0003-4382-930b-72627d56a44a" />

<img width="637" height="227" alt="image" src="https://github.com/user-attachments/assets/24e11fdd-5ff7-47c7-aec2-79a6d75d663f" />

### stored procedures

    A Stored Procedure in SQL is a precompiled collection of one or more SQL statements stored in the database, which can be executed as a single unit. It improves performance, supports parameters, enhances security, and allows reuse of complex logic.

<img width="704" height="400" alt="image" src="https://github.com/user-attachments/assets/e0654f67-862b-4731-9a90-d23d3b3dd5c1" />

<img width="697" height="107" alt="image" src="https://github.com/user-attachments/assets/b5bd46cf-2276-481b-b4fc-44fd937b54ec" />


	

