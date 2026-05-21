🍽️ Online Food Ordering System (Restaurant)

A full-stack web application for restaurant management and online food ordering built with PHP + MySQL. This system allows users to browse menus, manage cart, place orders, submit reviews, and reserve tables while giving admins full control over operations.

🚀 Live Project Overview

This project is a complete restaurant automation system including:

Food ordering system
Cart management
Order processing
Reservation system
User authentication
Review system
📌 Table of Contents
About Project
Features
File Structure
System Workflow
Installation
Database Setup
How to Run
Screenshots
Future Improvements
Author
📖 About The Project

The Online Food Ordering System is designed to digitalize restaurant operations. It removes manual order handling and allows customers to interact with the restaurant online.

🔥 Main Goal:

To build a fast, scalable, and user-friendly restaurant system where:

Customers can order food easily
Admin can manage everything in one place
✨ Features
👤 User Features
User registration & login
Browse food menu
Add items to cart
Update cart quantity
Remove items from cart
Place orders
Order confirmation system
Order history
Table reservation
Profile management
Submit food reviews
🍽️ Food Ordering System
Dynamic menu display
Cart system
Order processing workflow
Order confirmation page
⭐ Review System
Submit ratings & feedback
View order-based reviews
🪑 Reservation System
Book tables online
Manage reservations
🧩 File Structure (Your Project)
Online-Food-Ordering-System/
│
├── action.php
├── add_to_cart.php
├── cancel_order.php
├── cart.php
├── cart.css
├── db_connection.php
├── dblogin.php
├── dbregister.php
├── delete_cart_item.php
├── fetch_orders.php
├── footer.html
├── index.php
├── index.css
├── login.php
├── login.css
├── logout.php
├── menu.php
├── menu.css
├── navbar.php
├── nav-logged.php
├── order_confirm.php
├── order_review.php
├── order_review.css
├── orders.php
├── process_order.php
├── profile.php
├── profile.css
├── reservations.php
├── submit_reviews.php
├── update_cart_quantity.php
└── restaurant.sql
🔄 System Workflow
1. User Flow
Register → Login → Browse Menu → Add to Cart → Checkout → Order Confirmed
2. Order Flow
Cart → process_order.php → orders.php → admin processing → completion
3. Review Flow
Delivered Order → order_review.php → submit_reviews.php
🛠️ Technology Stack
PHP (Backend)
MySQL (Database)
HTML5
CSS3
JavaScript
Bootstrap (optional UI support)
AJAX (for cart/order updates)
⚙️ Installation Guide
1️⃣ Clone Project
git clone https://github.com/your-username/online-food-ordering-system.git
2️⃣ Move to XAMPP

Move folder to:

C:/xampp/htdocs/
3️⃣ Start Server

Open XAMPP:

Start Apache
Start MySQL
4️⃣ Create Database

Open phpMyAdmin:

Database name: restaurant

Import:

restaurant.sql
5️⃣ Run Project

Open browser:

http://localhost/your-project-folder/
🗄️ Database Info
Database: restaurant
File: restaurant.sql
Contains:
users
orders
cart
reviews
reservations
🔐 Core Modules Explained
🛒 Cart System

Files:

add_to_cart.php
cart.php
update_cart_quantity.php
delete_cart_item.php
📦 Order System

Files:

process_order.php
orders.php
order_confirm.php
cancel_order.php
👤 Authentication

Files:

login.php
dblogin.php
dbregister.php
logout.php
⭐ Review System

Files:

order_review.php
submit_reviews.php
🪑 Reservation System

Files:

reservations.php
🎯 Key Highlights
Clean modular PHP structure
AJAX-based cart updates
Secure login system
Lightweight and fast
Easy database integration
Beginner-friendly architecture
🚀 Future Improvements
Admin dashboard panel
Online payment integration (Esewa / Khalti)
Real-time order tracking
Email/SMS notifications
API-based backend upgrade
React frontend upgrade
Mobile app version
👨‍💻 Author

Omprakash Gharti Magar

GitHub: https://github.com/ai-omprakash

⭐ Project Status

✔ Completed
✔ Functional
✔ Portfolio Ready
✔ Beginner-to-Mid Level Full Stack Project
