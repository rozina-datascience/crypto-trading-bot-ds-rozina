# 📊 Crypto Trading Bot – DS Rozina

**Simulated Binance Futures Trading Bot** with sentiment-based profitability analysis using Python and Google Colab.

---

## 📌 Project Overview

This project combines **market sentiment analysis** with **Binance Futures trading simulation** to explore whether public sentiment (Fear/Greed Index) correlates with trading profitability.

### 🔹 Part 1: Sentiment-Based Profitability Analysis
- Loaded and cleaned real historical trading logs (`historical_data.csv`)
- Merged with daily Fear & Greed Index sentiment data
- Analyzed average Closed PnL by sentiment classification
- Visualized results using Seaborn & Matplotlib
- Exported a bar chart: `outputs/pnl_by_sentiment.png`

### 🔹 Part 2: Binance Futures Trading Bot (Simulated)
- Developed a Python script using the `python-binance` library
- Accepts CLI input for symbol, order type, and quantity
- Simulates placing market/limit orders using **sample API keys**
- Logs order simulation to `bot.log`

---

## 🧪 Technologies Used
- **Python** (Pandas, Seaborn, Matplotlib, Logging)
- **Google Colab**
- **Binance API (Simulated)**
- **Command Line Interface (CLI)**

---

## 📁 Repository Structure

ds_rozina/
├── notebook_1.ipynb # Colab notebook (EDA + charts)
├── ds_report.pdf # Report with summary, code, and plots
├── bot.py # Simulated Binance Futures bot
├── bot.log # Log file created after simulation
├── README.md # Project overview
├── CSV_files/
│ ├── historical_data.csv
│ └── fear_greed_index.csv
├── outputs/
│ └── pnl_by_sentiment.png

yaml
Copy code

---

## 🚨 Disclaimer

⚠️ This bot **does NOT place real orders**.  
It is for **educational and assignment purposes only**, and uses **sample API keys**.

---

## 📬 Author

**Rozina Mohsin Pathan**  
[GitHub Profile](https://github.com/rozina-datascience)
GitHub Repository: https://github.com/rozina-datascience/crypto-trading-bot-ds-rozina
🔗 GitHub Link:(https://github.com/rozina-datascience/crypto-trading-bot-ds-rozina)
