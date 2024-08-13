# Scenario
As a system administrator, you need to get specific information about employees, their machines, and the departments they’re in. Your team needs this data to perform various tasks, such as running updates, posting a privacy notice in certain departments, and sending an alert to an employee with an issue on a machine.

[Project reference](https://www.coursera.org/learn/linux-and-sql/home/welcome)

# List all organization machines
Get a list of all organization machines and their operating systems.

![image](https://github.com/user-attachments/assets/03fad05f-6d60-416e-8732-2056e3ea5a22)

# Retrieve a list of the machines with OS 2
Obtain a list of all machines with the `OS 2` operating system because these machines need an update.

![image](https://github.com/user-attachments/assets/b6baba53-e7c8-4a46-8aed-150b4c96b20e)

# List employees in the Finance and Sales departments
Retrieve a list of all the employees in the `Finance` and `Sales` departments to obtain their office numbers. A notice about handling confidential financial information will be posted to these offices.

1. I filtered the rows returned from `department` column in the `employees` table to include only employees from the `Finance` department.

![image](https://github.com/user-attachments/assets/a57d10e8-dbc8-4c9b-a1ea-8d08ec14d298)

The employee id of the first employee is `1003`

2. I Modified the previous query so that it returns employees who are in the 'Sales'` department.

![image](https://github.com/user-attachments/assets/1a530431-c009-4a28-98e4-b36e7018fee5)

# Identify employee machines using the South office
Your team recently discovered that there are issues with machines in the South building. In this task, you need to obtain certain employee and computer information. A machine in `'South-109'` has an issue. You need to determine which employee uses that computer so you can send them an alert.

1. I identified which employee uses the office in `'South-109'`.

![image](https://github.com/user-attachments/assets/2dbbbbe2-2158-40b5-8ec0-6c81255e00d1)

user id:1010, username:jlansky

2. Your team has determined that there is an issue with all the machines in the South building. Offices in the organization are named with the building name, a hyphen, and the office number in that building (for example, `'South-109'`). Modify the query you used in the previous step so that it returns information on all the employees in the `'South'` building.

![image](https://github.com/user-attachments/assets/1670662c-2fa2-4b55-bc68-f83a4dc2c0eb)

The first employee listed in the South building belong to the `Finance` department.
