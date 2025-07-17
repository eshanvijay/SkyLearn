# 🚀 SkyLearn: The Future of College Management Systems  
*A lightweight, modern, and open-source solution for managing academic institutions.*

---

> A full-featured, role-based college management system built with Django. Designed for both real-world deployment and developer learning, it supports students, lecturers, and administrators with streamlined workflows and modern UI.

---

![UI Screenshot](https://github.com/user-attachments/assets/08644f49-6ae0-4695-86cc-afe331c6f61a)

---

## 🎯 Key Highlights

- ✅ Role-based portals: Students, Lecturers, Admins  
- 🎓 Course enrollment, grade tracking, PDF reports  
- 📊 Admin dashboard with full control and analytics  
- 🧪 Built-in quiz & assessment system  
- 🔐 Secure, scalable, and easily extensible

---

## ✅ Features Overview

### 🔐 Admin Panel
- View college-wide analytics and demographics
- Add, update, or delete students and lecturers
- Manage sessions, semesters, and departments
- Control course uploads (videos, documents)

### 🎓 Student Portal
- Enroll/drop courses
- View assessments, results, and GPA
- Download results and registration slips as PDF

### 👨‍🏫 Lecturer Dashboard
- Submit and manage attendance, scores, and final grades
- Automatic GPA calculations and performance summaries
- Add comments: Pass/Fail/Warn system

### 🧠 Quiz & Assessment Module
- Store quiz results per student
- Randomized question order for fairness
- Support for MCQs and True/False (Essay coming soon!)
- Resume incomplete quizzes
- Set attempt limits and pass marks
- Category-wise performance breakdown
- Admin review panel for essay questions

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite (default), can be switched to PostgreSQL
- **Email:** Configurable SMTP support
- **PDF Generation:** Integrated using report libraries

---

## 📦 Installation Guide

### ✅ Requirements
- Python 3.8+
- pip (Python package installer)
- Virtualenv (optional but recommended)

### 🧰 Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/SkyCascade/SkyLearn.git

# 2. Navigate to the project directory
cd SkyLearn

# 3. Create and activate a virtual environment
python -m venv env
env\Scripts\activate        # On Windows
# source env/bin/activate   # On macOS/Linux

# 4. Install the dependencies
pip install -r requirements.txt

# 5. Create a `.env` file in the root directory
# You can copy from the example provided
# On Windows: manually copy and edit
# On Unix: cp .env.example .env

# 6. Apply database migrations
python manage.py migrate

# 7. Create a superuser (for admin access)
python manage.py createsuperuser

# 8. Start the development server
python manage.py runserver
