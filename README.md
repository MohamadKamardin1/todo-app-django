📝 Django To-Do App
This is a simple To-Do List web app built with Django. It allows users to add, view, update, and delete tasks. The frontend is handled using Django's template system (HTML).

🚀 Features
Add new tasks

Mark tasks as completed

Edit/update task titles

Delete tasks

Responsive interface using Django Templates

🛠️ Technologies Used
Python

Django

HTML (Django Templates)

SQLite (default database)

📦 Installation
Clone the project

git clone git@github.com:MohamadKamardin1/django-todo-app.git
cd django-todo-app
Create virtual environment (optional but recommended)


python -m venv venv
source venv/Scripts/activate  # On Windows
# or
source venv/bin/activate      # On Linux/Mac
Install dependencies


pip install -r requirements.txt
Run migrations


python manage.py migrate
Start the development server


python manage.py runserver
Open the app in your browser
Visit: http://127.0.0.1:8000

📁 Project Structure

django-todo-app/
├── todo/               # Main app
│   ├── templates/      # HTML templates
│   └── views.py        # App views
├── db.sqlite3          # Database
├── manage.py           # Django management script
└── requirements.txt    # Python packages
🙋‍♂️ Author
Mohamad Kamardin (a.k.a. Sultan)
📧 Email: focusinzanzibar@outlook.com
🌍 Location: Zanzibar
💼 Freelance Tour Guide & Developer

🧠 Want to contribute?
You're welcome! Feel free to fork this repo and submit a pull request 🚀
