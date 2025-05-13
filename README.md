# Simple PHP Blog Website

This is a basic blog web application developed using plain PHP and MySQL. It is designed as a simple CRUD (Create, Read, Update, Delete) system for learning purposes.

## 🎯 Project Goal

The goal of this project is to practice core PHP skills and understand how basic blog systems work without using any frameworks.

## 🧩 Features

- Add new blog posts
- View blog post list
- Read single post with full content
- Edit and update blog posts
- Delete blog posts
- Basic user authentication (optional)
- Clean and minimal UI

## 🛠️ Technologies Used

- PHP (Vanilla / Core PHP)
- MySQL
- HTML5 & CSS3
- Basic JavaScript (for validation)
- Apache (XAMPP, Laragon, or similar)

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/php-simple-blog.git
Create a new database:

    Import blog.sql into your MySQL server (phpMyAdmin or CLI)

Configure database connection:

    Open config/db.php and update DB credentials

Run the project:

    Put the folder into htdocs (XAMPP) or www (Laragon)

    Go to http://localhost/php-simple-blog in your browser

📁 Folder Structure
/php-simple-blog
│
├── config/         # Database connection file
├── includes/       # Reusable PHP components
├── posts/          # Create, edit, delete post logic
├── views/          # Frontend templates
├── assets/         # CSS, JS, images
├── index.php       # Main landing page (blog list)
├── blog.sql        # Database dump file
└── README.md

👨‍💻 Author

Samandar
Student of Applied Mathematics
Learning PHP through practical projects

📄 License

Free to use for educational and personal learning purposes.
