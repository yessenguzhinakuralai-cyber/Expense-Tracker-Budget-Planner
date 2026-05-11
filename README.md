FinMate is a robust Telegram-based personal finance assistant designed to help users track daily expenses, manage monthly budgets, and perform loan calculations. Built with Python 3.x, the project focuses on user-centric design, financial clarity, and data-driven insights.

---

Key Features

Dynamic Expense Tracking
Users can log expenses through an interactive flow by selecting a category such as Entertainment, Cafés, Shopping, or Utilities, and then entering the amount. All data is stored in a structured format for later analysis.

Precise Transaction Logging
Every transaction is automatically timestamped in the format YYYY-MM-DD HH:MM:SS, ensuring accurate financial history, clear chronological tracking, and audit-ready records.

Financial Statistics
The system generates comprehensive financial summaries, including daily spending reports, total income and expenses, and net balance calculations. It also supports long-term financial behavior tracking.

Mortgage and Loan Calculator
FinMate includes a built-in calculator that computes monthly annuity payments, total interest paid, and total loan repayment amount using standard financial formulas.

Smart Budget Planning
Users can define a monthly budget limit. The system tracks expenses in real time and provides alerts when the limit is exceeded, helping users maintain financial discipline.

Financial Advice System
The bot provides context-aware financial guidance, including budgeting strategies such as the 50/30/20 rule, saving recommendations, and general financial literacy insights based on real-world practices.

---

Technical Stack

The project is built using Python 3.x. It uses the pyTelegramBotAPI (Telebot) library to interact with the Telegram API. Data is stored in a JSON-based persistence system, ensuring lightweight storage, fast access, and human-readable structure. The bot follows a state-driven conversational architecture.

---

Setup and Deployment

To run the project, first clone the repository:

git clone [https://github.com/yessenguzhinakuralai-cyber/Expense-Tracker-Budget-Planner.git](https://github.com/yessenguzhinakuralai-cyber/Expense-Tracker-Budget-Planner.git)
cd Expense-Tracker-Budget-Planner

Then install the required dependencies:

pip install -r requirements.txt

Finally, start the bot:
python main.py

---

Project Purpose

FinMate was created to simplify personal financial management, improve budgeting discipline, and promote financial literacy. It also serves as a practical demonstration of Python-based Telegram bot development with structured architecture and real-world functionality.

---

Future Improvements

Planned upgrades include migration to SQLite or PostgreSQL for stronger data management, integration of data visualization dashboards, AI-based spending prediction models, multi-currency support, and a web-based admin panel for extended control and analytics.
