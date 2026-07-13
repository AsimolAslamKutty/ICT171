# Lab 3B2 Reflection - MariaDB Additional Server Service

- In this lab, I chose MariaDB as my additional server service because I wanted to try something different from Apache, DNS and HTTPS.

- MariaDB is a database service, so it is used more for storing data instead of showing web pages.

- I installed MariaDB on my AWS Ubuntu server and checked that the service was active and running.

- I also made sure it was enabled, so it can start again when the server restarts.

- After that, I ran the secure installation step to remove some unsafe default settings.

- I tested MariaDB by using `SHOW DATABASES;` first, then I created a small database called `ict171_lab`.

- I also created a `students` table, inserted one record, and displayed it using a SQL query.

- One thing I noticed is that SQL commands must be typed carefully because small mistakes like missing semicolons or quotes can cause errors.

- This lab helped me understand that one server can run different services. For example, Apache can show the website, while MariaDB can be used to store data.
