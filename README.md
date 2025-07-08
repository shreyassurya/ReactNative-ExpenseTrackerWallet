# 📱 React Native Expense Tracker Wallet

A mobile wallet app built with React Native that helps users track income and expenses in a clean, intuitive interface. It supports visual insights and budget management, making personal finance simple and accessible.

---

## 🔧 Tech Stack

- **Frontend**: React Native (Expo)
- **Backend**: Node.js, Express.js
- **Database**: Neon (PostgreSQL - serverless)
- **Version Control**: Git & GitHub

---

## 🚀 Features

- 💸 Add income and expenses
- 📊 Track real-time balances
- 🧾 View transaction history
- 🔐 Secure backend integration
- ☁️ Hosted on serverless PostgreSQL (Neon DB)

---

## 📽️ Demo

▶️ [Watch the Demo Video](https://drive.google.com/drive/folders/1MnAfjN6fXBtdFPXEzdU9uX0d8wDO1cK_?usp=drive_link)

---

## 📂 Project Structure

```

React-Native-Wallet/
├── backend/           # Express.js API
├── mobile/            # React Native frontend
├── .gitignore
├── README.md
└── ...

````

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/shreyassurya/ReactNative-ExpenseTrackerWallet.git
cd ReactNative-ExpenseTrackerWallet
````

### 2. Install Frontend Dependencies

```bash
cd mobile
npm install
npx expo start
```

### 3. Install Backend Dependencies

```bash
cd ../backend
npm install
npm start
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the `backend` folder with the following:

```
PORT=5000
DATABASE_URL=your_neon_postgres_url
```

---

## 🙌 Author

Made with ❤️ by [Shreyas Suryawanshi](https://github.com/shreyassurya)

---
