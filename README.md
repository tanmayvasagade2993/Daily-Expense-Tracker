# Daily-Expense-Tracker
# DailyExpenseTracker
An expenditure tracker to keep track of personal finance expenses spend on daily basis.
This project is a Daily Expense Tracker built using NetBeans for the development environment and SQL for the database. It helps users manage and track their daily expenses, categorize them, and analyze their spending habits.

Features
Track Daily Expenses: Record daily expenditures with details like category, amount, and date.
Expense Categories: Add custom categories to organize your expenses (e.g., Food, Transport, Entertainment).
Database Integration: Stores expense data in an SQL database for persistent storage and future retrieval.
Expense Summary: Provides a summary of total expenses within a given time period.
User-friendly Interface: Designed with a simple and intuitive UI for easy use.
Technologies Used
NetBeans IDE: Used for the development and implementation of the project.
SQL Database: Used for storing and managing expenses data.
JDBC (Java Database Connectivity): For connecting the NetBeans application to the SQL database.
Database Structure
The project uses a simple SQL database with the following tables:

Expenses Table
id (INT) - Unique identifier for each expense.
category (VARCHAR) - The category of the expense.
amount (DECIMAL) - The amount spent.
date (DATE) - Date of the expense.
Installation
Clone/Download the Project

Clone this repository or download the project files.
Set Up the Database

Create an SQL database and use the provided schema to set up tables.
Example schema:

sql
Copy
CREATE TABLE Expenses (
  id INT AUTO_INCREMENT PRIMARY KEY,
  category VARCHAR(50),
  amount DECIMAL(10, 2),
  date DATE
);
Configure Database Connection

Update the database connection details in the project (usually in the DBConnection.java file).
Modify the database URL, username, and password accordingly.
Open the Project in NetBeans

Open the project in NetBeans IDE.
Build the project.
Run the Application

Execute the project by clicking the Run button in NetBeans.
Usage
Add an Expense: Use the "Add Expense" button to input details like category, amount, and date.
View Expenses: The application will display a list of all recorded expenses.
View Summary: Get a summary of the total expenses for a given time period (e.g., daily, monthly).
Future Improvements
Authentication: Add user authentication for personalized expense tracking.
Charts and Reports: Implement graphical charts and reports for better expense analysis.
Expense Export: Allow exporting data to formats like CSV or PDF.
License
This project is licensed under the MIT License.

