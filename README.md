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


After creating the retirement titles table, the next step was to create the unique titles table. This table will show Pewlett Hackard the employees that still currently working for the company, and exclude those that do not. As shown below:


<img width="388" alt="image" src="https://user-images.githubusercontent.com/107371010/194138714-ffd043e8-5293-48cd-8c0e-813b8d163852.png">


Next was to figure out the employees that are eligible to participate in a mentorship program. Using the information I used to gather the previous table, I was able to create a code that would be able to determine who was eligible and place that information into the _mentorship_eligibilty.csv_. The code provided below:

<img width="381" alt="image" src="https://user-images.githubusercontent.com/107371010/194139590-17d0b41b-faea-4781-a6ed-83b419e38ad6.png">


## Summary:

With the upcoming "silver tsumani", the amount of roles that would need to be filled according to the analysis are shown in the visual below:

<img width="143" alt="image" src="https://user-images.githubusercontent.com/107371010/194141558-b843c502-8a03-4470-8141-c86a4eb5aa03.png">


There will not be enough retirement-ready employees that will be able to mentor the next generation of Pewlett Hackard employees, the data from the _mentorship_eligibilty.csv_ shows there is not enough employees to mentor the upcoming employees.


