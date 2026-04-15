# Bank-Management-System
📄 Banking System Documentation
1. Overview
This program is a simple console-based banking system written in C++. It allows users to create and manage accounts, perform transactions, and provides an admin panel for oversight. Data is stored in arrays, and the system supports up to 100 accounts.

2. Features
👤 User Functions
Create Account

Supports Savings and Checking accounts.

Requires a minimum opening deposit of Rs. 500.

Generates a unique account number starting from 1001.

PIN authentication for security.

Login & Account Menu

Deposit money.

Withdraw money.

Transfer funds to another account.

View account details.

Change PIN.

Logout option.

🔑 Admin Functions
List All Accounts – Displays all accounts with details.

Search Account – Find and view details of a specific account.

Close Account – Deactivate an account.

Bank Summary – Shows total accounts, active accounts, and total money in the bank.

Admin access is protected by a password (admin123).

3. Data Structures
Arrays store account information:

accountNumber[] – Unique account IDs.

accountName[] – Holder’s name.

accountType[] – Savings or Checking.

accountPin[] – 4-digit PIN.

accountBalance[] – Current balance.

accountActive[] – Status (Active/Closed).

Global Variables

totalAccounts – Tracks number of accounts.

nextAccountNumber – Generates sequential account numbers.

4. Program Flow
Main Menu
Code
WELCOME TO MY BANK SYSTEM
-----------------------------------------------
1. Create New Account
2. Login
3. Admin Panel
0. Exit
Option 1 → createAccount()

Option 2 → login() → accountMenu()

Option 3 → adminMenu()

Option 0 → Exit program

5. Security
PIN verification for account login and PIN change.

Admin panel protected by ADMIN_PIN.

Accounts can be closed by admin, preventing further transactions.

6. Limitations
Data stored in arrays (not persistent; lost when program ends).

Maximum of 100 accounts.

No encryption for PINs (stored as plain text).

Limited account types (Savings/Checking).

7. Possible Improvements
Use file handling or databases for persistent storage.

Encrypt PINs for better security.

Add interest calculation for savings accounts.

Implement account reopening option.

Replace arrays with classes and vectors for scalability.
