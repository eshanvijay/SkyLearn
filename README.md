![Group 23](https://github.com/user-attachments/assets/4e84251a-27b0-462b-bd5e-fb0bcadc4694)

# 🚀 SkyLearn: The Future of Learning Management Systems  
### The world’s most lightweight, beautifully designed, and feature-packed open-source LMS.

---

> **SkyLearn** is a powerful, full-featured Learning Management System built with the Django web framework. Whether you're a developer looking to enhance your portfolio or an institution searching for a reliable LMS solution — **SkyLearn** is designed for both learning and real-world deployment.

Our mission is to build the **most intuitive, lightweight, and modern LMS** out there — and we can’t do it without your support.  
**If you find this project helpful, please consider giving it a ⭐️ on GitHub.**



---

![SkyLearn UI Screenshot](https://github.com/user-attachments/assets/08644f49-6ae0-4695-86cc-afe331c6f61a)

---

## 🎯 Why SkyLearn?

- Clean and user-friendly interface  
- Lightweight but powerful feature set  
- Easy to contribute to — ideal for open-source beginners  
- Built with Django — robust, scalable, and secure  
- Ideal for colleges, schools, and educational startups  

---

## ✅ Current Features

### 🔐 Admin Panel
- View school-wide analytics and demographics
- Add, update, or delete students and lecturers
- Manage sessions/semesters
- Control course uploads (videos, docs)

### 🎓 Student Portal
- Add or drop courses
- View assessment and grade reports
- Download registration slip and results as PDFs

### 👨‍🏫 Lecturer Dashboard
- Submit scores (attendance, midterm, final exam, assignments)
- Automated grade calculations (total, average, GPA, etc.)
- Pass/Fail/Warn comments

### 🧠 Quiz & Assessments
- Store results per user
- Randomized question order
- Resume incomplete quizzes
- Attempt limits and pass marks
- MCQ, True/False (Essay coming soon!)
- Category-wise performance tracking
- Custom messages based on results
- Admin marking panel for essay-type questions

---

## 📦 Installation Guide

### Requirements
- [Python 3.8+](https://www.python.org/downloads/)

### Steps

```bash
# 1. Clone the repo
git clone https://github.com/SkyCascade/SkyLearn.git

# 2. Navigate into the directory
cd SkyLearn

# 3. Create and activate virtual environment (venv)
python -m venv env
source env/bin/activate  # For Windows: env\Scripts\activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Create a `.env` file in the root folder and customize it
cp .env.example .env  # On Windows: manually create .env and paste contents

# 6. Apply database migrations
python manage.py migrate

# 7. Create a superuser (admin access)
python manage.py createsuperuser

# 8. Start the server
python manage.py runserver
