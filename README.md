# 🏦 Python Interactive Banking System

A command-line banking application built with Python that allows users to create customers and bank accounts, deposit and withdraw money, transfer funds between accounts, check balances, and view transaction history.

This project demonstrates my progress in **Python, Object-Oriented Programming (OOP), JSON data persistence, file handling, and application design**.

## ✨ Key Features

- **Customer Creation** — Create and store customer profiles within the banking system.
- **Bank Account Creation** — Create accounts associated with customers.
- **Deposits** — Deposit money into an account and update the account balance.
- **Withdrawals** — Withdraw money while validating that sufficient funds are available.
- **Money Transfers** — Transfer money from one bank account to another with balance validation.
- **Balance Checking** — Check the current balance of a specific account.
- **Account Details** — View account information and its associated owner.
- **Customer Management** — View customers registered in the banking system.
- **Account Management** — View existing bank accounts.
- **Transaction History** — Record and display deposits, withdrawals, and transfers.
- **Persistent Data Storage** — Save customers, accounts, balances, and transaction information to a JSON file.
- **Data Loading** — Load previously saved banking data when the application starts.

## 🏗️ Architecture & Design

The project uses **Object-Oriented Programming (OOP)** to organize the banking system into separate classes.

### Class Structure

```text
Bank
├── Customers
├── Accounts
├── Customer Management
├── Account Management
├── Banking Operations
├── Transaction History
└── JSON Data Persistence

Customer
├── Customer ID
└── Customer Name

BankAccount
├── Account Number
├── Owner
├── Private Balance
└── Transaction History
