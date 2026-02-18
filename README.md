
# Simple Banking System (C++)
📌 Description

A simple **console-based** banking application in C++ that demonstrates basic Object-Oriented Programming concepts such as classes, encapsulation, and composition using `Customer` and `Account` classes.
This is a simple Banking System implemented in C++ as part of CodeAlpha Task 2.
The program allows a user to create a customer account and perform basic banking operations such as deposit, withdraw, and view account details using a menu-driven interface.

## Features
🚀 Features

- Maintains a single customer's bank account.
- Supports deposit and withdrawal operations with basic validation.
- Displays customer details and current account balance.
- Menu-driven interface for user interaction via the terminal.
Create a customer account

## Concepts Used
Deposit money into the account

- C++ classes and objects (`Customer`, `Account`).
- Encapsulation using private data members and public getters/setters.
- Constructors with default parameters.
- Menu loop using `do-while` and `switch` statement.
- Basic input validation for user choices and transaction amounts.
Withdraw money with balance validation

## File Structure
View customer and account details

- `main.cpp` (or your chosen filename): Contains the full implementation of:
  - `Account` class (handles balance, deposit, withdraw, and balance display).
  - `Customer` class (stores customer name and associated account).
  - `main()` function with the menu loop.
User-friendly menu-driven system

## How It Works
Input validation for invalid amounts

1. A `Customer` object is created with:
   - Name: `"Student"`
   - Account Number: `1001`
   - Initial Balance: `0.0`
2. The program repeatedly shows a menu:
   - `1. Deposit`
   - `2. Withdraw`
   - `3. View Account Details`
   - `4. Exit`
3. On each choice:
   - Deposit: Prompts for an amount, validates it, and updates balance.
   - Withdraw: Prompts for an amount, checks for sufficient balance, and updates balance.
   - View Account Details: Shows customer name, account number, and current balance.
   - Exit: Ends the program.
🛠️ Technologies Used

## Compilation and Execution
Language: C++

Use any C++ compiler like `g++`:
Concepts:

```bash
g++ main.cpp -o banking_app
./banking_app
Classes & Objects
Encapsulation
Conditional Statements
Loops
User Input/Output
📂 Project Structure
Banking-System/
│
├── main.cpp   // Source code
└── README.md  // Project documentation
▶️ How to Run the Program
Make sure you have a C++ compiler installed (e.g., g++).
Save the code in a file named main.cpp.
Open a terminal or command prompt.
Compile the program:
g++ main.cpp -o banking
Run the executable:
./banking
📋 Menu Options
====== Banking Menu ======
1. Deposit
2. Withdraw
3. View Account Details
4. Exit
🧪 Sample Output
Enter Customer Name: John Doe
Enter Account Number: 12345
====== Banking Menu ======
1. Deposit
2. Withdraw
3. View Account Details
4. Exit
Enter your choice: 1
Enter amount to deposit: $500
Money deposited successfully.
⚠️ Validations Included
Deposit amount must be greater than 0
Withdrawal amount must not exceed account balance
Invalid menu choices are handled properly
📌 Conclusion
This project demonstrates basic object-oriented programming concepts in C++ and simulates a simple real-world banking system. It is ideal for beginners learning classes, objects, and menu-based programs.
0 commit comments
Comments
0
 (0)
Comment
You're not receiving notifications from this thread.

Copied!
