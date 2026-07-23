# File System Notes

## 5 Useful Commands I Learned

### 1. cd

Changes your current directory. Useful for navigating around the Linux file system.

**Example:**

```bash
cd /var/log
```

Moves to the `/var/log` directory.

---

### 2. ls -lah

Lists files and folders with detailed information, including permissions, owner, size, and hidden files.

**Example:**

```bash
ls -lah
```

Displays all files in the current directory.

---

### 3. mkdir -p

Creates directories, including any parent directories that do not already exist.

**Example:**

```bash
mkdir -p projects/demo
```

Creates the `projects` folder and the `demo` folder inside it.

---

### 4. cp

Copies files or directories from one location to another.

**Example:**

```bash
cp test.txt projects/demo/
```

Copies `test.txt` into the `projects/demo` directory.

---

### 5. tail -f

Displays the last lines of a file and updates the output in real time. Useful for monitoring log files.

**Example:**

```bash
tail -f /var/log/auth.log
```

Shows new log entries as they are added.

---

## What I Learned

I learned how to navigate the Linux file system, create directories, copy files, view directory contents, and monitor log files in real time.
