                    # 🎓 Student Attendance & Performance Tracker

## 📌 Project Information

| Detail | Description |
|---|---|
| Project Title | Student Attendance & Performance Tracker |
| Problem Statement | PS No. 45 |
| Course | Programming Fundamentals Using Python |
| Course Code | RU-100-05-00058 |
| Programme | BCA |
| Semester | First Semester |
| Section | 1C |
| Language | Python |

## 📖 Project Overview

The **Student Attendance & Performance Tracker** is a Python-based application designed to analyze students' attendance and academic performance.

The system reads student information from a CSV file, calculates individual attendance percentages, identifies students who are academically or attendance-wise At Risk, and generates visual reports using bar charts and scatter plots.

It helps in monitoring student performance and identifying students who may require additional academic support.

## ✨ Key Features

- 📂 **CSV File Handling:** Reads student records from CSV files using Pandas.
- 📊 **Attendance Calculation:** Automatically calculates attendance percentages.
- 📚 **Performance Analysis:** Analyzes students' marks out of 100.
- ⚠️ **At Risk Detection:** Identifies students with low attendance or marks.
- 📈 **Bar Chart Visualization:** Displays attendance percentages for all students.
- 🔵 **Scatter Plot Visualization:** Shows the relationship between attendance and marks.
- 🧹 **Data Validation:** Detects invalid or incomplete student records.
- 📋 **Student Reports:** Displays individual attendance, marks, and status.
- 📉 **Performance Summary:** Calculates average attendance and average marks.

## 🚨 At Risk Criteria

A student is classified as **At Risk** if either of the following conditions is satisfied:

| Condition | Requirement |
|---|---|
| Attendance | Below 75% |
| Marks | Below 40 out of 100 |

**Note:** A student satisfying either one or both conditions is classified as At Risk.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python 3 | Main programming language |
| Pandas | CSV handling and data analysis |
| Matplotlib | Graphs and data visualization |
| CSV | Student data storage |

## 📁 Project Structure

```text
Student-Attendance-Performance-Tracker/
│
├── main.py
├── students.csv
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YourUsername/Student-Attendance-Performance-Tracker.git
```

### 2. Navigate to the Project Folder

```bash
cd Student-Attendance-Performance-Tracker
```

### 3. Install Required Libraries

```bash
pip install pandas matplotlib
```

### 4. Run the Project

```bash
python main.py
```

## 📄 CSV File Format

The program accepts student data in CSV format.

Example: `students.csv`

```csv
Name,Classes_Held,Classes_Attended,Marks
Rahul,100,85,78
Aman,100,60,35
Priya,100,90,88
Sneha,100,70,65
Rohit,100,95,92
```

The program also supports CSV files without a header row.

## 🖥️ Main Menu

```text
--- Student Attendance & Performance Tracker ---

1. Report
2. Summary and charts
3. Exit

Enter choice:
```

### Option 1: Student Report

Displays each student's attendance percentage, marks, and risk status.

### Option 2: Summary and Charts

Displays:
- Average attendance percentage.
- Average marks.
- Total number of At Risk students.
- Names of At Risk students.
- Attendance bar chart.
- Attendance vs Marks scatter chart.

### Option 3: Exit

Terminates the application.

## 📊 Data Visualization

The project generates two graphical representations:

**1. Attendance Percentage Bar Chart**
- Displays attendance percentages for each student.
- Red bars represent At Risk students.
- Green bars represent students with OK status.
- A dashed horizontal line represents the 75% attendance requirement.

**2. Attendance vs Marks Scatter Chart**
- Represents attendance percentage on the X-axis.
- Represents marks on the Y-axis.
- Identifies students who are At Risk.
- Displays student names alongside their data points.

## 🧠 Python Concepts Used

- Variables and Constants
- Functions and Modules
- Conditional Statements
- Loops
- Lists and Sets
- Exception Handling
- File Handling
- CSV Data Processing
- Pandas DataFrames
- Boolean Filtering
- Data Visualization
- Mathematical Calculations

## 🚀 Future Improvements

- Add a graphical user interface using Tkinter.
- Integrate an SQLite database.
- Generate downloadable PDF reports.
- Add student search functionality.
- Include monthly attendance analysis.
- Develop interactive performance dashboards.

## 🎯 Learning Outcomes

Through this project, I learned how to:

- Work with CSV files using Python.
- Process and analyze structured datasets.
- Apply conditional logic to identify At Risk students.
- Handle invalid data using exception handling.
- Perform calculations using Pandas.
- Represent data visually using Matplotlib.
- Develop a menu-driven Python application.

## 👨‍💻 Author

**Lakshansh Yadav**

BCA | First Semester | Section 1C

Programming Fundamentals Using Python

---

⭐ If you find this project useful, consider giving this repository a star!

---

---

⭐ *"Every expert was once a beginner. Keep learning, keep building."*

Thanks for visiting my profile!

https://github.com/SATYAPRAKASHSETHY
