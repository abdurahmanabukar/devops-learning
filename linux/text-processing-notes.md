5 useful commands I learned
1. grep
Searches for text patterns inside files.
Useful for finding errors, keywords, usernames, or log entries.

Example:  
grep "error" /var/log/syslog

2. awk
Extracts and processes specific columns from text.
Useful for analysing logs, user lists, and process output.

Example:  
ps aux | awk '{print $1, $11}'  
Shows the user + command for each process.

3. sed
Edits text streams (replace, delete, print).
Useful for automation and modifying config files.

Example:  
sed 's/old/new/g' file.txt  
Replaces all “old” with “new”.

4. wc -l
Counts lines in a file or output.
Useful for counting errors, users, or log entries.

Example:  
grep -i "failed" /var/log/auth.log | wc -l  
Counts failed login attempts.

5. sort | uniq
Sorts text and removes duplicates.
Useful for summarising logs or finding unique entries.

Example:  
cat /var/log/syslog | grep "error" | sort | uniq
