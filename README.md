# sql-challenge

Background

For this project, we designed the tables to hold the data from the 6 CSV files, imported the CSV files into a SQL database, and then answered questions about the data. We performed data modeling, data engineering, and data analysis, respectively.


Data Modeling
We inspected the CSV files, and then sketched an Entity Relationship Diagram of the tables. To create the sketch, we used QuickDBD

Data Engineering
Using the provided information we created a table schema for each of the six CSV files.
We specified the data types, primary keys, foreign keys, and other constraints. We created the tables in the correct order to handle the foreign keys

For the primary keys, we verified that the column is unique. Otherwise, created a composite key which takes two primary keys to uniquely identify a row.

Then imported each CSV file into its corresponding SQL table.


Data Analysis
We were asked to list the employee number, last name, first name, sex, and salary of each employee.

We were asked to list the first name, last name, and hire date for the employees who were hired in 1986.

We were asked to list the manager of each department along with their department number, department name, employee number, last name, and first name.

We were asked to list the department number for each employee along with that employee’s employee number, last name, first name, and department name.

We were asked to list first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

We were asked to list each employee in the Sales department, including their employee number, last name, and first name.

We were asked to list each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

We were asked to list the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

 