# 🏧 ATM Interface

## 📌 Overview
This project is a simple ATM (Automated Teller Machine) interface implemented in Java. It allows users to perform basic banking transactions such as withdrawing money, depositing funds, and checking their account balance through a console-based menu.

## ✨ Features
- 💵 Withdraw money from the account (if sufficient balance is available)
- 💰 Deposit money into the account
- 📊 Check the current account balance
- 🚪 Exit the ATM interface

## 🛠 Technologies Used
- ☕ Java


## 🚀 How to Run
1. Ensure you have Java installed on your system.
2. Copy and save the Java file with a `.java` extension.
3. Open a terminal or command prompt and navigate to the directory containing the file.
4. Compile the Java program using:
   ```sh
   javac atm_Interface.java
   ```
5. Run the compiled program using:
   ```sh
   java atm_Interface
   ```
6. Follow the on-screen instructions to interact with the ATM system.

## 📂 Code Structure
### 📌 Classes:
1. **🏦 BankAccount**
   - Handles account balance, withdrawal, and deposit functionalities.
2. **🖥 ATM**
   - Provides an interactive menu for the user.
   - Calls `BankAccount` methods for transactions.
3. **📌 atm_Interface (Main Class)**
   - Initializes the bank account and ATM interface.
   - Starts the ATM operation.

## 💡 Example Usage
```
Welcome to the ATM
1. Withdraw
2. Deposit
3. Check Balance
4. Exit
Choose an option: 2
Enter deposit amount: 500
Deposit successful. New balance: $1500
```

## 🔮 Future Enhancements
- 🔑 Implement user authentication with a PIN.
- 📜 Add transaction history.
- 🖥 Improve UI using a graphical interface.

## ✍️ Author
Jigyasa


