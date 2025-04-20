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


2. Set up the Backend (Django)
Install backend dependencies
bash
Copy
Edit
cd backend
pip install -r requirements.txt
Configure Database
Make sure to set up the database in the settings.py file in the backend directory. By default, it uses SQLite, but you can configure it to use PostgreSQL or MySQL if necessary.

Apply Migrations
bash
Copy
Edit
python manage.py migrate
Create a Superuser (Admin)
bash
Copy
Edit
python manage.py createsuperuser
Follow the prompts to create an admin user. You can access the admin panel at http://localhost:8000/admin.

3. Set up the Frontend (React)
Install frontend dependencies
bash
Copy
Edit
cd frontend
npm install
Start the React development server
bash
Copy
Edit
npm start
This will start the React development server on http://localhost:3000.

4. Run the Backend Server
bash
Copy
Edit
cd backend
python manage.py runserver
This will start the Django server on http://localhost:8000.

Usage
For Admins: You can access the Django admin panel at http://localhost:8000/admin to manage users, products, and vendors.

For Customers: You can browse products, add them to the cart, and place orders.

For Vendors: Vendors can register and manage their stores and products.



Create your feature branch (git checkout -b feature/your-feature).

Commit your changes (git commit -am 'Add new feature').

Push to the branch (git push origin feature/your-feature).

Create a new Pull Request.


This is a comprehensive `README.md` file for your project. Feel free to adjust any sections as needed!
