# Gym-Management-System
# 🏋️‍♂️ Gym Management System

A web-based application to streamline the management of gym memberships, bookings, profiles, and payments. Built using **PHP**, **MySQL**, **HTML/CSS**, and **JavaScript**.

## 🚀 Features

- 🧾 Member Registration & Login
- 📅 Booking History
- 🧑‍💼 Admin Dashboard
- 💳 Payment Management (Full/Partial)
- ✉️ Contact & Feedback
- 🔐 Password Management
- 📁 Session-based Authentication

## 📂 Project Structure

├── admin/ │ ├── full-payment-bookings.php │ ├── partial-payment-bookings.php │ ├── new-bookings.php │ └── ... ├── include/ │ ├── config.php │ ├── header.php │ ├── footer.php │ └── ... ├── Booking-History.php ├── index.php ├── login.php ├── logout.php ├── contact.php └── ...

markdown
Copy
Edit

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL

## 📦 Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ROHIT-THOTA01/Gym-Management-System.git
   cd Gym-Management-System
2.Set Up the Database:

Create a MySQL database (e.g., gym_db).

Import the SQL file (if provided) via phpMyAdmin or MySQL CLI.

3.Configure DB Connection:

Open include/config.php and set your DB credentials:

php
Copy
Edit
$con = mysqli_connect("localhost", "root", "", "gym_db");
4.Start Local Server: Using PHP built-in server:

bash
Copy
Edit
php -S localhost:8000
Then open: http://localhost:8000

🧑‍💻 Author
Rohit Thota
GitHub

📄 License
This project is licensed under the MIT License.
