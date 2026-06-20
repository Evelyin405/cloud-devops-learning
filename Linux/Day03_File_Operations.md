# Linux Day 3

# File Operations Commands

Today I learned three important Linux commands:

1. cp
2. mv
3. rm

These commands are used to manage files and folders in Linux.

---

## 1. cp

Purpose:
Copies a file or folder from one location to another.

Syntax:

cp source destination

Example:

cp file1.txt file2.txt

Explanation:

- file1.txt is the original file.
- file2.txt is the new copied file.
- The original file remains unchanged.
- A duplicate copy is created.

Before:

file1.txt

After:

file1.txt
file2.txt

Use Case:

Used when we need a backup copy of a file without affecting the original file.

---

## 2. mv

Purpose:
Moves a file/folder to another location or renames it.

Syntax:

mv source destination

Example 1 (Rename a file):

mv file1.txt notes.txt

Explanation:

- The file name changes from file1.txt to notes.txt.
- No duplicate file is created.

Before:

file1.txt

After:

notes.txt

Example 2 (Move a file to another folder):

mv notes.txt Backup/

Explanation:

- The file is moved into the Backup folder.
- It no longer exists in the previous location.

Use Case:

Used for organizing files and renaming files.

---

## 3. rm

Purpose:
Deletes a file.

Syntax:

rm filename

Example:

rm file1.txt

Explanation:

- Permanently removes the file.
- The file is not sent to the Recycle Bin.

Before:

file1.txt

After:

(No file)

Warning:

Be careful while using rm because deleted files cannot be easily recovered.

Use Case:

Used to remove unwanted files.

---

# Practice Session

Create a folder:

mkdir Day3Practice

Move into the folder:

cd Day3Practice

Create files:

touch file1.txt
touch file2.txt

View files:

ls

Copy a file:

cp file1.txt copy.txt

View files:

ls

Rename a file:

mv copy.txt notes.txt

View files:

ls

Create a folder:

mkdir Backup

Move file into folder:

mv notes.txt Backup/

Check files:

ls
ls Backup

Delete a file:

rm file2.txt

View files:

ls

---

# Summary

cp  -> Copy files

mv  -> Move or rename files

rm  -> Delete files

Difference Between cp and mv:

cp:
Creates a duplicate copy while keeping the original file.

mv:
Moves or renames the file without creating a duplicate copy.

---

# Commands Learned So Far

Day 1:
pwd
ls
mkdir
cd
touch
lsb_release -a

Day 2:
cat
echo
history
clear
man

Day 3:
cp
mv
rm