# Lab 2B1 Reflection

- This lab helped me understand how cloud hosting is different from using a local VM. With AWS EC2, the server has a public IP address, so the web page can be opened from a browser like a real hosted website.

- I learnt that the security group is important because it controls what can access the server. Port 22 was needed for SSH, and port 80 was needed for the Apache web page.

- After connecting through SSH, I installed Apache and tested the default page first. Then I edited the `index.html` file and added my own simple content.

- I also used `wget` to download a PDF file and copied it into `/var/www/html/`. This showed me that Apache serves files from the web root folder.

- I noticed that some commands needed `sudo`, especially when editing or copying files into the Apache folder. This helped me understand that file permissions are important on a server.

- I also learnt that cloud servers can create charges if they are left running, so stopping the EC2 instance after the lab is important.