# Process Management Notes

## 5 Useful Commands I Learned

### 1. ps aux

Shows all running processes on the system, including the PID, CPU usage, memory usage, and the command being run.

**Example:**

```bash
ps aux
```

---

### 2. jobs

Displays all background jobs running in the current terminal session.

**Example:**

```bash
jobs
```

---

### 3. sleep 100 &

Starts a background process that runs for 100 seconds. Useful for practising process management commands.

**Example:**

```bash
sleep 100 &
```

---

### 4. fg %1

Brings the first background job back to the foreground.

**Example:**

```bash
fg %1
```

---

### 5. kill

Stops a running process using its Process ID (PID).

**Example:**

```bash
kill 1234
```

---

## What I Learned

I learned how to view running processes, manage background jobs, bring jobs to the foreground, and stop processes using the `kill` command.
