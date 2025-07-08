# 📚 Online Book Store (Django)

A web-based application for browsing, managing, and downloading books. Built with Django, Bootstrap, and supports login/logout, admin controls, PDF download, and user reviews.

---

## 🚀 Features

- ✅ User authentication (Login/Register/Logout)
- ✅ Admin-only CRUD operations (Add, Edit, Delete books)
- ✅ Book listing with search and pagination
- ✅ Book ratings and user reviews
- ✅ PDF upload, download, and view in browser
- ✅ Image upload for each book
- ✅ Responsive design using Bootstrap 5

---

## 🛠 Tech Stack

- **Backend:** Django 4.x
- **Frontend:** HTML5, CSS3, Bootstrap 5
- **Database:** SQLite (default) or MySQL (optional)
- **Others:** Django Authentication, Pagination, File Handling

---

## 🧩 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/online-book-store.git
cd online-book-store

### 2. Create virtual environment

python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate (Windows)

### 3. Install dependencies

pip install -r requirements.txt

### 4. Apply migrations

python manage.py migrate

### 5. Create superuser

python manage.py createsuperuser 

### 6. Run development server

python manage.py runserver
