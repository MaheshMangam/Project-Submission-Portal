📂 Project Submission Portal

A web-based platform for students to submit their projects and for admins to review and manage submissions efficiently.

🚀 Features

Student Module
Register/Login
Submit project details & files
View submission history
Admin Module
Review all student submissions
Approve/Reject projects
Manage student accounts
Common
Unified login page (Student & Admin side-by-side)
Secure authentication
Responsive design for mobile & desktop

🛠 Tech Stack

Frontend: HTML, CSS, JavaScript (Bootstrap for styling)
Backend: Python (Django Framework)
Database: SQLite
Version Control: Git & GitHub

📦 Installation & Setup

Clone the repository

git clone https://github.com/yourusername/project-submission-portal.git
cd project-submission-portal

Create & activate a virtual environment

python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate # Mac/Linux

Install dependencies

pip install -r requirements.txt

Run migrations

python manage.py makemigrations
python manage.py migrate

Start the development server

python manage.py runserver

Open in browser: http://127.0.0.1:8000