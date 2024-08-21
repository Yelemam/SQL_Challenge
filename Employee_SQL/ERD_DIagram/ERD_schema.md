#  Exported from QuickDBD: https://www.quickdatabasediagrams.com/
#  Link to schema: https://app.quickdatabasediagrams.com/#/d/HTFxWG
#  NOTE! If you have used non-SQL datatypes in your design, you will have to change these here.
#  Modify this code to update the DB schema diagram.
#  To reset the sample schema, replace everything with
#  two dots ('..' - without quotes).

"employees"
--
"emp_np" int PK FK >- salaries.emp_no
"emp_title_id" VARCHAR FK >- titles.title_ID
"birth_date" VARCHAR
"first_name" VARCHAR
"last_name" VARCHAR
"sex" VARCHAR
"hire_date" VARCHAR

"titles"
--
"title_ID" VARCHAR
"title" VARCHAR

"salaries"
--
"emp_no" int PK FK 
"salary" int

"departments"
--
"dept_no" VARCHAR
"dept_name" VARCHAR

"dep_manager"
--
"dept_no" VARCHAR PK FK >- departments.dept_no
"emp_no" int PK FK >- employees.emp_np

"dep_emp"
--
"emp_no" int PK FK >- employees.emp_np
"dept_no" FK >- departments.dept_no

