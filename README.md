# 🚗 MotoCar Rentals – Vehicle Hub

A **Django-based Car & Bike Rental System** that allows users to browse, rent, and manage vehicles online.  
This project includes vehicle listings, location-based filtering, cart & checkout system, and a user-friendly interface for managing rentals.

---

## 📌 Features
- 🔑 **User Authentication** – Register, Login & Manage Profile  
- 🚘 **Vehicle Management** – Browse cars & bikes available for rent  
- 🌍 **Location Filtering** – Search vehicles by state & city  
- 🛒 **Cart & Checkout** – Add vehicles to cart and confirm booking  
- 📅 **Booking System** – Manage rental duration & pricing  
- 📩 **Contact Form** – Users can send queries/feedback  
- 🛠️ **Admin Panel** – Manage users, vehicles, and bookings  

---

## 🛠️ Tech Stack
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap (Django Templates)
- **Database:** SQLite (default, can switch to PostgreSQL/MySQL)
- **Other:** Django ORM, Signals, Migrations

---

## 📂 Project Structure
```
│── MotoCar/
│   │── App/                # Main Django App
│   │   │── models.py       # Database Models (Car, Bike, Cart, Rentals)
│   │   │── views.py        # Business Logic
│   │   │── urls.py         # App Routes
│   │   │── admin.py        # Django Admin Config
│   │   │── signals.py      # Signal Handling
│   │   │── templates/      # HTML Templates (bikes, cars, checkout, etc.)
│   │   │── migrations/     # Database Migrations
│   │── manage.py           # Django Management Script
│── db.sqlite3              # SQLite Database
│── requirements.txt        # Dependencies
│── README.md               # Project Documentation
```
---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
git clone https://github.com/omkarmore003/MotoCar-Rentals-Project-vehicle-hub.git
cd MotoCar-Rentals-Project-vehicle-hub

### 2️⃣ Create & Activate Virtual Environment
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

### 3️⃣ Install Dependencies
pip install -r requirements.txt

### 4️⃣ Run Migrations
python manage.py migrate

### 5️⃣ Create Superuser (Admin Access)
python manage.py createsuperuser

### 6️⃣ Run Development Server
python manage.py runserver

Visit 👉 http://127.0.0.1:8000/

---

## 👨‍💻 Contributing
Pull requests are welcome! For major changes, please open an issue first  
to discuss what you would like to change.

---

## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## ✨ Author
- **Your Name** – https://github.com/omkarmore003
