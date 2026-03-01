# BalanceBee-Low-code-no-code
# 💰 Balance Management System

A personal finance tracking application built using **Zoho Creator** and **Deluge scripting**.

This application helps users manage their cash and account balances, track daily expenses, generate monthly reports, and send automated payment reminders to friends.

## 📌 Features

### 👤 User Profile Management
- Add user details
- Maintain cash balance
- Maintain account balance
- Automatic total balance calculation

### 💸 Expense Tracking
- Add daily expenses
- Choose payment mode (Cash / Account)
- Automatic balance deduction
- Edit & delete expenses with recalculation
- Real-time balance updates

### 📊 Reports & Dashboard
- Monthly expense summary
- Category-wise expense analysis
- Cash vs Account spending comparison
- Visual charts & graphs
- Pending payments overview

### 🔔 Friend Payment Reminder System
- Add friend details
- Track amount owed
- Send automatic reminder emails
- 7-day recurring reminders
- Mark as completed when paid

### 📈 Budget Monitoring
- Track monthly expenses
- Monitor spending trends
- Budget usage alerts

---

## 🛠️ Built With

- **Zoho Creator**
- **Deluge Script**
- **Zoho Workflows**
- **Zoho Scheduler**
- **Zoho Zia AI (Concept Based)**

---

## 🧠 Workflow Logic Overview

### 1️⃣ User Initialization
- On user creation:
  - `Total Balance = Cash Balance + Account Balance`

### 2️⃣ Expense Creation
- Deduct amount from selected payment mode
- Update total balance

### 3️⃣ Expense Update
- Restore old amount
- Deduct new amount
- Recalculate total balance

### 4️⃣ Expense Deletion
- Add amount back to correct balance
- Update total balance

### 5️⃣ Friend Reminder Automation
- First reminder sent when record is created
- Automatic 7-day recurring reminders
- Stops when status is marked "Completed"

---

## 🏗 Application Structure

### Forms
- Users
- Expense
- Friend Reminder

### Reports
- Monthly Summary
- Category-wise Expenses
- Cash vs Account Analysis
- Pending Amount Tracker

---

## 🔐 Security

- Role-based access control
- Each user can access only their data
- Workflow automation for data consistency

---

## 📱 Accessibility

- Web-based application
- Mobile compatible via Zoho Creator app
- Cloud hosted

