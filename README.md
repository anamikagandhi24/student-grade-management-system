# Student Grade Management System

A Python-based command-line application for storing and managing student academic records.

The application allows users to add student details, calculate grades from marks, view stored records, search for individual students, and remove records when required. Student information is maintained locally using a CSV file.

## Features

* Add a new student record
* Store student ID, name, marks, and calculated grade
* Automatically assign a letter grade based on marks
* Display all registered students
* Search for a student using their ID
* Delete an existing student record
* Calculate basic class performance statistics
* Validate student input and marks
* Store records locally in a CSV file

## Technology Used

* **Language:** Python
* **Data Storage:** CSV
* **Interface:** Command Line Interface (CLI)
* **Libraries:** Python standard library

No external Python packages are required.

## Grading Criteria

|  Marks | Grade |
| -----: | :---: |
| 90–100 |   A+  |
|  80–89 |   A   |
|  70–79 |   B   |
|  60–69 |   C   |
|  50–59 |   D   |
|   0–49 |   F   |

## Project Structure

```text
student-grade-management-system/
│
├── main.py
├── students_data.csv
├── statement.md
└── README.md
```

### `main.py`

Contains the application logic, user interaction, grade calculation, validation, and record management.

### `students_data.csv`

Stores student records locally.

### `statement.md`

Contains the project requirements/problem statement.

## Requirements

Make sure Python is installed on your system.

Check the installed version:

```bash
python --version
```

Python 3.7 or later is recommended.

## Running the Application

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/student-grade-management-system.git
```

Move into the project directory:

```bash
cd student-grade-management-system
```

Run the application:

```bash
python main.py
```

On systems where `python` is mapped differently, you can use:

```bash
python3 main.py
```

## How It Works

When the application starts, it presents a menu through which the user can manage student records.

The general workflow is:

```text
Start Application
       │
       ▼
Display Menu
       │
       ├── Add Student
       │
       ├── View Students
       │
       ├── Search Student
       │
       ├── Delete Student
       │
       └── Exit
```

When a student's marks are entered, the application determines the corresponding letter grade and stores the resulting record in the CSV data file.

## Data Validation

The application checks user input before storing a record.

Examples include:

* Student ID cannot be empty.
* Student IDs should not be duplicated.
* Student names cannot be blank.
* Marks must be numeric.
* Marks must fall between 0 and 100.

## Example Record

A stored record follows this structure:

```text
Student ID, Name, Marks, Grade
STU101, Student Name, 92, A+
```

## Future Improvements

Possible extensions to the project include:

* Database integration using MySQL or PostgreSQL
* A graphical user interface
* Student and administrator login
* Exporting performance reports
* Subject-wise marks
* GPA/CGPA calculation
* REST API integration
* Unit testing
* Web-based dashboard

## Author

**Anamika Gandhi**

Computer Science & Engineering
