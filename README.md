# 🎓 Student Performance Analysis System

A Python-based Student Performance Analysis System that helps manage student records, search student details, generate rankings, analyse class performance, and export assessment statistics using CSV files.

## 📌 Project Overview

The Student Performance Analysis System is a menu-driven Python application developed to simplify student record management and academic performance analysis.

It uses Python's built-in `csv` module to read, store, update, and analyse student information through a CSV dataset.

The project focuses on basic Python programming concepts such as functions, loops, conditional statements, lists, file handling, exception handling, and sorting.

## ✨ Features

### 1. Show All Students
- Displays all student records.
- Shows registration number, name, batch, section, and total marks.

### 2. Search Student
- Searches for a student using their registration number.
- Displays a detailed student report.
- Shows assessment-wise marks and total marks.

### 3. Student Ranking
- Sorts students according to their total marks.
- Displays students in descending order of marks.
- Assigns ranks to students.

### 4. Class Performance Summary
- Calculates the total number of students.
- Calculates the class average.
- Identifies the highest and lowest scorers.
- Calculates assessment-wise averages and percentages.
- Identifies the strongest and weakest assessment components.

### 5. Add New Student
- Allows users to enter new student details.
- Checks for duplicate registration numbers.
- Validates assessment marks.
- Saves new student records directly into the CSV file.

### 6. Export Analysis
- Generates a separate `component_analysis.csv` file.
- Exports assessment-wise maximum marks, class averages, and average percentages.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Storage:** CSV (Comma-Separated Values)
- **Python Modules:** `csv`, `pathlib`
- **Concepts Used:** Functions, Lists, Loops, Conditional Statements, File Handling, Exception Handling, and Sorting.

## 📂 Project Structure

```text
Student-Performance-Analysis/
│
├── student_performance_analysis_completed.py
├── students.csv
├── component_analysis.csv
└── README.md
```

`component_analysis.csv` is generated when the Export Analysis option is used.

## 🚀 Installation and Execution

### Prerequisites
- Python 3.x installed on your computer.
- A code editor such as VS Code (optional).

### Steps

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**2. Open the project folder**

```bash
cd Student-Performance-Analysis
```

**3. Run the Python program**

```bash
python student_performance_analysis_completed.py
```

**4. Make sure `students.csv` is present in the same folder as the Python file.**

## 🖥️ Application Menu

When the program runs, the following menu appears:

```text
STUDENT PERFORMANCE ANALYSIS SYSTEM

1. Show all students
2. Search student
3. Show ranking
4. Show class summary
5. Add student
6. Export analysis
7. Exit

Enter your choice:
```

Enter the corresponding number to access the desired functionality.

## 📊 Assessment Components

The system analyses the following assessment components:

| Assessment | Maximum Marks |
|---|---:|
| GFG | 6 |
| EL Activities | 2 |
| Project Milestone-1 | 2 |
| Lab | 7.5 |

## 📚 Python Concepts Demonstrated

This project demonstrates the practical application of:

- **Functions:** Dividing the program into smaller, reusable modules.
- **Lists:** Storing and managing student records.
- **Loops:** Iterating through student data and performing calculations.
- **Conditional Statements:** Implementing menu options and validation.
- **File Handling:** Reading and writing CSV files.
- **Exception Handling:** Handling invalid numerical inputs and missing files.
- **Sorting:** Arranging students according to their total marks.
- **Data Analysis:** Calculating averages, percentages, and performance insights.

## 🎯 Project Objective

The main objective of this project is to apply fundamental Python programming concepts to develop a practical student management and academic performance analysis application.

It provides an organized approach to handling student records and understanding class performance through automated calculations.

## 👨‍💻 Author

**Adil Alam**

B.Tech – Computer Science and Engineering  
Bennett University

---

*Developed as an academic Python programming project.*
