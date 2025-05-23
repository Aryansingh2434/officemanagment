# officemanagment
# Office Employee Management System

This is a Django-based web application designed to manage employee records and departmental information within an office environment. It allows HR or admins to perform tasks such as adding employees, managing departments, updating information, and viewing filtered data.

## 🔧 Features

- Add, update, and delete employee records
- Manage departments
- Filter and search employee data
- Simple and intuitive user interface
- Built using Django and Bootstrap

## 🛠️ Technologies Used

- Python
- Django (Backend Framework)
- SQLite (Default database)
- HTML, CSS, Bootstrap (Frontend)

## 🚀 Getting Started

Follow these steps to run the project locally:

### Prerequisites

- Python 3.x installed
- `pip` installed

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Aryansingh2434/officemanagment.git
cd officemanagment/ofc-emp-management-system/ofc-emp-management-system-main/office_emp_proj

    Create and activate a virtual environment

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

    Install the dependencies:

pip install -r requirements.txt

    Run migrations:

python manage.py migrate

    Start the development server:

python manage.py runserver

    Visit the application in your browser:

http://127.0.0.1:8000/

📁 Project Structure

office_emp_proj/
├── employee/             # Django app for employee operations
├── office_emp_proj/      # Project settings
├── templates/            # HTML templates
├── static/               # Static files (CSS, JS, images)
├── db.sqlite3            # Default SQLite database
└── manage.py             # Django management script
