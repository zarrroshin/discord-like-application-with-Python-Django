discord-like-application-with-Python-Django Inspired by the [Traversy Media Django Crash Course](https://www.youtube.com/watch?v=UmljXZIypDc). --- ## 🚀 Features - 👤 User authentication (Register, Login, Logout) - 🧑‍💻 Developer profiles - 🗂️ Add, update, and delete projects - 💬 Message system between users - 🖼️ Upload profile pictures and project images - 🧩 Django admin panel for full control --- ## 🏗️ Tech Stack | Component | Technology | |------------|-------------| | **Backend** | Django 4+ | | **Frontend** | HTML, CSS, JavaScript | | **Database** | SQLite3 | | **Authentication** | Django built-in Auth System | | **Media Handling** | Django Media & Static Files | --- ## ⚙️ Installation ### 1️⃣ Clone the repository
bash
git clone https://github.com/zarrroshin/discord-like-application-with-Python-Django.git
cd studybud
2️⃣ Create and activate a virtual environment
bash
Copy code
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
3️⃣ Install dependencies
bash
Copy code
pip install -r requirements.txt
4️⃣ Apply migrations
bash
Copy code
python manage.py migrate
5️⃣ Run the development server
bash
Copy code
python manage.py runserver
6️⃣ Open your browser and visit:
cpp
Copy code
http://127.0.0.1:8000/
🧠 Learning Goals
This project helped me strengthen my understanding of:

Django Models, Views, Templates (MVT)

Django ORM and Querysets

CRUD operations

Authentication and Authorization

Static and Media file management

HTML Template Inheritance

📈 Future Improvements

📨 Add notifications and messaging

🌗 Implement Dark/Light theme toggle

☁️ Deploy to Render / Railway / Vercel

👩‍💻 Author
Zahra Roshani
📧 zahraroshani973@gmail.com
🌐 GitHub
💼 LinkedIn