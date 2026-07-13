
## What I Learnt

For this lab, I learnt how a backup can be done automatically instead of copying files manually every time.

I first tested the backup script myself, then used cron to run it automatically. I also checked the ZIP files and the log file to make sure the cron job was really working.

One thing I had to be careful with was the file path. When using cron, I realised it is better to use the full path because cron may not run the same way as the normal terminal.

I also tested copying the backup ZIP file using `scp`. This helped me understand how backup files can be moved to another location after they are created.

For a real server, I think the script can be improved by adding error messages, checking whether the backup is successful, and removing very old backups so the storage does not become full.



# Lab 3B1 Reflection

- In this lab, I learnt how to create a backup using a Bash script.

- I first made some sample files and folders in the Documents folder, so I could test whether the backup script was working.

- After that, I wrote a script to copy the files into a backup folder. I also tested it from another folder after moving the script to `/usr/bin`.

- I then changed the script to create a ZIP backup with the date and time in the file name. This made it easier to see when each backup was created.

- I used cron to run the backup script automatically. At first, I tested it using a shorter timing, then I changed it to run hourly.

- I checked the ZIP files and the backup log to make sure the cron job actually worked.

- I also used `scp` to copy the backup ZIP file into another folder. This helped me understand how a backup can be moved to another location.

- From this lab, I understood that backup tasks can be automated instead of doing everything manually. I also realised why scripting and cron jobs are useful for server maintenance.
