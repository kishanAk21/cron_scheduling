# Linux Cron job instructions

1. Open cron tab from linux terminal using command: crontab -e

2. Write following command:
0 0 * * THU path_to_python_executible\python.exe file_path\python_script.py

3. Once done, press the ESC key to exit the insert mode, immediately followed by :wq and ENTER keys.
 This will save the crontab files, and you’ll be back in the Terminal window instantly.
 
 
 Above instructions would run the python script on every thursday @ 00:00:00 hour and update your csv output.
