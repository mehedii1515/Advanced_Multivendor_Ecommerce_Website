# 🛒 HaatKhola Advanced Multi-Vendor E-commerce Website

This project is a full-featured, scalable multi-vendor e-commerce platform built using **Django** for the backend and **React** for the frontend. It enables multiple vendors to manage their own stores while providing customers with a seamless shopping experience. The application incorporates role-based access control, secure authentication, and a rich set of e-commerce functionalities.

Live Link: https://haatkhola.netlify.app/
---

## 🚀 Features

### 🧑‍💼 User Roles

- **Super Admin**: Oversees the entire platform, manages users, vendors, and site-wide settings.
- **Vendor**: Manages their own store, including product listings, orders, and store details.
- **Customer**: Browses products, places orders, and manages personal profiles.

### 🛍️ E-commerce Functionalities

- **Product Management**: Vendors can add, edit, and delete products with images and descriptions.
- **Shopping Cart**: Customers can add products to their cart and proceed to checkout.
- **Order Processing**: Order placement, tracking, and management for both vendors and customers.
- **Payment Integration**: Secure payment processing using integrated payment gateways.
- **Product Reviews and Ratings**: Customers can leave feedback on products.
- **Search and Filtering**: Advanced search options to find products easily.

### 🔐 Security and Access Control

- **Authentication**: Secure login and registration for all user roles.
- **Authorization**: Role-based access control to restrict functionalities based on user roles.
- **Data Validation**: Server-side validation to ensure data integrity.

---

## 🛠️ Technologies Used

### Frontend

- React
- Redux
- React Router
- Axios
- Bootstrap

### Backend

- Django
- Django REST Framework
- PostgreSQL
- JWT Authentication

### Others

- Docker
- Nginx
- Gunicorn
- Celery
- Redis

---

## 📦 Installation

### Prerequisites

- Python 3.8+
- Node.js 14+
- PostgreSQL
- Docker and Docker Compose (optional, for containerization)

### Backend Setup

1. Clone the repository:

```bash
git clone https://github.com/mehedii1515/Advanced_Multivendor_Ecommerce_Website.git
cd Advanced_Multivendor_Ecommerce_Website/backend
```

2. Create a virtual environment and activate it:

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Configure the `.env` file with your environment variables.

5. Apply migrations:

```bash
python manage.py migrate
```

6. Create a superuser:

```bash
python manage.py createsuperuser
```

7. Run the development server:

```bash
python manage.py runserver
```

### Frontend Setup

1. Navigate to the frontend directory:

```bash
cd ../frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

---


## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---
