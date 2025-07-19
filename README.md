# 🏦 Simple ATM Simulation in Python

This project is a **console-based ATM system** built in Python. It simulates basic banking operations like login authentication, deposit, withdrawal, and balance checking using file-based storage (`balance.json`).

## 📂 Project Structure

- `validation.py` – Handles PIN login and authentication.
- `account_logic.py` – Core banking logic: deposit, withdraw, check balance.
- `balance.json` – Stores the current account balance.
- `display_menu.py` – (Expected) menu display logic for ATM interface.

## ✅ Features

- 🔐 Secure login using a 4-digit PIN with limited attempts.
- 💸 Deposit and withdraw money from your virtual account.
- 📊 Check balance after every transaction.
- 📁 Uses a JSON file to persist balance data between sessions.

## ⚙️ How to Run

1. Make sure `balance.json` file exists with sample data like:
   ```json
   {
     "balance": 1000
   }
   ```

2. Run the program using:
   ```bash
   python validation.py
   ```

3. Follow on-screen prompts for login and transactions.

## 🚫 Notes

- The login PIN is hardcoded as `"1234"` (with a space in the current version—may need correction).
- Incorrect PIN attempts will eventually lock the account.
- Logic in deposit/withdraw may need fixes for arithmetic signs and file handling.

## 💡 To Improve

- Fix minor bugs in withdrawal/deposit logic.
- Add user input validation and proper exception handling.
- Separate UI logic from business logic for
