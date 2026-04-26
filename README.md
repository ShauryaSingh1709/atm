ATM Banking System
Project Overview
A console-based ATM Banking System implemented in Python, providing core banking functionalities including balance checking, deposits, withdrawals, and transaction history tracking. This project demonstrates object-oriented programming concepts, file handling, and user interface design.

Features
Balance Inquiry - View current account balance
Cash Deposit - Add funds to account
Cash Withdrawal - Withdraw money (with balance validation)
Transaction History - Complete transaction log
User-Friendly Menu - Intuitive console interface
Input Validation - Error handling for invalid inputs
Tech Stack
Language: Python


Quick Start
Prerequisites
Python 3.6 or higher
Installation & Run
bash


# Clone/Download the project
git clone 
cd ATM-Banking-System

# Run the application
python main.py
 How to Use
Launch the application
Choose from the menu options:


1. Check Amount
2. Deposit Amount  
3. Withdraw
4. Statement
5. Exit
Follow on-screen prompts
View transaction history anytime
Sample Usage


Welcome!
Please choose an option:
1.Check Amount
2.Deposite Amount
3.Withdraw
4.Statement
5.Exit
Enter choice: 2
Enter Amount: 1000
Deposit Successful!
Code Architecture
Key Functions
Function

Description

Parameters

checkbalance()

Displays current balance

None

deposit()

Adds money to account

User input

withdraw()

Withdraws money with validation

User input

statement()

Shows transaction history

None

Data Flow


User Input → Menu Handler → Function Call → Balance/Transactions Update → Display Result
Testing
Test Cases


