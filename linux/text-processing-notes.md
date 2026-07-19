Text Processing Notes
cat
Shows the full content of a file.
Example:  
cat /etc/passwd

head
Shows the first lines of a file.
Example:  
head -n 20 /etc/services

less
Opens a file in a scrollable viewer so you can move up and down.
Example:  
less /var/log/syslog

tail
Shows the last lines of a file.
Example:  
tail /var/log/auth.log

tail -f
Shows the last lines and keeps updating live as new log entries appear.
Example:  
tail -f /var/log/auth.log

What I Learned
I learned how to view and inspect files in Linux using different text‑processing commands. These commands help me read full files, check the beginning or end of files, scroll through logs, and monitor live updates. They are important for understanding system activity and debugging issues.
