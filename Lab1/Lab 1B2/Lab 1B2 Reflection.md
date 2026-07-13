# Lab 1B2 Reflection 

- This lab helped me understand how Linux controls file access using users, groups, and permissions. Creating Alice, Bob, and Mallory made it easier to see how different users can have different access to the same folder.

- I learnt that groups are useful because permissions can be given to a group instead of setting access for every user one by one. In this lab, Alice and Bob were added to the shared group, while Mallory was not given the same access.

- I understood the meaning of file permissions better after checking the shared folder. The owner had more control, the group had limited access, and other users could be blocked from the folder.

- Testing with `su` and `whoami` was useful because I could confirm which user I was using before testing the folder access. This made the permission results easier to understand.

- The Mallory sudo test showed me that giving sudo access is a big security decision. Once a user has sudo permission, they can access protected areas and make system changes.

- From this lab, I learnt that permissions are important in a multi-user system because they help protect files and stop users from accessing things they should not.