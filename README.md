# School Management System

A simple Python-based School Management System using MySQL to manage:
- Student Admissions
- Student Academic Records
- Fee Details

## Features

- Add, view, search, update, and delete student admission records
- Manage student academic data (class, section, subjects)
- Deposit and track fee details month-wise
- Text-based menu-driven interface
- MySQL-based persistent storage

## Project Structure

```
Python_Project~SchoolManagementSystem/
├── main.py                       # Main launcher
├── TABLES and Records/
│   └── initialize_db.py          # Create DB & pre-load data
├── Modules/
│   ├── admission.py
│   ├── fee_details.py
│   └── student_data.py
```

## How to Run

1. Make sure MySQL is installed and running.
2. Run the DB initializer:

```bash
python "TABLES and Records/initialize_db.py"
```

3. Launch the main program:

```bash
python main.py
```

## Requirements

- Python 3.x
- MySQL (XAMPP/WAMP or standalone)
- MySQL connector for Python:

```bash
pip install mysql-connector-python
```

## Author

**Praveen Kumar**  
[GitHub](https://github.com/pkrcode) | [LinkedIn](https://linkedin.com/in/praveenk-dev)
