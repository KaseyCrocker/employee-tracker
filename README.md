# Employee Tracker

## Description
The employee tracker application is designed to manage a database of employees, roles, and departments for the company that uses it. The user will be able to add, and view all departments, roles, and employees.

## User Story
```
AS A business owner, I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business
```

## Acceptance Criteria
```
GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database
```

## Built With:
  * Node.js
  * Node MySQL2
  * Inquirer.js
  * Console.table
  * Chalk
  * Dotenv
  
## Installation
  1. To install this application, ``` git clone ``` this repository, or download the .zip file and extract all of the files.
  2. Ensure Node.js is installed on your system.
  3. Install all of the dependencies in the package.json file by typing ``` npm install ``` in the terminal.
  
## Usage
Esnure that you are in the root directory in the command terminal in order to initialize the application.
In the command terminal, enter the following command to start the application.
``` npm start ```

## Walkthrough video
[Employee-Tracker-Walkthrough.webm](https://user-images.githubusercontent.com/106774932/199377170-b35f415a-f292-4cc4-9812-2a3413599181.webm)

## Questions
If you have any questions, please contact me at kasey_crocker@yahoo.com
