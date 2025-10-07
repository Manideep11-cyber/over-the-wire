# Bandit — level0 → level1
**File:** `level0-to-1.md`

---

## 🎯 Objective
Connect to the Bandit server as **bandit0**, read the file that contains the password for **bandit1**, and record that password.  
This is the very first step: learn to use SSH and read files on a remote Linux system.

---

## 🔒 Prerequisites
- A terminal (Linux / macOS) or an SSH-capable client (Windows: PowerShell, PuTTY, or Windows Subsystem for Linux).
- Internet access.
- Username and password for level 0:
  - **Username:** `bandit0`
  - **Password:** `bandit0`
- Bandit server address and port:
  - Host: `bandit.labs.overthewire.org`
  - Port: `2220`

---

## 💻 Commands Used:- ls,cat.


## 🔗 Connect via SSH
Open your terminal and run:

'''bash
ssh bandit0@bandit.labs.overthewire.org -p 2220 
and press enter.
As shown below:-



<img width="808" height="782" alt="image" src="https://github.com/user-attachments/assets/b1559088-237a-4bd5-91ab-54bb06b8da41" />



Enter the **password** : `bandit0`

use 'ls' command to know the files in folder or directory.
**command** = ls
As shown below :- You will get a file called readme.



<img width="262" height="37" alt="image" src="https://github.com/user-attachments/assets/73a4ad90-997e-4078-8a96-21b7c8eaed5d" />



Use 'cat' command to `concatenate files and print on the standard output.`
**command** = cat readme
As shown below :- you will get the password.



<img width="881" height="133" alt="image" src="https://github.com/user-attachments/assets/2808ff86-34af-4a42-9c28-b2ea95e851d7" />



 Password is :- ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

## Note the password in notepad or notes with level0 - ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If


## 🚀 Key Learnings:- How to login to bandit0 using ssh.
                      Using basic commands.
