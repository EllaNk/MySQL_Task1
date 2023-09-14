# MySQL_Task1
![]()

## Introdution
This report serves as a Step into **MySQL** and its functionalities. The tasks involve creating a database, with two tables named Staff Info and Staff Salary with at least 10 rows of information in it respectively, and 4 constraints. This task aims to establish a basic understanding of MySQL and its fundamentals.


## Problem Statement:
1.	Create a database named “Staff”
2.	Create the following tables with at least 4 constraints for each
- Staff_Info (ID PK, Name, Age, DOE, Contract_Duration)
- Staff_Salary (ID FK, Salary, Yearly_Increment)
3.	Insert 10 rows of information into both tables
4.	Return the name and age of the staff
5.	Return ID and Salary of the staffs

![](SQL_(Staff_Info).png)

From the snapshot above, a database named **“Staff”** was created. Within the database, two tables were created **“Staff_Info”** and **"Staff_Salary”**, each containing unique set of information.
The process of creating the database was carried out using the below command:

_CREATE DATABASE (Database Name);_

## Similarly, creating the tables was achieved using the below command:

_CREATE TABLE (Tabel_Name);_

## In creating a table with specific columns, the following syntax was used and the snapshot below:

_USE (Database Name);_

_CREATE TABLE Staff_Info (ID INT PRIMARY KEY AUTO_INCREMENT, Name VARCHAR(50) UNIQUE,_
_Age INT, DOE DATE, Contract_Duration INT DEFAULT 23);_

## Creating rows of tables with informations, the following command was carried out:

_INSERT INTO Staff_info (ID, Name, Age, DOE, Contract_Duration)_

_values (ID, Age, DOE, Contract_Duration);_

## Selection of Data From Columns:

![](SQL_(Name_&_Age).png)

The snapshot above shows the selection of data from two specific columns. This was achieved using the following command:

## To return only the “Name" and "Age” columns from the table:

_SELECT * FROM (Table_Name);_

_SELECT Name, ID FROM (Table_Name);_

This command enables the selection of desired columns from the specified table, making it easy to assess the information needed from the column.

## Conclusion


Completing these tasks not only provided the basics of **MySQL** but also provided valuable hands on experience, which is essential for tackling more advanced SQL challenges.





