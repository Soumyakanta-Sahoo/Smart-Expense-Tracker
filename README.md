# Smart Expense Tracker

## 🚀 Overview
Smart Expense Tracker is a beginner-friendly finance app that helps users **track expenses**, categorize spending, and receive **AI-driven budget recommendations**. This project is designed to help users take control of their finances with **simple, automated, and smart tracking**.

## 🛠 Tech Stack
- **Frontend:** React Native (for mobile) / React.js (for web)
- **Backend:** Firebase / Node.js + Express / Flask
- **Database:** Firebase Firestore / MongoDB
- **AI Integration:** OpenAI API (for budget recommendations)

## 📌 Features
✅ **Add Expenses:** Users can manually log their expenses with categories (Food, Transport, Shopping, etc.).  
✅ **Auto Categorization:** AI suggests categories based on the expense description.  
✅ **Monthly Reports:** Visualize spending with charts & graphs.  
✅ **Budget Suggestions:** AI provides budget insights based on past spending patterns.  
✅ **Authentication:** Secure Google Sign-in.  

## 📂 Folder Structure
```
smart-expense-tracker/
├── frontend/             # React or React Native frontend
│   ├── src/
│   ├── components/       # UI components
│   ├── pages/            # Main app screens/pages
│   ├── assets/           # Images, icons, etc.
│   ├── App.js
│   ├── index.js
│   ├── package.json
├── backend/              # Backend API (Node.js + Express / Flask)
│   ├── models/           # Database models
│   ├── routes/           # API routes
│   ├── controllers/      # Business logic
│   ├── app.js
│   ├── package.json
├── database/             # Firebase/MongoDB setup
├── docs/                 # Documentation & setup guides
└── README.md             # Project documentation
```

## 🎯 Getting Started
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/smart-expense-tracker.git
cd smart-expense-tracker
```

### 2️⃣ Setup Frontend
```bash
cd frontend
npm install
npm start
```

### 3️⃣ Setup Backend
```bash
cd backend
npm install
node app.js
```

### 4️⃣ Setup Firebase
1. Create a Firebase project.
2. Enable Firestore and Authentication.
3. Add `firebaseConfig` to your frontend app.

## 🔥 Future Enhancements
- ✅ **OCR-based receipt scanning** 📄
- ✅ **Expense-sharing for groups** 👥
- ✅ **Dark mode support** 🌙
- ✅ **PWA Support for Web Version** 🌍

## 📜 License
This project is licensed under the **MIT License**.

---

💡 **Contributions are welcome!** Feel free to fork this repo and submit PRs! 🚀

