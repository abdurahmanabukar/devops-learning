# Bandit Solutions

## Bandit Level 0 → Level 1

### Commands Used

```bash
ls
ls -lah
cat readme
```

### What I Learned

I learned how to list files and read the contents of a file.

---

## Bandit Level 1 → Level 2

### Commands Used

```bash
ls
cat ./-
```

### What I Learned

I learned how to open files with special names.

---

## Bandit Level 2 → Level 3

### Commands Used

```bash
ls
cat "spaces in this filename"
```

### What I Learned

I learned how to work with filenames that contain spaces.

---

## Bandit Level 3 → Level 4

### Commands Used

```bash
ls
cd inhere
ls -la
cat ...Hiding-From-You
```

### What I Learned

I learned how to find and read hidden files.

---

## Bandit Level 4 → Level 5

### Commands Used

```bash
ls
cd inhere
ls
file ./*
cat ./-file07
```

### What I Learned

I learned how to identify file types before opening them.

---

## Bandit Level 5 → Level 6

### Commands Used

```bash
ls
cd inhere
find . -type f -size 1033c ! -executable
cat ./maybehere07/.file2
```

### What I Learned

I learned how to search for files using specific properties.

---

## Bandit Level 6 → Level 7

### Commands Used

```bash
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
```

### What I Learned

I learned how to search the system while ignoring permission errors.

---

## Bandit Level 7 → Level 8

### Commands Used

```bash
ls
grep "millionth" data.txt
```

### What I Learned

I learned how to search for text inside a file using `grep`.

---

## Bandit Level 8 → Level 9

### Commands Used

```bash
ls
sort data.txt | uniq -u
```

### What I Learned

I learned how to sort data and find unique values.

---

## Bandit Level 9 → Level 10

### Commands Used

```bash
ls
strings data.txt | grep "="
```

### What I Learned

I learned how to extract readable text from binary files.

---

## Bandit Level 10 → Level 11

### Commands Used

```bash
ls
base64 -d data.txt
```

### What I Learned

I learned how to decode Base64 encoded data.

---

## Bandit Level 11 → Level 12

### Commands Used

```bash
ls
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```

### What I Learned

I learned how to translate characters using the `tr` command.

---

## Bandit Level 12 → Level 13

### Commands Used

```bash
mkdir /tmp/bandit
cp data.txt /tmp/bandit
cd /tmp/bandit
xxd -r data.txt > data
file data
gzip -d data.gz
bzip2 -d data.bz2
tar -xf data.tar
```

### What I Learned

I learned how to extract and decompress different archive formats.

---

## Bandit Level 13 → Level 14

### Commands Used

```bash
ls
ssh -i sshkey.private bandit14@localhost -p 2220
```

### What I Learned

I learned how to log in using an SSH private key.

---

## Bandit Level 14 → Level 15

### Commands Used

```bash
cat /etc/bandit_pass/bandit14
nc localhost 30000
```

### What I Learned

I learned how to connect to a service using Netcat.

---

## Bandit Level 15 → Level 16

### Commands Used

```bash
openssl s_client -connect localhost:30001
```

### What I Learned

I learned how to establish a secure SSL/TLS connection.

---

## Bandit Level 16 → Level 17

### Commands Used

```bash
nmap localhost
openssl s_client -connect localhost:31790
```

### What I Learned

I learned how to scan ports and identify the correct service.

---

## Bandit Level 17 → Level 18

### Commands Used

```bash
diff passwords.old passwords.new
```

### What I Learned

I learned how to compare two files using the `diff` command.

---

## Bandit Level 18 → Level 19

### Commands Used

```bash
ssh bandit18@bandit.labs.overthewire.org -p 2220 "cat readme"
```

### What I Learned

I learned how to execute a command during an SSH connection.

---

## Bandit Level 19 → Level 20

### Commands Used

```bash
ls
./bandit20-do cat /etc/bandit_pass/bandit20
```

### What I Learned

I learned how to run a command with another user's permissions.
