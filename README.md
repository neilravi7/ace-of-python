# Core Python Banking & Authentication System

A practice project built with **core Python** to explore concepts like:
- Object-Oriented Programming (OOP)
- File handling with CSV
- Custom exceptions
- Decorators
- Authentication & authorization
- Basic account operations (deposit, withdrawal, balance check)
- Password encryption using `cryptography.Fernet`

---

## 🚀 Features
- **User & Admin Authentication**  
  - Users login with email/password  
  - Admins login with a secret key  

- **Role-Based Access Control**  
  - Admin-only operations (e.g., creating new users)  
  - Decorator `@admin_operations` enforces admin privileges  

- **Account Management**  
  - Create accounts for customers  
  - Deposit, withdraw, and check balance  
  - Error handling for invalid amounts or insufficient balance  

- **Security**  
  - Passwords stored in encrypted form  
  - Unique IDs and account numbers generated with `secrets.token_hex`

---

## 📂 Project Structure
project/ │── admin.csv │── users.csv │── accounts.csv │── main.py │── README.md
