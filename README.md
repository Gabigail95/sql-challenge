# sql-challenge
sql-challenge

# Project Goal
This project will consist of researching an employee database for those employed with the company within the 1980s and 1990s. The files that will be referenced in this project are within the "data" directory, in the form of 6 CSV files. 

# Tools
The needed tools to complete this project are PostgreSQL 16 and QuickDBD. 

# Breakdown

- Data Modeling: An Entity Relationship Diagram is created. Please see ERD image within the EmployeeSQL directory. 
- Data Engineering: Table schema is created for each of the CSV files. Data types, primary and foreign keys are all indicated. CSV files were then imported into the respective tables created. Please see findings within table_schemata.sql
- Data Analysis: The imported data was then analyzed to answer the below questions. Please see findings within "queries.sql"
  List the employee number, last name, first name, sex, and salary of each employee.
  List the first name, last name, and hire date for the employees who were hired in 1986.
  List the manager of each department along with their department number, department name, employee number, last name, and first name.
  List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
  List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
  List each employee in the Sales department, including their employee number, last name, and first name.
  List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
  List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

  Thank you!
