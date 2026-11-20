# Banking Management System

A console-based banking application built with Java, JDBC and MySQL.

## Features
- User registration and login
- Open a bank account
- Credit money, debit money and transfer money (secured with a PIN)
- Check balance

## Tech Stack
- Java
- JDBC
- MySQL

## Setup
1. Clone the repository:
   ```
   git clone https://github.com/mansidarswal/Banking_Management_System.git
   ```
2. Run `database/schema.sql` in MySQL to create the database and tables.
3. In IntelliJ, open **Run → Edit Configurations** and set these environment variables:
   ````
   DB_URL=jdbc:mysql://localhost:3306/banking_system;DB_USERNAME=your_username;DB_PASSWORD=your_password
   ````
4. Run `BankingApp.java`.

## Project Structure
````
├── database/schema.sql
└── src/BankingManagementSystem/
    ├── AccountManager.java
    ├── Accounts.java
    ├── BankingApp.java
    └── User.java
````