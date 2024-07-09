# SQL-Project
Applying filters to SQL queries
# Project Description
This project provides the steps I used to ensure the system is safe and investigate potential issues.
# Retrieve after hours failed login attempts
Failed login attempts needed to be investigated.
![image](https://github.com/NataliaEgan/SQL-Project/assets/173753740/e5997579-a7cb-4a68-84b4-269618491664)
The login_time column in the log_in_attempts table contains the login attempts that were made. I selected all the content of the log_in_attempts table then I used a WHERE clause and used the AND operator to retrieve the failed login attempts that occurred after business hours ('18:00'). The output shows me that there were 19 failed login attempts that occured after 18:00.
# Retrieve login attempts on specific dates
A suspicious event occurred on 2022-05-09, so I retrieved all login attempts that occurred on this day and the day before.
![image](https://github.com/NataliaEgan/SQL-Project/assets/173753740/a9b8eae5-dcae-4894-9577-5b9fd21032f3)
I selected all of the content of the log_in_attempts table and used the clause WHERE with the operator OR resulting in an output of 75 login attempts in those two days.
# Retrieve login attempts outside of Mexico
The logins that did not originate in Mexico need to be investigated.
![image](https://github.com/NataliaEgan/SQL-Project/assets/173753740/e773aeec-37fd-4459-93ed-0932296fdcf2)
First I selected all of the content from the log_in_attempts table and used the clause WHERE NOT and the operator LIKE, which resulted in 144 login attempts made outside of Mexico.
# Retrieve employees in Marketing
Employee machines need to be updated, and so I obtained information about the employees in the Marketing department who are located in the offices of the East building (East-170 or East-320).
![image](https://github.com/NataliaEgan/SQL-Project/assets/173753740/fc36e12c-9432-4d3f-bea2-83e76ad1b4d5)
I retrieved the information of the employees table using the WHERE clause and the AND and LIKE operators.
