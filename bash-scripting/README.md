#  Bash Scripting

This folder contains my Bash scripting assignments completed as part of my **DevOps learning journey**.

The challenges helped me develop practical skills in Bash scripting, Linux automation, file management, permissions, and basic error handling.

---

##  Challenges Completed

| Challenge | Description | Status |
|---|---|---|
| Challenge 1 | Basic Arithmetic Calculator | ✅ Completed |
| Challenge 2 | File Operations Script | ✅ Completed |
| Challenge 3 | File Checker with Permissions | ✅ Completed |
| Challenge 4 | Backup Script for Text Files | ✅ Completed |

---

#  Skills Practised

Throughout these challenges, I practised:

-  Variables and user input
-  Arithmetic operations
-  `if`, `elif`, and `else` statements
-  File and directory operations
-  File permissions
-  File existence and permission checks
-  Reading file contents
-  Copying and backing up files
-  Working with timestamps
-  Basic error handling
-  Bash scripting and automation

---

# Challenge 1 — Basic Arithmetic Calculator

###  Objective

Create a Bash script that takes two numbers from the user and performs basic arithmetic operations.

### What my script does

- Prompts the user for two numbers
- Performs addition
- Performs subtraction
- Performs multiplication
- Performs division
- Handles division by zero
- Displays the results

### Skills Practised

- Variables
- `read`
- Arithmetic expansion `$(( ))`
- Conditional statements
- Basic error handling

###  Screenshots

- `challenge1-script.png`
- `challenge1-output.png`

---

# Challenge 2 — File Operations Script

###  Objective

Create a Bash script that automates directory and file creation.

### What my script does

- Creates a directory called `bash_demo`
- Navigates into the directory
- Creates a file called `demo.txt`
- Writes the current date into the file
- Displays the contents of the file

### Skills Practised

- `mkdir`
- `cd`
- `echo`
- `>`
- `cat`
- `date`

###  Screenshots

- `challenge2-script.png`
- `challenge2-output.png`

---

# Challenge 3 — File Checker with Permissions

###  Objective

Create a Bash script that checks whether a file exists and displays its permissions.

### What my script does

- Prompts the user for a filename
- Checks whether the file exists
- Checks if the file is readable
- Checks if the file is writable
- Checks if the file is executable
- Displays the appropriate messages

### Skills Practised

- `read`
- `if` / `else`
- `-e`
- `-r`
- `-w`
- `-x`
- File permission checks

###  Screenshots

- `challenge3-script.png`
- `challenge3-output.png`

---

# Challenge 4 — Backup Script

### Objective

Create a Bash script that backs up all `.txt` files from a source directory into a timestamped backup folder.

### What my script does

- Prompts the user for a source directory
- Creates a timestamped backup folder
- Finds `.txt` files using `*.txt`
- Copies the files into the backup folder
- Counts the files backed up
- Displays the backup results

### Skills Practised

- `mkdir`
- `cp`
- Wildcards (`*.txt`)
- `date`
- `ls`
- `wc`
- Variables
- File automation

### 📸 Screenshots

- `challenge4-script.png`
- `challenge4-output.png`

---

# Screenshots

Screenshots documenting my completed challenges are stored in the:

`screenshots/`

folder.

Each challenge includes screenshots showing both the **Bash script** and its **terminal output**.

---

# 🚀 Learning Outcome

Completing these challenges has helped me build a stronger understanding of Bash scripting and how Linux commands can be combined to automate repetitive tasks.

I'm continuing to build on these skills as part of my **DevOps learning journey**, with a focus on Linux, automation, Git, and other DevOps tools.
