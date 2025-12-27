
#  STUDENT PROGRESS TRACKER SYSTEM

## 📌 Project Title
Student Progress Tracker System

## 📄 Project Type
Mini Project (Console-Based Application)

## 🧑‍🎓 Student Details
- **Name:** K. Shanmukha Rao  
- **Branch:** CSE – CSC  
- **Roll Number:** 25B25A4621  

## 📘 Project Description
The **Student Progress Tracker System** is a Python-based console application designed to calculate and display a student’s academic performance.  
The program collects student details, subject-wise marks, computes total marks, average, grade, and result (PASS/FAIL), and generates a structured progress report.

It also provides menu options to:
- Re-enter marks
- View the last saved report
- Save the report to a text file
- Exit the application
- 
## 🎯 Objectives
- To calculate student academic performance
- To generate a formatted progress report
- To practice Python basics such as loops, conditions, lists, and file handling
- To build a menu-driven real-time application

  
## 🛠️ Technologies Used
- **Programming Language:** Python 3
- **Interface:** Console / Terminal
- **Concepts Used:**
  - Input / Output
  - Conditional Statements
  - Loops
  - Lists
  - File Handling
  - Menu-driven logic

## ⚙️ Features
- Accepts student personal details
- Accepts subject-wise marks dynamically
- Calculates:
  - Total Marks
  - Average Marks
  - Grade
  - Result (PASS / FAIL)
- Displays formatted progress report
- Stores last report in memory
- Saves report to a `.txt` file
- Continuous execution using menu options

## 📊 Grading Logic
| Average Marks | Grade |
|--------------|-------|
| ≥ 90         | A     |
| ≥ 75         | B     |
| ≥ 50         | C     |
| ≥ 35         | D     |
| < 35         | Fail  |

**Result Rule:**  
If any subject mark is less than 35 → Result = FAIL  
Otherwise → Result = PASS

## ▶️ How to Run the Program
1. Install Python 3
2. Open terminal or command prompt
3. Run the program using:
   ```bash
   python student_progress_tracker.py
