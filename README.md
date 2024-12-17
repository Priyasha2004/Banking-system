# Banking-system
# Introduction
The Banking System is a Python-based application that allows users to manage their banking transactions securely and efficiently. This system is backed by a MySQL database and offers a range of functionalities for user management and banking transactions.
# Features
1. Add User: Create a new user with validated fields such as name, account number, password, balance, contact number, email, and address.
2. Show User: Display user information in a proper format.
3. Login: Secure user login with account number and password.
4. Banking Operations: Perform transactions like credit, debit, viewing balance and updating profile.
5. Account Management: Activate or deactivate accounts and change the user’s password.
# Requirements
• Python 3.X  
• MySQL  
• mysql-connector for Python
# Database Structure
The system uses a MySQL database called banking_system with the following tables:  

Banking System README
Overview
The Banking System is a Python-based application that allows users to manage their banking transactions securely and efficiently. This system is backed by a MySQL database and offers a range of functionalities for user management and banking transactions.

Features:
Add User: Create a new user with validated fields such as name, account number, password, balance, contact number, email, and address.
Show User: Display user information in a proper format.
Login: Secure user login with account number and password.
Banking Operations: Perform transactions like credit, debit, transfers, viewing balance, viewing transaction history, and updating profile.
Account Management: Activate or deactivate accounts and change the user’s password.
Requirements
Python 3.x
MySQL (for the database)
MySQL Connector for Python
Install required Python libraries using the following command:

bash
Copy code
pip install mysql-connector-python
Database Structure
The system uses a MySQL database called banking_system with the following tables:
1. users
Stores the details of the users.
2. login
Contains login details for users.
3. transaction
Contains transaction details of users.
# Features And Functions
1. Add User
This feature allows the admin or the system to add new users with the following fields:
• Name
• Account number
• Date of birth
• City
• Password
• Initial Balance
• Contact Number
• Email ID
• Address
2. Show User
Displays the user's information in a formatted output (e.g., name, account number, balance, email, etc.).
3. Login
Users can log in with their account number and password. After successful login, the following actions are available:
• Show balance
• show transaction details
• Credit amount
• Debit amount
• Activate/Deactivate account
• Change password
• Update profile
4. Exit
Exit the application safely.
# Conclusion
The Banking System is a secure and user-friendly application to manage users, transactions, and account details. It provides an easy-to-use interface for both admins and users to perform day-to-day banking tasks securely.
