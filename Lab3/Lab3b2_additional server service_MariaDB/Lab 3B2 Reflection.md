# Lab 3B2 Reflection - MariaDB Additional Server Service

- In this lab, I tried installing MariaDB as an extra server service on my AWS Ubuntu server.

- I chose MariaDB because it is a database service, so it is not the same as the Apache, DNS, or HTTPS tasks I already did.

- First, I checked that MariaDB was installed and running. I also made sure it was enabled so it can start again when the server restarts.

- I then did the secure installation step. This helped remove some default settings that are not safe, like anonymous users and the test database.

- After that, I used `SHOW DATABASES;` to check whether MariaDB was working properly.

- I also created a small database called `ict171_lab`, made a `students` table, inserted one record, and displayed it using a SQL query.

- One thing I noticed is that SQL commands must be typed carefully. Even a small mistake like missing quotes or a semicolon can stop the command from working.

- This lab helped me understand that a server can run different types of services. For example, Apache can be used for the website, while MariaDB can be used to store data.