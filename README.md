# Bank Management System 🏦

## Overview
The Bank Management System is a Java-based console application that simulates the core operations of a banking institution. Built with strong Object-Oriented Programming (OOP) principles, the system manages different user roles, handles financial transactions, and persists data using local text files.

## 🌟 Features
* **Role-Based Access Control:** Separate logic and permissions for `Admin`, `Employee`, and `Client` users.
* **Account Management:** Support for different account types, specifically `Current` and `Saving` accounts.
* **Financial Operations:** Automated handling of `Fees` and `Profits` through dedicated Java interfaces.
* **Transaction Tracking:** A robust `Transaction` system to process and record all account activities.
* **State Management:** Utilizes Enums (`AccountType`, `UserAction`) to strictly categorize accounts and track user behaviors.
* **Data Persistence:** Stores and retrieves system data locally using flat text files (`client.txt`, `employee.txt`, `transaction.txt`).

## 🛠️ Technologies Used
* **Language:** Java
* **Architecture:** Object-Oriented Programming (Inheritance, Polymorphism, Interfaces)
* **Storage:** File I/O (Text files)[cite: 2]
* **IDE:** IntelliJ IDEA (Ready to import via the `.idea` configuration)

## 📂 Project Structure

├── src/
│   ├── Main.java               # Application entry point
│   ├── User.java               # Base abstract class for system users
│   ├── Admin.java              # Admin role implementation[cite: 2]
│   ├── Employee.java           # Employee role implementation
│   ├── Client.java             # Client role implementation
│   ├── Account.java            # Base account model
│   ├── Current.java            # Current account implementation
│   ├── Saving.java             # Saving account implementation
│   ├── Transaction.java        # Transaction processing logic
│   ├── enums/
│   │   ├── AccountType.java    # Enum for account categorization
│   │   └── UserAction.java     # Enum for tracking user actions
│   └── interfaces/
│       ├── Fees.java           # Interface for fee deduction logic
│       └── Profits.java        # Interface for interest/profit calculation
├── client.txt                  # Database file for clients
├── employee.txt                # Database file for employees
└── transaction.txt             # Database file for transaction logs

