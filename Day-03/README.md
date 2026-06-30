# Day 2 - Linux File and Directory Management

## Objective
Learn basic Linux commands used to manage files and directories.

---

## Commands Learned

### 1. cp
**Definition:**
Copies files or directories from one location to another.

**Syntax**
```bash
cp source destination
```

**Example**
```bash
cp file1.txt backup/
```

**Real-Time Use**
- Backup configuration files
- Copy project files
- Duplicate important documents

---

### 2. mv
**Definition:**
Moves or renames files and directories.

**Syntax**
```bash
mv source destination
```

**Example**
```bash
mv file1.txt backup/
```

**Rename Example**
```bash
mv file1.txt linux.txt
```

**Real-Time Use**
- Move log files
- Rename deployment scripts
- Organize project files

---

### 3. rm
**Definition:**
Removes files permanently.

**Syntax**
```bash
rm filename
```

**Example**
```bash
rm notes.txt
```

**Real-Time Use**
- Delete temporary files
- Remove old logs
- Clean project files

---

### 4. rmdir
**Definition:**
Removes an empty directory.

**Syntax**
```bash
rmdir directory_name
```

**Example**
```bash
rmdir test
```

**Real-Time Use**
- Delete empty folders
- Clean unused directories

---

### 5. cat
**Definition:**
Displays, creates, and combines text files.

**Syntax**
```bash
cat filename
```

**Example**
```bash
cat linux.txt
```

**Real-Time Use**
- View configuration files
- Read log files
- Display shell scripts

---

## Concepts Learned

### Directory
A directory is a folder used to store files and other directories.

### Relative Path
A path based on the current working directory.

Example:

```bash
cp file1.txt backup/
```

### Absolute Path
A complete path starting from the root directory.

Example:

```bash
cp file1.txt /home/manikanta/Desktop/backup/
```

---

## Commands Practiced

```bash
mkdir mani
cd mani

touch file1.txt file2.txt

cp file1.txt file3.txt

mkdir backup

cp file1.txt backup/

mv file1.txt linux.txt

mv linux.txt backup/

rm file2.txt

rmdir test

cat linux.txt
```

---

## What I Learned Today

- File management using Linux
- Directory management
- Copying files
- Moving and renaming files
- Deleting files and directories
- Viewing file contents
- Relative and absolute paths

---

## Status

✅ Day 2 Completed Successfully
