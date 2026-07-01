# Day 3 - Linux File Viewing and Text Editing

## Objective
Learn how to view, create, edit, and analyze text files using Linux commands.

---

# Commands Learned

## 1. pwd

### Definition
Displays the current working directory.

### Syntax

```bash
pwd
```

### Example

```bash
pwd
```

### Real-Time Use
- Check the current directory before running commands.
- Verify the working location while managing projects.

---

## 2. echo

### Definition
Displays text on the terminal or writes text into a file.

### Syntax

```bash
echo "text"
```

### Examples

```bash
echo "Hello Linux"

echo "Learning Linux" > notes.txt

echo "Learning Docker" >> notes.txt
```

### Important

`>`  → Overwrites the file.

`>>` → Appends new content to the existing file.

### Real-Time Use

- Create configuration files.
- Add environment variables.
- Write log messages.
- Test shell scripts.

---

## 3. nano

### Definition
A simple text editor used to create and edit files.

### Syntax

```bash
nano filename
```

### Example

```bash
nano notes.txt
```

### Save File

Ctrl + O

Press Enter

### Exit

Ctrl + X

### Real-Time Use

- Edit configuration files.
- Modify shell scripts.
- Update YAML files.

---

## 4. head

### Definition
Displays the first 10 lines of a file.

### Syntax

```bash
head filename
```

### Example

```bash
head notes.txt
```

### Real-Time Use

Quickly check the beginning of log or configuration files.

---

## 5. tail

### Definition
Displays the last 10 lines of a file.

### Syntax

```bash
tail filename
```

### Example

```bash
tail notes.txt
```

### Real-Time Use

Monitor application log files.

```bash
tail -f application.log
```

---

## 6. less

### Definition
Displays a file page by page.

### Syntax

```bash
less filename
```

### Real-Time Use

Read very large files without opening them in an editor.

---

## 7. wc

### Definition
Counts lines, words, and characters in a file.

### Syntax

```bash
wc filename
```

### Example

```bash
wc notes.txt
```

### Useful Options

```bash
wc -l notes.txt
```

Counts lines.

```bash
wc -w notes.txt
```

Counts words.

---

# Concepts Learned

## Overwrite

`>` replaces the existing content of a file.

Example

```bash
echo "Linux" > notes.txt
```

---

## Append

`>>` adds new content without removing existing content.

Example

```bash
echo "Docker" >> notes.txt
```

---

## What I Practiced

```bash
pwd

echo "Learning Linux" > notes.txt

echo "Learning Docker" >> notes.txt

cat notes.txt

nano notes.txt

head notes.txt

tail notes.txt

less notes.txt

wc notes.txt
```

---

# What I Learned Today

- Check current working directory.
- Create files using echo.
- Edit files using nano.
- View file content.
- Read the first and last lines of a file.
- Read large files page by page.
- Count lines, words, and characters.
- Difference between > and >>.

---

# Status

✅ Day 3 Completed Successfully

🚀 DevOps Journey Continues...
