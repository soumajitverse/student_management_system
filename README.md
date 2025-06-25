# 🏫 Django Student Management System

A **Student Management System** built using **Python Django** for educational purposes. It provides role-based access for Admin (HOD), Faculty (Teachers), and Students with a user-friendly interface.

> ✅ Built while learning Django to understand real-world use cases like authentication, CRUD operations, and role-based dashboards.

---

## 🚀 Features

### 👨‍💼 Admin (HOD)
- Dashboard with summary charts
- Manage Faculty (Add, Update, Delete)
- Manage Students (Add, Update, Delete)
- Manage Courses and Subjects
- Manage Academic Sessions
- View Attendance Records
- Review & respond to Feedback
- Approve/Reject Leave Applications

### 👨‍🏫 Faculty (Teachers)
- View personalized dashboard
- Take & update student attendance
- Add/Update results
- Apply for leave
- Send feedback to Admin

### 👨‍🎓 Students
- View attendance and result
- Apply for leave
- Send feedback to Admin
- View subject details and academic sessions

---

## 🛠 Tech Stack
- Python 3.x
- Django 3.x+
- HTML, CSS, Bootstrap
- SQLite (default DB)
- Chart.js (for dashboard visuals)

---

## 💻 Getting Started

### ✅ Prerequisites
- Python installed: [https://python.org](https://python.org)
- Git installed: [https://git-scm.com](https://git-scm.com)

### 🔧 Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/your-username/django-student-management-system.git
cd django-student-management-system

# 2. Create virtual environment
python -m venv venv

# 3. Activate virtual environment
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run migrations
python manage.py makemigrations
python manage.py migrate

# 6. Create superuser
python manage.py createsuperuser

# 7. Start the server
python manage.py runserver
