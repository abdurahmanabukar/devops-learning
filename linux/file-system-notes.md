# File System Notes

## Commands Practiced

cd

Changes directory (folder).

Example:

```bash
cd /var/log
```

pwd

Shows the current working directory.

Example:

```bash
pwd
```

ls -lah

Lists files and directories with detailed information, including hidden files.

Example:

```bash
ls -lah
```

touch

Creates an empty file.

Example:

```bash
touch test.txt
```

mkdir -p

Creates directories and any parent directories that do not already exist.

Example:

```bash
mkdir -p projects/demo
```

cp

Copies a file from one location to another.

Example:

```bash
cp test.txt projects/demo/
```

mv

Moves or renames a file.

Example:

```bash
mv projects/demo/test.txt projects/demo/backup.txt
```

rm

Deletes a file.

Example:

```bash
rm projects/demo/backup.txt
```

cat

Displays the contents of a file.

Example:

```bash
cat /etc/passwd
```

head

Displays the first lines of a file.

Example:

```bash
head -n 20 /etc/services
```

## What I Learned

In this task, I learned how to navigate the Linux file system and perform basic file operations using the command line. I practiced creating, copying, moving, renaming, and deleting files, as well as viewing file contents. These commands are essential for working efficiently in Linux and form the foundation of many DevOps tools and workflows.
