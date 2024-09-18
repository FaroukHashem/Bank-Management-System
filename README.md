# Banking System ATM Program


https://github.com/user-attachments/assets/f1bbe2f3-f25e-4636-b359-1642871acf60



## Problem Description
This project is a program that simulates a banking system through an ATM interface. The program interactively deals with the user and provides different banking services such as account creation, deposits, withdrawals, and transfers.

## Features

- **Account Creation:** The program allows users to create a new account by entering their name and a 10-digit card number.
- **Deposit Functionality:** Users can deposit money into their account, with an additional 1% bonus added to the deposit amount.
- **Withdrawal Functionality:** Users can withdraw money from their account, with a 3% fee deducted from the withdrawal amount.
- **Money Transfer:** Users can transfer money between accounts, with a 1.5% deduction from both the sender’s and the receiver’s accounts.
- **Account Information:** Users can view account details including the account holder's name, card number, and the current balance.
- **Interactive Program Flow:** The program continuously interacts with users until they choose to terminate the program.

## Code Structure

### Class: `ATM`

The `ATM` class consists of the following members:

### Variables:
- **Account Name:** Holds the name of the account owner (up to 100 characters).
- **Card Number:** A 10-digit card number.
- **Amount:** The current amount of money in the account.

### Functions:
- **`create_new_acc()`:** Allows users to create a new account by entering their name and card number.
- **`Deposit()`:** Adds a deposited amount to the account balance, with an extra 1% bonus.
- **`Withdrawal()`:** Deducts the requested amount from the account balance, along with a 3% fee.
- **`Transfer()`:** Transfers money between two accounts, deducting 1.5% from both accounts involved.
- **`Print_acc_data()`:** Prints the account details including the account name, card number, and the current balance.

## Constants and Equations
- **Maximum Accounts:** The program supports a maximum of 100 accounts.
- **Deposit Bonus:** An extra 1% of the deposited amount is added to the account.
- **Withdrawal Fee:** A 3% fee is deducted from the withdrawal amount.
- **Transfer Fee:** 1.5% is deducted from both accounts during a transfer.

## Program Flow
The program interactively processes user inputs and continues until the user decides to terminate the program. Proper input validation is implemented, such as ensuring the card number consists of exactly 10 digits. Different corner cases are handled to ensure smooth user interaction.
