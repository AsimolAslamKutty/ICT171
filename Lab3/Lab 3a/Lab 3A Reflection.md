# Lab 3A Reflection 

- In this lab, I connected my AWS Apache web server to a DuckDNS domain.

- I used DuckDNS because it is easier to open the website using a domain name instead of remembering the AWS public IP address.

- I checked the domain using `nslookup` and `dig` to make sure it was pointing to my AWS public IP.

- I also checked the AWS security group and made sure the needed ports were allowed, especially 80 for HTTP and 443 for HTTPS.

- After the domain was working, I used Certbot to install a Let's Encrypt certificate for my website.

- I tested the website in the browser and confirmed that HTTPS was working.

- I also checked the certificate details to make sure it was issued to my DuckDNS domain.

- One thing I noticed is that the AWS public IP can change after restarting the instance, so the DuckDNS record must match the current IP.

- This lab helped me understand how a domain name, DNS, Apache, and HTTPS are connected in a real web server setup.