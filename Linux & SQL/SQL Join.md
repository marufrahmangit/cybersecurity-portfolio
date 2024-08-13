# Scenario
As a security analyst, you’ll investigate a recent security incident that compromised some machines. You are responsible for getting the required information from the database for the investigation.

[Project reference](https://www.coursera.org/learn/linux-and-sql/home/welcome)

# Match employees to their machines
Identify which employees are using which machines. The data is located in the `machines` and `employees` tables.

![image](https://github.com/user-attachments/assets/28b21cfa-8dfb-4ffb-a51c-906162f47cc6)

# Return more data
Now I must return the information on all machines and the employees who have machines. 

![image](https://github.com/user-attachments/assets/729a8dd0-bccb-4937-abb7-d851e8fc58f0)

The value in the username column for the last record returned is `NULL`.

Next, I did the reverse and retrieve the information of all employees and any machines that are assigned to them.

![image](https://github.com/user-attachments/assets/6bd16f75-7b48-4264-aa53-25c59ad6030b)

The value in the username column for the last record returned is areyes`.

# Retrieve login attempt data
To continue investigating the security incident, I must retrieve the information on all employees who have made login attempts. 

![image](https://github.com/user-attachments/assets/aafd2884-e58d-4409-b0a0-10e43ac73c24)
