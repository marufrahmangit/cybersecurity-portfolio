# Scenario
As a system administrator, you have to determine which employee devices must be updated. You also need to investigate user login activity to explore if any unusual activity has occurred.

The information you need is located in the `machines` and `login_attempts` tables in the organization database.

[Project reference](https://www.coursera.org/learn/linux-and-sql/home/welcome)

# Retrieve employee device data
I need to obtain information on employee devices because my team needs to update them. The information I need is in the `machines` table in the organization database.

![image](https://github.com/user-attachments/assets/b1614d51-5307-4073-a67a-3e422fb5a53c)

Next, I want to focus on the email client running on various devices.

![image](https://github.com/user-attachments/assets/d24d81fd-b009-4eb4-bc6f-687b0edfebf0)

Next, I need information on the operating systems used on various devices and their last patch date.

![image](https://github.com/user-attachments/assets/6fb841ef-bd5f-40cb-901c-3041a786a3a5)

# Examine login activity
I need to analyze the information from the `log_in_attempts` table to determine if any unusual activity has occurred.

First, I need to investigate the locations where login attempts were made to ensure that they’re in expected areas (the United States, Canada, or Mexico).

![image](https://github.com/user-attachments/assets/81a50705-eab2-4626-87a2-0a8e7dfc7439)

Next, check if there were any login attempts made from Australia.

![image](https://github.com/user-attachments/assets/75706589-cbaf-48b1-a938-f19f38a4926c)

No attempts were made from Australia as shown by the empty set returned. Next, check if login attempts were made outside of the organization's working hours.

![image](https://github.com/user-attachments/assets/18826873-1bb2-4570-b5f9-3ed24c68d64d)

I need to get a complete picture of all login attempts.

![image](https://github.com/user-attachments/assets/7cc4a2a2-77b8-4039-bf8b-03edbf6eb4e7)

# Order login attempts data
I need to sequence the data that my query returns according to the login date and time.

![image](https://github.com/user-attachments/assets/a0a21a52-b177-4940-9206-6a1750ca740b)

# Retrieve employee device data
Retrieve login attempts after the date `'2022-05-09'`

![image](https://github.com/user-attachments/assets/6d82656b-881e-49db-b76a-28ed44d21fb7)

Next, retrieve data for login attempts that were made on or after `'2022-05-09'`

![image](https://github.com/user-attachments/assets/6dbd482d-d93b-429f-b3dd-3c908e977fd8)

# Retrieve employee device data
I need to narrow the focus of the search. Login attempts made after `2022-05-11` shouldn't be included. I need to return results between `'2022-05-09'` and `'2022-05-11'`.

![image](https://github.com/user-attachments/assets/25823552-ef44-4dc9-b126-1b17a7e3256e)

# Investigate logins at certain times
First, your organization's typical work hours begin at 07:00:00. 
I need to retrieve all login attempts made before `07:00:00` to learn more about the users who are logging in outside of typical hours.

![image](https://github.com/user-attachments/assets/ab5bf369-2bd2-4280-b91f-0c92f5106aa7)

The username of the fifth record is `eraab`.

The query in the previous step returned more results than required. I need to return logins between '06:00:00' and '07:00:00'.

![image](https://github.com/user-attachments/assets/3ad40dfe-0bd0-427c-b379-4fd1e1a857bc)

The earliest login time between the time range is `06:01:31`.

# Investigate logins by event ID
I need to investigate login attempts based on event ID numbers. With this query, you want to return only the `event_id`, `username`, and `login_date` fields from the `log_in_attempts` table.

I need to return the login attempts with `event_id` greater than or equal to `100`.

![image](https://github.com/user-attachments/assets/863efad3-a203-439d-95e7-3e3879e8edda)

The login date of the third result is `2022-05-09`.

Next, I need to modify the query to return only login attempts with `event_id` between `100` and `150`.

![image](https://github.com/user-attachments/assets/e9984bc5-880b-4dc4-8a10-3484ad9eebb0)

The username of the seventh result is `tmitchel`.
