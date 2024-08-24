# SQL_Challenge
# Employee Database

![database](https://github.com/user-attachments/assets/f44047a6-2e17-4486-aff6-f7cec40d1b6b)


# Instruction

Research about people whom the company employed during the 1980s and 
1990s using the only six CSV files that remains of the employee database.
The Tables were sucessfully create and all the information from the
CSV files were importated.

# Data Modeling

Inspect the CSV files, and then sketch an Entity Relationship Diagram 
of the tables. To create the ERD Diagram. The QuickDBD was used in this project.

![ERD](https://github.com/user-attachments/assets/1de8900d-a14e-4507-bab0-866468a12ff0)


# Data Engineering

1. Use the provided information to create a table schema for each of the six CSV files, and specify data types, primary keys, foreign keys, and other constraints.

   o For the primary keys, verify that the column is unique. Otherwise, create a composite keyLinks to an external site., which takes two primary keys to uniquely identify a row.
   
   o Be sure to create the tables in the correct order to handle the foreign keys.
   
2. Import each CSV file into its corresponding SQL table.

# Data Analysis

1.    List the employee number, last name, first name, sex, and salary of each employee.
2.    List the first name, last name, and hire date for the employees who were hired in 1986.
3.    List the manager of each department along with their department number, department name, employee number, last name, and first name.
4.    List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
5.    List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
6.    List each employee in the Sales department, including their employee number, last name, and first name.
7.    List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
8.    List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).


# Table of Contents 

 1. ERD.png: an image file of the ERD
 2. Employee_CreatingTable.sql: a .sql file for creating the tables
 3. Employee_Queries.sql: a .sql file of the queries
 4. Employee_creatingtable _importing_queries.sql: a complete .sql file with creating importaing and queries.
 5. Eight .csv file for the output of each query.
 6. ERD_schema. md : ERD Schema
 7. Six Data files .csv
 
