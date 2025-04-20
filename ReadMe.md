# HaatKhola Advanced Multivendor Ecommerce Website

This project is an advanced multivendor e-commerce website built using **Django** and **React**. It allows multiple vendors to list and sell their products, while customers can browse, search, and purchase items. The website provides a fully functional platform for both customers and vendors, including user authentication, order management, and vendor management features.

## Project Features

- **Multivendor Support**: Vendors can register, manage their stores, and list products for sale.
- **User Authentication**: Users can register, log in, and manage their profiles.
- **Product Search and Filters**: Customers can search for products and filter based on various criteria.
- **Shopping Cart and Checkout**: Customers can add products to their cart and proceed to checkout.
- **Order Management**: Both customers and vendors can view order history and manage orders.
- **Admin Panel**: The admin panel allows administrators to manage users, vendors, and orders.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Django (Python)
- **Database**: SQLite (default, can be configured to use PostgreSQL or MySQL)
- **Authentication**: JWT (JSON Web Tokens) for secure user authentication
- **Deployment**: Docker (for containerization)

## Installation

Follow these steps to set up the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/mehedii1515/Advanced_Multivendor_Ecommerce_Website.git
cd Advanced_Multivendor_Ecommerce_Website
```
---

## 1️⃣ Set Up the Backend (Django)

### ✅ Install Backend Dependencies

```bash
cd backend
pip install -r requirements.txt
```

### ⚙️ Configure the Database

Make sure your database settings are configured in `backend/settings.py`.  
By default, it uses **SQLite**, but you can switch to **PostgreSQL** or **MySQL**.

### 🔁 Apply Migrations

```bash
python manage.py migrate
```

### 👤 Create a Superuser (Admin)

```bash
python manage.py createsuperuser
```

Follow the prompts to create an admin account.  
Access the admin panel at: [http://localhost:8000/admin](http://localhost:8000/admin)

---

## 2️⃣ Set Up the Frontend (React)

### 📥 Install Frontend Dependencies

```bash
cd frontend
npm install
```

### 🚀 Start the React Development Server

```bash
npm start
```

The React frontend will run at: [http://localhost:3000](http://localhost:3000)

---

## 3️⃣ Run the Backend Server

```bash
cd backend
python manage.py runserver
```

This will start the Django backend server at: [http://localhost:8000](http://localhost:8000)

---

## 🧑‍💻 Usage

### 🔐 Admins  
Manage users, products, vendors via: [http://localhost:8000/admin](http://localhost:8000/admin)

### 🛍️ Customers  
Browse products, add to cart, and place orders from the React frontend.

### 🏪 Vendors  
Register and manage stores, products, and view orders.

---


---

## 🤝 Contributing

1. Fork the repository  
2. Create your feature branch  
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes  
   ```bash
   git commit -am 'Add new feature'
   ```
4. Push to your branch  
   ```bash
   git push origin feature/your-feature
   ```
5. Create a Pull Request

---
