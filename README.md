# UserFormSystem
A lightweight user form system that lets users submit their **name** and **age**, stores the data in a MySQL database, and displays a styled success message using PHP sessions.
## ⚙️ Technologies Used
- 💻 HTML & CSS – Form and display layout
- 🐘 PHP – Data processing and session handling
- 🗄️ MySQL – Database storage
- 🔐 PHP Sessions – Secure data sharing across pages

## 📁 Project Structure

form_project/
├── form.html          # The main form where users input their name and age
├── submit.php         # Processes form data and inserts it into the database
├── result.php         # Displays the submitted data using PHP sessions
├── userdata.sql       # (Optional) SQL file to create the required database table
└── README.md          # Documentation and usage guide


## 🚀 How to Run
1. Make sure XAMPP or any local server with PHP & MySQL is running.
2. Create a MySQL database named `userdata` and run the following SQL:
   ```sql
   CREATE TABLE users (
     id INT AUTO_INCREMENT PRIMARY KEY,
     name VARCHAR(255),
     age VARCHAR(255)
   );
Place the project folder inside your server directory (e.g., htdocs/form_project).

Open the form in your browser:

http://localhost/form_project/form.html
Submit the form to save the data and view the result.

🎨 Features
Clean UI with a centered success message

Uses prepared statements for security

PHP sessions for data persistence across pages

Easy to expand with admin dashboard or user list view

👩‍💻 Developer Aryam
