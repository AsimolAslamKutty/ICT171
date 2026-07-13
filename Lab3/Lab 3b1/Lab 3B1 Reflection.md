# Lab 3B1 Reflection

- In this lab, I learnt how to create a backup using a Bash script.

- I first made some sample files and folders in the Documents folder, so I could test whether the backup script was working.

- After that, I wrote a script to copy the files into a backup folder. I also tested it from another folder after moving the script to `/usr/bin`.

- I then changed the script to create a ZIP backup with the date and time in the file name. This made it easier to see when each backup was created.

- I used cron to run the backup script automatically. At first, I tested it using a shorter timing, then I changed it to run hourly.

- I checked the ZIP files and the backup log to make sure the cron job actually worked.

- I also used `scp` to copy the backup ZIP file into another folder. This helped me understand how a backup can be moved to another location.

- From this lab, I understood that backup tasks can be automated instead of doing everything manually. I also realised why scripting and cron jobs are useful for server maintenance.