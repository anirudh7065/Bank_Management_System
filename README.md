# Bank Account Management System

A console-based banking application developed in **C++** that enables users to perform basic banking transactions from their PC or laptop.

---

## Features

- Secure admin login  
- Create new bank accounts  
- Deposit cash into accounts  
- Withdraw cash from accounts  
- Check balance details of an account  
- Display list of all account holders  
- Modify existing account details  
- Close (delete) an account  
- Persistent storage using binary file handling (`account.dat`)  

---

## Description

This application provides a simple and secure interface to manage bank accounts. Only authorized users (via admin login) can access the system to perform transactions and view customer account details. The data is stored in a binary file which maintains account information across sessions.

---

## How to Use

1. **Admin Login**  
   The application starts by requesting the admin username and password.  
   - Username: `abhi7065`  
   - Password: `706595`  

2. **Main Menu Options:**  
   - `1` - Create a new account  
   - `2` - Deposit amount to an account  
   - `3` - Withdraw amount from an account  
   - `4` - Check balance details of an account  
   - `5` - Display all account holders  
   - `6` - Close (delete) an account  
   - `7` - Modify account details  
   - `8` - Exit the program  

3. Follow on-screen prompts to input account numbers, amounts, and other details as required.

---

## Compilation & Running

### Prerequisites

- A C++ compiler like `g++` or an IDE (Visual Studio, Code::Blocks, etc.)

### Compile

```bash
g++ -o bank_management_system bank_management_system.cpp
````

### Run

```bash
./bank_management_system
```

---

## Code Highlights

* **Account Class:** Encapsulates account details and operations like creating, modifying, depositing, withdrawing, and reporting.
* **File Handling:** Uses binary file streams to read/write accounts to `account.dat`.
* **Data Persistence:** All account data is saved in a file and persists between program runs.
* **Input Validation:** Basic input prompts with case normalization for account types (C/S).
* **Clear Console:** Uses `system("CLS")` to clear screen (Windows specific).

---

## Notes

* Ensure you run this on a Windows environment because of `system("CLS")` calls. For Linux/macOS, replace with `system("clear")` or remove.
* The admin credentials are hardcoded for simplicity.

---

## Author

**Abhishek Valsan**

---

## License

This project is open source and free to use.

---

Feel free to contribute or report issues!

```
