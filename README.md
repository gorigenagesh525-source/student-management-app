# Student Management & CGPA Dashboard

A Python-based Student Management System built using **Streamlit** and **SQLite**.

## Features

- Add Students
- View Student Details
- Update Student Details
- Delete Students
- Add Subject Marks
-Calculate CGPA
- Display Student Results
- Search Students
- SQLite Database
- Simple and User-Friendly Dashboard

## Technologies Used

- Python
- Streamlit
- SQLite
- Pandas

## Project Structure

```text
Student-Management-CGPA-Dashboard/
│
├── app.py
├── database.py
├── cgpa_cal.py
├── requirements.txt
├── students.db
├── .gitignore
└── README.md
```

## Installation

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the Project Folder

```bash
cd Student-Management-CGPA-Dashboard
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
streamlit run app.py
```

The application will open in your web browser.

## Requirements

Create a `requirements.txt` file with:

```text
streamlit
pandas
```

> SQLite is included with Python, so it normally does not need to be installed separately.

## How It Works

1. Open the Streamlit application.
2. Add student information.
3. Enter subject marks.
4. The system calculates the CGPA.
5. Student information and results are stored in SQLite.
6. View and manage student records from the dashboard.

## CGPA Calculation

The system calculates CGPA based on the student's subject grades/marks according to the calculation method implemented in the project.

## Database

The project uses **SQLite** to store student information and academic records.

The database is lightweight and does not require a separate database server.

## How to Use

### Add Student

Enter the student's:

* Name
* Roll Number
* Other required details

Then click **Add Student**.

### Calculate CGPA

Enter the marks for the required subjects. The application processes the marks and displays the calculated CGPA.

### Manage Students

You can view, update, search, and delete student records from the dashboard.

## Future Improvements

* Student login system
* Admin login
* Export results to Excel/PDF
* Grade-wise reports
* Attendance management
* Student performance charts
* Cloud database integration

## Author

**GORIGE NAGESH**

BCA (Honours)
SRKDC, Nandyal

## License

This project is created for **educational purposes**.
