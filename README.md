# Pewlett Hackard Analysis.

## Project Overview 

The company, Pewlett Hackard, is wanting to know which of their employees will start retiring within the year. The Pewlett Hackard analyisis will be using the program, PostgreSQL. In the following analysis, Pewlett Hackard will know:
  - The number of retiring employees per title.
  - the employees that are eligible to participate in a mentorship program.

## Resources used for analysis:
- Data sources: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv.

## Pewlett Hackard Analysis Results:

Utilizing the data sources provided for the analysis, I was able to join the data and then create tables for them. The visual below is the code I used in order to obtain the employee number, first name, last name, title, from date, and to date of their time at the comany into the retirement titles table. 



<img width="380" alt="image" src="https://user-images.githubusercontent.com/107371010/193962374-cf01ec6d-896b-4377-9284-53f6c27926e3.png">


After creating the retirement titles table, the next step was to create the unique titles table. This table will show Pewlett Hackard the employee that still currently working for the company, and exclude those that do not. 
