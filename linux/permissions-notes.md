1. chmod
Changes file permissions (read, write, execute).
Useful for making scripts executable or restricting access.

Example:  
chmod +x hello.sh  
Gives execute permission.

2. chown
Changes the owner and group of a file.
Important for security and admin tasks.

Example:  
sudo chown root:root hello.sh  
Makes root the owner.

3. ls -l
Shows detailed file info including permissions (rwx), owner, group, and size.
Useful for checking permission changes.

Example:  
ls -l hello.sh

4. touch
Creates an empty file.
Useful for testing permissions or creating config files.

Example:  
touch secure.txt

5. chmod 644
Sets permissions so only the owner can read/write, and everyone else can only read.
Useful for secure files.

Example:  
chmod 644 secure.txt
