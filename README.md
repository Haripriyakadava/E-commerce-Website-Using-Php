🛒 E-Commerce Website (PHP + MySQL)

This is a simple E-commerce website built using PHP and MySQL with XAMPP server.  
It supports user authentication, product management, and cart functionality.  

🚀 Features
- User Registration & Login
- Add to Cart, View Cart, Remove from Cart
- Admin Panel for managing products
- MySQL Database Integration
- Basic UI with HTML/CSS

🗂️ Project Structure

E-COMMERCE/
│── admin/ # Admin panel (add/manage products, login/logout)
│── css/ # Stylesheets
│── images/ # Product and UI images
│── includes/ # Database connection file
│── pages/ # User pages (cart, login, register, etc.)
│── index.php # Homepage
│── test_db.php # Database testing


🛠️ Installation Guide

1.Clone Repository

git clone https://github.com/Haripriyakadava/E-commerce-Website-Using-Php.git

2.Move to XAMPP htdocs

C:/xampp/htdocs/E-Commerce

3.Import Database

--> Open phpMyAdmin
--> Create a new database (e.g., ecommerce_db)
--> Import the SQL file from:
database/ecommerce.sql

4.Configure Database

Update database connection in includes/db.php:
$host = "localhost";
$user = "root";      // default user
$pass = "";          // default password (empty in XAMPP)
$db   = "ecommerce_db"; // your database name
$conn = mysqli_connect($host, $user, $pass, $db);

▶️ Run the Project
Start Apache and MySQL from XAMPP control panel
Open your browser:
http://localhost/E-Commerce/

📷 Screenshots

🔑 Login Page
![Screenshots/login.png](Screenshots/login.png)

🏠 Home Page
![Home Page](Screenshots/home.png)

🛒 Cart Page
![Cart Page](Screenshots/cart.png)

🔐 Admin Login Page
![Admin Login](Screenshots/Admin login.png)

📊 Admin Dashboard
![Admin Dashboard](Screenshots/admin-dashboard.png)

📦 Manage Products
![Manage Products](Screenshots/manage-products.png)



📌 Notes

Default database user → root, password → (empty).
Make sure XAMPP is installed and running.
Customize CSS in css/style.css.

👩‍💻 Author
Haripriya Kadava