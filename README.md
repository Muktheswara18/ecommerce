# Basic E-commerce Website

A simple e-commerce website built using **HTML**, **CSS**, **PHP**, and **MySQL**, developed locally with **XAMPP**. It includes essential features like user registration, login, product listing, and a basic cart system.

---

## 🚀 Features

- Product listing page
- User registration & login
- Admin login
- Add-to-cart functionality
- Cart page with item display and remove option
- MySQL database integration

> ❗ Note: Checkout and payment functionality are **not implemented** in this version.

---

## 🛠 Tech Stack

- **Frontend**: HTML, CSS
- **Backend**: PHP
- **Database**: MySQL
- **Local Server**: XAMPP (Apache + MySQL)

---

## 📁 Project Structure
ecommerce-website/
├── css/
│ └── style.css
├── images/
│ └── product1.jpg
├── js/
│ └── script.js
├── includes/
│ └── db_connect.php
├── index.php
├── login.php
├── register.php
├── cart.php
├── admin.php
├── ecommerce.sql


---

## 💾 How to Run Locally

1. **Install XAMPP**  
   Download and install [XAMPP](https://www.apachefriends.org/index.html)

2. **Clone or Download this Repository**

3. **Move the Project to XAMPP Folder**  
   Place the folder inside:C:\xampp\htdocs\
   

4. **Start Apache and MySQL in XAMPP Control Panel**

5. **Import the Database**
- Open your browser and go to: `http://localhost/phpmyadmin`
- Create a new database (e.g., `ecommerce`)
- Click **Import** and select the `ecommerce.sql` file from the project folder

6. **Access the Website**
Open your browser and navigate to:http://localhost/ecommerce-website

---

## 🔐 Sample Login Credentials

### User:
- **Email:** user@example.com
- **Password:** 123456

### Admin:
- **Email:** admin@example.com
- **Password:** admin123

> *(You can modify or add new users directly in the MySQL database.)*

---

## 📝 Database Connection File 

Ensure your `db_connect.php` file has the correct connection settings:
```php
<?php
$conn = mysqli_connect("localhost", "root", "", "ecommerce");
if (!$conn) {
 die("Connection failed: " . mysqli_connect_error());
}
?>
```
---


## 📌 Future Enhancements

```markdown
- Add checkout and payment gateway integration (e.g., PayPal, Stripe)
- Product category and search filtering
- Wishlist and save-for-later features
- User profile management and order history
- Admin panel to manage products, users, and orders
- Product ratings and reviews
- Responsive design using Bootstrap or a front-end framework
- Email notifications for orders and registration
- Security improvements (e.g., input validation, password hashing)
- Pagination for large product listings
```

