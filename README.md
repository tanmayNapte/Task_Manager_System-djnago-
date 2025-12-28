# Task Management System (Django)

A simple and functional **Task Management System** built using **Django**, focused on core backend concepts like authentication, CRUD operations, and database handling.

This project was built to strengthen backend fundamentals and demonstrate real-world Django workflow.

---

## 🚀 Features

- User authentication (Login / Logout)
- Create, update, and delete tasks
- Task status management
- Secure session-based access
- Clean UI using Django templates & Bootstrap
- Django ORM for database operations

---

## 🛠 Tech Stack

- **Backend:** Python, Django  
- **Database:** SQLite  
- **Frontend:** HTML, CSS, Bootstrap  
- **Tools:** Git, GitHub

---

## 📁 Project Structure

task_management_system/
│── manage.py
│── taskmanager/
│── tasks/
│── templates/
│── static/
│── requirements.txt
│── .gitignore
│── README.md


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

git clone https://github.com/tanmayNapte/Task_Manager_System-djnago-.git
cd Task_Manager_System-djnago-

###2️⃣ Create virtual environment
python -m venv venv
venv\Scripts\activate   # Windows

###3️⃣ Install dependencies
pip install -r requirements.txt

###4️⃣ Run migrations
python manage.py migrate

###5️⃣ Create superuser
python manage.py createsuperuser

###6️⃣ Run server
python manage.py runserver


Open browser:

http://127.0.0.1:8000/

📌 Purpose of the Project

This project was created to:

Understand Django project structure

Practice authentication & authorization

Implement CRUD operations using Django ORM

Gain hands-on experience with backend development

📈 Future Improvements

Task priority levels

Due dates & reminders

REST API using Django REST Framework

Deployment on cloud platform

👤 Author

Tanmay Napte
BCA (Science) Student | Aspiring Python Backend Developer
