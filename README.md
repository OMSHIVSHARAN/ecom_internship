# 🛒 E-Commerce Internship Project

A **Django-based E-Commerce Web Application** built as part of an internship project.  
This project includes product management, user authentication, shopping cart, and payment gateway integration.

---

## 📌 Features

- **User Registration & Login** (with OTP email verification)
- **Product Categories & Search**
- **Add to Cart & Checkout**
- **Razorpay Payment Gateway**
- **Order Management**
- **Admin Panel** for managing:
  - Products
  - Categories
  - Orders
  - Users

---

## 🛠 Tech Stack

- **Backend:** Django, Python
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite (default, can be changed to PostgreSQL/MySQL)
- **Payment Integration:** Razorpay
- **Version Control:** Git & GitHub

---

## 📂 Project Structure






ecom_internship/
│
├── ecom/ # Main application
├── static/ # Static files (CSS, JS, Images)
├── templates/ # HTML templates
├── media/ # Uploaded media files
├── manage.py # Django management script
└── requirements.txt # Python dependencies



---

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/OMSHIVSHARAN/ecom_internship.git
   cd ecom_internship
Create and activate virtual environment


python -m venv venv
venv\Scripts\activate  # On Windows
source venv/bin/activate  # On Mac/Linux
Install dependencies


pip install -r requirements.txt
Run migrations


python manage.py makemigrations
python manage.py migrate
Create superuser


python manage.py createsuperuser
Run the development server


python manage.py runserver
Open the app in your browser:


📜 License
This project is open-source and available under the MIT License.

💡 Author
OM ShivSharan

