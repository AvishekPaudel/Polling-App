# Django Polls Application

A simple and interactive polling web application built with Django. Users can view recent polls, vote on choices, and see real-time voting results.

This project was created while learning Django fundamentals including:

* Models
* Views
* Templates
* URL routing
* Forms and POST requests
* Generic class-based views
* Database queries
* Testing

---

# 🚀 Features

* View latest published questions
* Vote on poll choices
* Display voting results dynamically
* Prevent duplicate form submissions using redirects
* Use Django generic views for cleaner architecture
* Model testing using Django TestCase
* SQLite database integration

---

# 🛠️ Technologies Used

* Python 3
* Django 6
* SQLite3
* HTML5
* Django Template Language (DTL)

---

# 📂 Project Structure

```bash
polls/
│
├── migrations/
├── templates/
│   └── polls/
│       ├── index.html
│       ├── detail.html
│       └── results.html
│
├── admin.py
├── apps.py
├── models.py
├── tests.py
├── urls.py
└── views.py
```

---

# ⚙️ Installation Guide

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

## 2. Navigate into the Project Directory

```bash
cd your-repository-name
```

## 3. Create a Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

# 📦 Install Dependencies

```bash
pip install django
```

Or if you have a requirements file:

```bash
pip install -r requirements.txt
```

---

# 🗄️ Apply Database Migrations

```bash
python manage.py migrate
```

---

# 👤 Create Superuser

```bash
python manage.py createsuperuser
```

Follow the prompts to create your admin account.

---

# ▶️ Run the Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

```bash
http://127.0.0.1:8000/polls/
```

---

# 🧪 Running Tests

Run Django tests using:

```bash
python manage.py test
```

This project includes model tests for validating question publication logic.

---

# 📸 Application Flow

1. User visits the polls homepage
2. Latest questions are displayed
3. User selects a question
4. User votes for a choice
5. Vote count is updated
6. Results page displays updated vote counts

---

# 🧠 Key Django Concepts Practiced

## Models

Used Django ORM to create:

* Question model
* Choice model

## Views

Implemented both:

* Function-based views
* Generic class-based views

## Templates

Used Django Template Language for:

* Loops
* Variables
* URL template tags
* Conditional rendering

## Forms

Handled form submission securely using:

```html
{% csrf_token %}
```

## Testing

Created unit tests using Django TestCase.

---

# 🌱 Future Improvements

Potential upgrades for the project:

* User authentication
* AJAX voting without page reload
* Poll expiration dates
* Charts and analytics
* REST API integration
* Tailwind CSS styling
* Search and filtering
* Docker deployment

---

# 📄 License

This project is for educational and learning purposes.

---

# 👨‍💻 Author

Avishek Paudel

GitHub: [https://github.com/AvishekPaudel](https://github.com/AvishekPaudel)
