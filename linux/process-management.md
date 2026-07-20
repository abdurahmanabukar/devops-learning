5 useful commands I learned
1. ps aux
Shows all running processes on the system with details like PID, CPU usage, memory, and command.
Useful for finding what’s running and identifying processes to kill.

Example:  
ps aux

2. jobs
Shows background jobs running in the current terminal session.
Useful for tracking tasks you started with &.

Example:  
jobs

3. sleep 100 &
Starts a background process that sleeps for 100 seconds.
Useful for testing fg/bg and kill commands.

Example:  
sleep 100 &

4. fg %1
Brings a background job back to the foreground.
Useful when you want to interact with or stop a job.

Example:  
fg %1

5. kill
Terminates a process using its PID.
Useful for stopping stuck or long-running processes.

Example:  
kill 1234
