# Employee-Tracker-MySQL
My Solution to Week 12 Challenge

Developers are often tasked with creating interfaces,known as Content Management Systems (CMS) that make it easy for non-developers to view and interact with information stored in databases. This is a command-line application to manage a company's employee database, using Node.js, Inquirer and MySQL.

This application makes it easy for a business owner when the owner wants to view and manage the departments, roles, and emplypyees in the company. Also it makes it easier for the owner to organize and plan business according to the changing needs. 

When the owner starts the application, the owner is presented with the following options: 
- view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role

When the owner selects to view all departments, then the owner is presented with a formatted table showing department names and department ids.


When the owner selects to view all roles, then the owner is presented with the job title, role id, the department that role belongs to, and the salary for that role.

When the owner selects to view all employees, then the owner is presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to.

When the owner selects to add a department, then the owner is prompted to enter the name of the department and that department is added to the database.

When the owner selects to add a role, then the owner is prompted to enter the name, salary, and department for the role and that role is added to the database.

When the owner selects to add an employee, then the owner is prompted to enter the employee’s first name, last name, role, and manager and that employee is added to the database.

When the owner selects to update an employee role, then the owner is prompted to select an employee to update and their new role and this information is updated in the database. 

The owner also has the option to remove an employee from the database, if need be. 

#Install
- npm i : to install all file in order for npm to work
- npm i inquirer: to use inquirer to interact with the user via command line
- npm init - to create a json file
- npm i mysql: to connect to MySQL database
- npm console.table - to format tables

#Run
- node index.js

#Design
This application follows the database schema containing three variables: 
! [](images/schema.png)


You can view the demo of the app here: https://drive.google.com/file/d/1qvJRtgRQ0nPC32WzKMjZ-u5SlNfxkvhW/view