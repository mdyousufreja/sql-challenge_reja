# sql-challenge_reja


# Background # 

It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.

## Files ##

Downloaded the following files to get started:

Module 9 Challenge [files](https://courses.bootcampspot.com/courses/3819/assignments/56681?module_item_id=999676)


## Instructions ##

This Challenge is divided into three parts: data modeling, data engineering, and data analysis.


## Data Modeling ##

Inspected the CSV files, and then sketched an Entity Relationship Diagram (ER) of the tables. Created the sketch using a tool like QuickDBD [links](https://www.quickdatabasediagrams.com/)

## Data Engineering ##

1. Used the provided information to create a table schema for each of the six CSV files. Be sure to do the following:

   - Specified the data types, primary keys, foreign keys, and other constraints.

   - For the primary keys, verified that the column is unique. Otherwise, created a composite keyLinks to an               external site., which takes two primary keys to uniquely identify a row.

   - Created the tables in the correct order to handle the foreign keys.

2. Imported each CSV file into its corresponding SQL table.

## Data Analysis ##

1. Listed the employee number, last name, first name, sex, and salary of each employee.

2. List the first name, last name, and hire date for the employees who were hired in 1986.

3. Listed the manager of each department along with their department number, department name, employee number, last name, and first name.

4. Listed the department number for each employee along with that employee’s employee number, last name, first name, and department name.

5. Listed first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

6. Listed each employee in the Sales department, including their employee number, last name, and first name.

7. Listed each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. Listed the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

