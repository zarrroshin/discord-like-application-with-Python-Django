# 💬 Discord-like Application with Python & Django

Inspired by the [Traversy Media Django Crash Course](https://www.youtube.com/watch?v=UmljXZIypDc).  
A full-stack web app built using **Django** that allows users to join discussion rooms, chat in real-time (conceptually), and manage profiles — similar to Discord.

---

## 🚀 Features

- 👤 User Authentication (Register, Login, Logout)  
- 💬 Create, edit, and delete chat rooms  
- 🗨️ Post and delete messages  
- 🧑‍💻 Developer profiles with bio and avatar  
- 🖼️ Upload profile and room images  
- 🧩 Admin panel for full control  

---

## 🏗️ Tech Stack

| Component       | Technology                     |
|-----------------|--------------------------------|
| **Backend**     | Django 4+                      |
| **Frontend**    | HTML, CSS, JavaScript          |
| **Database**    | SQLite3                         |
| **Authentication** | Django built-in Auth System  |
| **Media Handling** | Django Media & Static Files   |

---

## ⚙️ Installation



```bash
1️⃣ Clone the repository
git clone https://github.com/zarrroshin/discord-like-application-with-Python-Django.git
cd discord-like-application-with-Python-Django

2️⃣ Create and activate a virtual environment
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Apply migrations
python manage.py migrate

5️⃣ Run the development server
python manage.py runserver

6️⃣ Open your browser and visit:
http://127.0.0.1:8000/

---

## 🧠 Learning Goals

This project helped me strengthen my understanding of:

Django Models, Views, and Templates (MVT)

Django ORM and Querysets

CRUD operations

Authentication and Authorization

Static and Media file management

HTML Template Inheritance

---

