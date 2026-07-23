# Permissions Notes

## 5 Useful Commands I Learned

### 1. chmod

Changes file permissions (read, write, and execute). Useful for controlling who can access or run a file.

**Example:**

```bash
chmod +x hello.sh
```

Gives the file execute permission.

---

### 2. chown

Changes the owner and group of a file. Useful for managing file ownership and system security.

**Example:**

```bash
sudo chown root:root hello.sh
```

Makes `root` the owner and group of the file.

---

### 3. ls -l

Displays detailed information about a file, including permissions, owner, group, and size.

**Example:**

```bash
ls -l hello.sh
```

Shows the current permissions and ownership of the file.

---

### 4. touch

Creates a new empty file. Useful for creating files for testing or configuration.

**Example:**

```bash
touch secure.txt
```

Creates an empty file called `secure.txt`.

---

### 5. chmod 644

Sets file permissions so the owner can read and write, while everyone else can only read.

**Example:**

```bash
chmod 644 secure.txt
```

Changes the file permissions to `rw-r--r--`.

---

## What I Learned

I learned how to manage file permissions, change file ownership, and check permissions using Linux commands.
