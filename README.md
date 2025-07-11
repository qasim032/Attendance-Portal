# Attendance-Portal (24BSAI)
![image](https://github.com/user-attachments/assets/947caac6-7f11-42a9-b3e5-e763c95a8162)


A basic C++ console app to record attendance for 56 students  
(24BSAI001 to 24BSAI056) and save it to a text file.

---

## Features

- Input subject name and date  
- Mark students as present (`p`) or absent (`a`)  
- Saves attendance to `attendance.txt`  
- Shows total present/absent count with roll numbers  

---

## How to Use

1. Run the program  
2. Enter subject and date  
3. For each roll number:  
   - Press `p` if present  
   - Press `a` if absent  
4. Attendance will be saved in `attendance.txt`  

---

## Requirements

- C++ compiler  
- Windows OS (uses `_getch()` from `<conio.h>`)  

---

## File Output Example

Attendance of 24BSAI
Subject: [Subject]
DATE: [Date]

Present Count: X
Roll numbers of students present: ...

Absent Count: Y
Roll numbers of students absent: ...
