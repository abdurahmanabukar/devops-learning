# Text Processing Notes

## 5 Useful Commands I Learned

### grep

Searches for text patterns inside files. Useful for finding errors, keywords, usernames, or log entries.

**Example:**

```bash
grep "error" /var/log/syslog
```

---

### awk

Extracts specific columns from text. Useful for analysing logs, user lists, and process output.

**Example:**

```bash
ps aux | awk '{print $1, $11}'
```

Displays the user and command for each running process.

---

### sed

Edits text by replacing, deleting, or printing text. Useful for automation and modifying configuration files.

**Example:**

```bash
sed 's/old/new/g' file.txt
```

Replaces every occurrence of **"old"** with **"new"**.

---

### wc -l

Counts the number of lines in a file or command output. Useful for counting errors, users, or log entries.

**Example:**

```bash
grep -i "failed" /var/log/auth.log | wc -l
```

Counts the number of failed login attempts.

---

### sort | uniq

Sorts text and removes duplicate entries. Useful for organising data and finding unique values.

**Example:**

```bash
cat /var/log/syslog | grep "error" | sort | uniq
```

---

## Challenge

**Task:** List all users with `/bin/bash` as their shell.

**Command:**

```bash
awk -F: '$7=="/bin/bash" {print $1}' /etc/passwd
```

This command displays all users who use **Bash** as their login shell.
