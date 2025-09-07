# FinCore-Banking-Management-System-CPP-OOP-Project-
FinCore is a console-based Banking Management System in C++, designed to simulate real-world banking operations in a modular and secure way. It applies OOP principles—inheritance, polymorphism, encapsulation, and abstraction—to ensure scalability and maintainability.

Each entity (`User`, `Customer`, `Admin`, `SuperAdmin`, `Bank`, `Currency`, `Transactions`, `TaxationDepartment`) is implemented in separate `.h` and `.cpp` files, making the project modular and maintainable.  

---

## Features  

- Customer: Create account, deposit, withdraw, transfer funds, view history, update info, delete account.  
- Admin: Manage customer accounts, search, backup, reports, sorting.  
- Super Admin: Manage admins, view revenue, taxation control.  
- Bank & Taxation: Track total accounts and funds, calculate tax.  
- Currency: Add new currencies, update/view rates.  

---

## Technical Details  
- Language: C++  
- Design: Modular with separate headers & source files  
- Data Storage: File handling (`.admin` & `.customer` files)  
- Testing: Unit testing for deposits, withdrawals, account updates, deletion, tax calculations  
- Security: Password validation (minimum 8 characters)  

---

## Project Structure

FinCore/
│
├── src/                     # Source code
│   ├── main.cpp             # Entry point
│   ├── User.h / User.cpp
│   ├── Customer.h / Customer.cpp
│   ├── Admin.h / Admin.cpp
│   ├── SuperAdmin.h / SuperAdmin.cpp
│   ├── Bank.h / Bank.cpp
│   ├── Currency.h / Currency.cpp
│   ├── Transactions.h / Transactions.cpp
│   ├── TaxationDepartment.h / TaxationDepartment.cpp
│   └── Makefile
│
├── docs/                    # Documentation
│   ├── User Manual.pdf
│   ├── Unit Testing.pdf
│   └── Class Diagram.pdf
│
├── data/                    # Data storage
│   ├── *.customer           # Customer account files
│   └── *.admin              # Admin account files
│
└── README.md                # Project manual

---

## Unit Testing

Implemented for:

- depositAmount()

- withdrawAmount()

- updateEmail() / updateContactNumber()

- deleteAccount()

- calculateTax()
