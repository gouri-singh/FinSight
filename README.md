FinSight — Personal Finance Management & Analytics

FinSight is a personal finance management and analytics web application designed to help users track transactions, manage budgets, monitor savings, and understand their financial patterns through interactive analytics.

Features

- 📊 Financial dashboard with key financial metrics
- 💳 Transaction management
- 💰 Budget management
- 📈 Financial analytics and spending trends
- 💡 Financial insights and anomaly detection
- 🎯 Savings tracking
- 📄 Financial reports
- 🤖 Python-powered analytics
- 🔐 User authentication
- 🗄️ SQLite database

Tech Stack

Frontend

- React.js
- Vite
- JavaScript
- CSS

Backend

- Node.js
- Express.js
- SQLite
- JWT Authentication
- bcryptjs

Analytics

- Python
- Data analysis and financial insights

Project Structure

FinSight/
│
├── backend/
│   ├── analytics/
│   ├── db/
│   ├── routes/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── App.jsx
│   │   ├── index.css
│   │   └── main.jsx
│   ├── index.html
│   ├── package.json
│   └── vite.config.js
│
├── FinSight_PRD-1.txt
├── .gitignore
└── README.md

Getting Started

1. Clone the repository

git clone https://github.com/gouri-singh/FinSight.git
cd FinSight

2. Install frontend dependencies

cd frontend
npm install

3. Start the frontend

npm run dev

The frontend will be available on the local development server.

4. Start the backend

Open another terminal:

cd backend
npm install
npm start

The backend API runs on port "5000" by default.

Application Modules

Dashboard

Provides an overview of financial activity, including income, expenses, balances, trends, and insights.

Transactions

Allows users to add and manage financial transactions.

Analytics

Provides spending analysis, category breakdowns, trends, and financial insights.

Budget

Helps users monitor and manage their budgets.

Savings

Provides savings-related tracking and information.

Reports

Provides financial reporting functionality.

Future Improvements

- Cloud database integration
- Advanced financial forecasting
- More personalized financial insights
- Improved authentication and user management
- Mobile-responsive enhancements
- Additional visualization and reporting features

Author

Gouri Singh

B.Tech — Computer Science & Engineering
