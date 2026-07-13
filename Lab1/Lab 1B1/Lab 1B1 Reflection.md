# Lab 1B1 Reflection 

- This lab helped me understand how Ubuntu can be used as a small server, not only as a normal desktop system. After setting up Apache, I could see how a webpage can be opened using localhost and also through the VM IP address.

- I learnt that firewall rules are important because a service being installed does not mean it can be accessed straight away. The correct port still needs to be allowed, such as port 80 for Apache and port 22 for SSH.

- One part I found a bit confusing was checking the different terminal outputs. Apache status, UFW status, SSH, and nmap all showed different information, so I had to check carefully whether the service was running or whether the port was open.

- SSH helped me understand remote access better because I could log in through the terminal instead of only using the Ubuntu desktop. This made it feel closer to how a real Linux server is managed.

- I also learnt why compression is useful before transferring files. Using `tar` and `bzip2` helped me group files together, and `scp` showed how files can be transferred between systems.

- The user account and privilege part showed me that not every user should have admin access. This is important because giving too much permission can affect the security of the system.