# 👟 Shoes Store

A php-based e-commerce web application for selling footwear online. It enables customers to browse, search, and purchase shoes while allowing store admins to manage products and orders.

## 📌 Features

### For Customers
- Browse shoe catalog with images, prices, and descriptions
- Search and filter by name, category, or price
- View detailed product pages
- Add to cart, update quantity, remove items
- Secure checkout process
- User registration and login

### For Admins
- Add, update, and delete products
- Manage product categories
- View and manage customer orders

---

## 🛠 Tech Stack
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap, JavaScript
- **Database:** SQLite (default)
- **Authentication:** Django's built-in auth system

---

## 🚀 Getting Started

### 1️⃣ Clone Repository
```bash
git clone https://github.com/shubham14102005/shoes_store.git
cd shoes_store
2️⃣ Create Virtual Environment
python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run Migrations
python manage.py makemigrations
python manage.py migrate
5️⃣ Create Superuser
python manage.py createsuperuser
6️⃣ Start Development Server
python manage.py runserver
Visit http://127.0.0.1:8000/ in your browser.

📂 Project Structure
shoes_store/
│
├── core/                  # Main application logic
├── templates/             # HTML templates
├── static/                # CSS, JS, images
├── db.sqlite3              # Database file
├── manage.py               # Django management script
└── README.md
