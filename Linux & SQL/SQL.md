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
