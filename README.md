# Employee Database Project
Performing data modeling, data engineering, and data analysis on old employee files using SQL

- - -
![ERD](EmployeeSQL/EmployeeDB_ERD.png)
- - -
## Project Structure

### All project files can be found in the [EmployeeSQL](EmployeeSQL/) folder.
**Data Modeling:** [EmployeeDB_ERD.png](EmployeeSQL/EmployeeDB_ERD.png)  
**Data Engineering:** [schema.sql](EmployeeSQL/schema.sql)  
**Data Analysis:** [Requested_Queries.sql](EmployeeSQL/Requested_Queries.sql)  
**Bonus:** [bonus.ipynb](EmployeeSQL/bonus.ipynb)  

### You can find the original CSV files in the [Resources](Resources/) folder.

- - -
## Scenario Background
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.

## Data Modeling

Inspect the CSV files, and then sketch an Entity Relationship Diagram of the tables. 
## Data Engineering

Use the provided information to create a table schema for each of the six CSV files.
## Data Analysis

- List the employee number, last name, first name, sex, and salary of each employee.

- List the first name, last name, and hire date for the employees who were hired in 1986.

- List the manager of each department along with their department number, department name, employee number, last name, and first name.

- List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

- List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

- List each employee in the Sales department, including their employee number, last name, and first name.

- List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

- List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

## Bonus:

(Optional) Create a Jupyter notebook of the analysis.
