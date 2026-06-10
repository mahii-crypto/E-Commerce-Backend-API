:

🛒 E-Commerce Backend API

A scalable RESTful E-Commerce Backend API built with Django REST Framework. The application provides authentication, product management, order processing, payment integration, and secure API endpoints for modern e-commerce platforms.

✨ Features
JWT Authentication and User Management
Product CRUD Operations with Categories
Order Management and Checkout System
Payment Gateway Integration (Stripe)
Email Verification and Password Reset
API Documentation using DRF Spectacular
PostgreSQL Database Support
Secure REST APIs with Django REST Framework

🛠️ Tech Stack
Technology	Purpose
Python	Backend Development
Django	Web Framework
Django REST Framework	API Development
PostgreSQL	Database
JWT	Authentication
Stripe	Payment Processing
Git & GitHub	Version Control
Render	Deployment

📂 Project Structure
ecommerce-api/
├── config/
├── users/
├── products/
├── orders/
├── payment/
├── requirements.txt
├── manage.py
└── README.md

🚀 Installation
git clone https://github.com/mahii-crypto/E-Commerce-Backend-API.git

cd E-Commerce-Backend-API

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver

🔌 API Endpoints
Method	Endpoint	Description
POST	/api/user/register/	User Registration
POST	/api/user/login/	User Login
GET	/api/products/	List Products
POST	/api/user/orders/	Create Order
POST	/api/user/payments/	Process Payment
🌐 Deployment

Backend deployed on Render.

👨‍💻 Author

Mahesh
