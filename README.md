Bank Account Management System
This project demonstrates a simple bank account management system implemented in C++. It includes two types of accounts: Current Account and Savings Account, each inheriting from a base class account.

Features
Current Account

Deposit money
Withdraw money (with a minimum balance check)
Display current balance
Savings Account

Deposit money (with interest calculation)
Withdraw money (with a minimum balance check)
Display current balance
Classes
account
The base class representing a generic bank account.

Attributes
name: Customer name
accno: Account number
atype: Account type
Methods
getAccountDetails(): Accepts customer details.
displayDetails(): Displays customer details.
current_account
Derived from account, representing a current account with additional balance management.

Attributes
balance: Current account balance
Methods
c_deposit(): Deposits money into the current account.
c_withdraw(): Withdraws money, ensuring the balance remains above a minimum threshold.
c_display(): Displays the current balance.
saving_account
Derived from account, representing a savings account with interest calculation.

Attributes
sav_balance: Savings account balance
Methods
s_deposit(): Deposits money into the savings account, calculating interest.
s_withdraw(): Withdraws money, ensuring the balance remains above a minimum threshold.
s_display(): Displays the savings account balance.
Usage
The program prompts the user to choose between a savings or current account and performs operations accordingly. The user can deposit, withdraw, display balance, and view account details.
