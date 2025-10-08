# Bandit — level1 → level2
**File:** `level1-to-level2.md`

---

## 🎯 Objective
The password for the next level is stored in a file called - located in the home directory.

---

* `bash`
ssh bandit1@bandit.labs.overthewire.org -p 2220 <br/><br/>
* Press enter. <br/><br/>
* Then Enter the `PASSWORD` :- `ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If` (Which we got in level0-to-level1). <br/><br/>
* As shown below:-

<img width="900" height="780" alt="image" src="https://github.com/user-attachments/assets/61896aaf-1af9-4f06-80ca-2d4aee4fc82f" /> <br/>

---
---

<br/>

* use `ls` command to know the files in folder or directory.<br/><br/>
* Command = ls <br/><br/>
* Than we will get a file called  `-`  . <br/><br/>
* Use `cat` and `./` to run the `-` file. <br/><br/>
* `Command` = `cat ./-` We will get the Password for next level.<br/><br/>
* **note :-** `cat` command is used to Display The File Contents. <br/>
            `./`  command is used to RUN the BASH files.
* As shown below:-

  <img width="433" height="95" alt="image" src="https://github.com/user-attachments/assets/055ca284-da4c-4ffd-bb08-d66734bd0d08" />

---
---

<br/>
<br/>

## Note the password in notepad or notes with level1 - 263JGJPfgU6LtdEvgfWU1XP5yac29mFx

## 💻 Commands Used:- `ls`,`cat`,`./`.
## 🚀 Key Learnings:- How to login to bandit1 using ssh and Using basic commands.


