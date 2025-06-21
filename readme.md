### 💼 Budget – Personal Finance & Advisory Tool
FinMate is a modular Flask-based web app designed to help users track expenses, manage investments, and receive smart financial advice — all with an intuitive UI, including a gamified card input system for enhanced user engagement.

## 🔍 Brief Summary
FinMate is a lightweight personal finance assistant that lets users:

- **Log their day-to-day expenses 🧾**

-**Track and analyze their investment portfolio 📊**

-**Get AI-style smart investment suggestions based on risk profiles 📈**

-**Engage with gamified, icon-based selection for budgeting categories 🎮**

-**It's ideal for students, young professionals, and anyone looking to build better financial habits with a touch of interactivity.**

## ✨ Features
-**✅ Expense Tracker: Add, view, and categorize daily expenses.**

-**🧠 Smart Advisor: Suggests investment strategies based on savings and risk appetite.**

-**📋 Portfolio Manager: Track multiple investment types (FDs, stocks, mutual funds, gold, etc.).**

-**🃏 Gamified UX: Card-based interactive input for selecting expenses and goals.**

-**📅 Date-wise logging with summaries.**

-**📦 Modular, scalable Flask project structure.**

## 🛠️ Tech Stack Used
Layer	Technology
Backend	Flask (Python)
Frontend	HTML5, CSS3, Jinja2
Styling	Bootstrap, Custom CSS
Scripting	Vanilla JavaScript
Optional DB	PostgreSQL / SQLite (future-ready)

## 🚧 Challenges Faced
Challenge	Solution Implemented
Designing a clean, modular structure	Split app into templates per module (expense, advisor...)
No DB initially → state reset on reload	Used in-memory storage, but kept code DB-ready
Making input fun and engaging	Built a card-flipping UI with JS + CSS
Managing category selection cleanly in HTML	Used Set() + hidden inputs to track selected cards

## 🧩 How We Overcame Them
Modularized the routes and templates to scale easily.

Used JS + CSS transitions for card-style gamified selection.

Kept core logic decoupled from storage so DB integration is smooth later.

Focused on accessibility — minimal dependencies, mobile-friendly layout.

## 🚀 Steps to Run the Project
-**1️⃣ Clone the repository**
bash
Copy
Edit
git clone https://github.com/your-username/finmate.git
cd finmate
-**2️⃣ Set up a virtual environment**
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
-**3️⃣ Install dependencies**
bash
Copy
Edit
pip install -r requirements.txt
-**4️⃣ Run the Flask app**
bash
Copy
Edit
python app.py
-**5️⃣ Open in your browser**
arduino
Copy
Edit
http://localhost:5000
## 📂 Directory Structure (Important Files)
pgsql
Copy
Edit
finmate/
│
├── app.py
├── requirements.txt
├── static/
│   ├── css/
│   └── js/
└── templates/
    ├── index.html
    ├── expense/
    │   ├── add.html
    │   └── list.html
    ├── advisor/
    │   └── recommend.html
    ├── portfolio/
    │   ├── add.html
    │   └── view.html
    └── select/
        └── select_expenses.html
## 📌 Future Enhancements
-**🔐 User login and session-based dashboards**

-**📊 Graph-based summaries using Chart.js or Plotly**

-**🧠 Real ML-powered advisory engine**

-**🏦 Database-backed persistence (PostgreSQL or SQLite)**

-**📱 Responsive mobile-first PWA version**

## 🤝 Contributors
Created by Arka — built with ❤️ for a better financial future!
