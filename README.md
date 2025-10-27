# Expense-Tracker
This project focuses on detecting and classifying spam or fake news articles using Natural Language Processing (NLP) and Machine Learning. The goal is to build an accurate model to distinguish between real and fake news content. 
A web-based Expense Tracker** built using **HTML, CSS, JavaScript, and PHP** to help users record, manage, and analyze their daily expenses efficiently. This project provides an intuitive interface for tracking spending habits and maintaining financial discipline.
## Features
- Add, edit, and delete expenses easily  
- Categorize expenses (Food, Travel, Bills, Shopping, etc.)  
- View total and category-wise spending  
- Filter expenses by date or category  
- Responsive and user-friendly interface  
- Data stored securely using MySQL database  
- Optional login system for multiple users  
- Real-time updates and interactive dashboard
Tech Stack
| Layer        | Technology Used |
|---------------|-----------------|
| Frontend      | HTML, CSS, JavaScript |
| Backend       | PHP |
| Database      | MySQL |
| Styling       | CSS3 |
| Optional Charts | Chart.js (for visualization) |
 Installation & Setup
Import the database
Locate the database.sql file in the project folder.
Import it into your MySQL server using phpMyAdmin.
Configure Database Connection
Open config.php and update the database credentials:
php
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "expense_tracker_db";
Start the server
Launch XAMPP or any local server.
Open your browser and visit:
arduino
Copy code
http://localhost/expense-tracker/
 Project Structure
pgsql
Copy code
Expense-Tracker/
│
├── index.html             # Home / Dashboard page
├── add_expense.php        # Form to add new expenses
├── view_expense.php       # Display expense list
├── delete_expense.php     # Delete functionality
├── update_expense.php     # Edit/update entries
├── config.php             # Database connection file
├── assets/
│   ├── css/
│   │   └── style.css      # Styling files
│   ├── js/
│   │   └── script.js      # Frontend interactivity
│   └── img/               # Icons or images
└── database.sql           # MySQL database schema
🧮 How It Works
Users can input expense details (date, category, description, amount).
JavaScript validates data before submission.
PHP handles server-side processing and stores data in the MySQL database.
Expenses are dynamically displayed on the dashboard.
Users can filter or delete entries as needed.
Future Enhancements
Add income tracking and budget limits
🧑‍💻 Author
Swadha Sharma
B.Tech (Computer Science - AI)
Banasthali Vidyapith 
