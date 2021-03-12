# SQL Challenge

## Overview

In this project, I designed tables to hold data in CSVs, imported CSVs into a SQL database, and answered questions about the data. Data is about employees of a corportation who during the 1980s and 1990s. This was done in three steps:

1. Data Modeling

2. Data Engineering

3. Data Analysis

### 1. Data Modeling

The first portion of this analysis included a review the CSVs and sketching out an Entity Relationship Diagram (ERD). 

![ERD_diagram.png](ERD_diagram.png)

### 2. Data Engineering

* The information from the ERD was used  to create a table schema for each of the six CSV files by specifying data types and identifying primary keys, foreign keys, and other constraints.

* Once the table was created each CSV file was imported into the corresponding SQL table.

### 3. Data Analysis

Once the database was complete, the following was conducted:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

## Additional Employee Evaluation

The following steps were conducted to generate a visualization and additional analysis of the data:

1. Imported the SQL database into Pandas

2. Create a histogram to visualize the most common salary ranges for employees.

![salaries.png](../Additional Evaluation/images/salaries.png)

3. Create a bar chart of average salary by title.

![../Additional Evaluation/images/title_salary.png](title_salary.png)

4. Search for data for ID number 499942

![../Additional Evaluation/images/id.png](id.png)




