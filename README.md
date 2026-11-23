# 💳 Banker App

Banker is a personal finance management app built with **Flutter**.  
It automatically reads and analyzes your SMS messages from the bank, then extracts and categorizes your transactions to provide clear insights into your spending habits.  

With Banker, you can easily track your monthly expenses, set a daily spending limit based on your budget, and visualize your financial data in a clean and simple interface.

---

## ✨ Features

- 📩 **Automatic SMS Parsing**  
  Reads incoming bank messages and extracts transaction details.

- 📊 **Monthly Expense Reports**  
  Summarizes your spending for the current month and last 30 days.

- 💡 **Smart Categorization**  
  Transactions are grouped into categories such as **purchases, transfers, withdrawals, online payments**, and more.

- ⏳ **Daily Limit Tracking**  
  Helps you stay within your budget by monitoring your daily spending cap.

- 📁 **Expense History**  
  Navigate through past weeks and months to review old reports.

- 🧩 **Custom Parsing Rules**  
  Define a rule per bank (sender, keywords, amount/store/date positions) so any SMS format can be parsed.

- 🗓️ **Weekly Budget**  
  Optional weekly budget on top of the monthly and daily limits, with a week-by-week breakdown.

- 🐷 **Monthly Savings**  
  Set aside an amount each month, track the savings balance and withdraw when needed.

- 🔁 **Transfers & Balance Correction**  
  Incoming and outgoing transfers are tracked separately, and the balance can be reconciled with the bank.

- 💾 **Backup & Restore**  
  Export all data to a JSON file and restore it on a new phone.

---

## 📷 Screenshots

| Home | Home (more) | Spending by Category |
|:---:|:---:|:---:|
| <img src="screenshots/01-home-dashboard.png" width="230"> | <img src="screenshots/02-home-dashboard-bottom.png" width="230"> | <img src="screenshots/03-monthly-categories.png" width="230"> |
| **Transactions** | **Weekly Budget** | **Savings** |
| <img src="screenshots/04-all-transactions.png" width="230"> | <img src="screenshots/05-weekly-budget-breakdown.png" width="230"> | <img src="screenshots/06-savings.png" width="230"> |
| **Outgoing Transfers** | **SMS Parsing Rule** | **Backup & Settings** |
| <img src="screenshots/07-outgoing-transfers.png" width="230"> | <img src="screenshots/08-add-sms-parser.png" width="230"> | <img src="screenshots/09-expenses-settings-backup.png" width="230"> |
| **First-run Setup** | | |
| <img src="screenshots/10-first-run-setup.png" width="230"> | | |

> Screenshots use sample data.

---

## 🛠️ Tech Stack

- **Framework:** [Flutter](https://flutter.dev/)  
- **Language:** Dart  
- **State Management:** Bloc  
- **Database:** Local SQLite (for storing expenses and settings)  
- **Notifications:** Local notifications for budget alerts  

