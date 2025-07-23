# 💸 Financial-Agent

AI-powered financial assistant built using the Phi.AI multi-agent framework, powered by Groq LLM and tools like Yahoo Finance and DuckDuckGo. This CLI-based tool provides real-time financial data, analyst recommendations, and company news directly in your terminal.


---

# 📌 Features

Real-time stock data using Yahoo Finance

Analyst recommendations, fundamentals & company news

Uses Groq + Phi.AI for ultra-fast terminal responses

CLI-based interface — no frontend or GUI needed

Clean tabular display of stock and financial information

Modular multi-agent setup for web + finance



---

# 🚀 Getting Started

1. Create a Virtual Environment

python -m venv venv

2. Activate the Environment

On Windows:

venv\Scripts\activate

On Linux/Mac:

source venv/bin/activate


3. Install Dependencies

pip install -r requirements.txt


---

# 🔐 Set API Key (Environment Variable)

To set your OPENAI_API_KEY in terminal:

On Windows:

setx OPENAI_API_KEY "your_api_key_here"

On Linux/Mac:

export OPENAI_API_KEY="your_api_key_here"


> You can skip .env setup since environment variables are set directly from terminal.




---

# 🧠 How It Works

Finance Agent:
Fetches stock prices, financials, analyst calls, and news via YFinanceTools

Web Agent:
Searches for financial context using DuckDuckGo

Multi-Agent Coordinator:
Uses Groq to combine results from both agents and display them in terminal



---

# ▶️ Run the App

python main.py

You'll be prompted to enter a stock ticker (e.g., AAPL, TSLA, INFY) and get detailed data printed directly in your terminal.


---

# 📚 Data Sources Used

📊 Yahoo Finance

🌐 DuckDuckGo Search



---

# ⚠️ Disclaimer

'''This project is intended for educational and research purposes only.

The insights are derived from publicly available financial data.

This tool is not a substitute for professional investment advice.

Results depend on third-party APIs and should not be used for live trading decisions.

Use at your own risk. The author is not liable for financial loss.'''
