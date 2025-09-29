# Bank-Account-Simulation-using-oops
Project Overview

The Bank Account Simulation is a simple Java Object-Oriented Programming (OOP) project that imitates how a real bank account works.
The program allows you to create a bank account, perform deposits and withdrawals, and maintain a record of all transactions.
It is an ideal exercise to practice Java OOP concepts such as classes, objects, methods, encapsulation, and data hiding.

Features to Implement
1. Account Class

Fields/Attributes:

String accountNumber

String accountHolderName

double balance

ArrayList<String> transactionHistory (to store details of each transaction)

Methods:

deposit(double amount) – Increases the balance and records the transaction.

withdraw(double amount) – Decreases the balance if sufficient funds exist and records the transaction.

getBalance() – Returns current balance.

printTransactionHistory() – Displays all transactions.

2. Main Class (Driver Program)

Provides a menu-driven interface to interact with the Account object:

Create a new account.

Deposit money.

Withdraw money.

Check balance.

View transaction history.

Exit.

Use Scanner for user input.
