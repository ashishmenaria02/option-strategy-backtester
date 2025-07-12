# 📈 Option Strategy Backtester

A Python-based tool to **backtest common option trading strategies** like Straddle, Strangle, and Bull Call Spread using historical data.

---

## 🔧 Features

- Choose strategy logic (ATM/OTM buy/sell)
- PnL calculation based on entry/exit time
- Works with Bank Nifty or Nifty data
- Modify SL/Target/Time easily

---

## 🚀 How It Works

- Sample data: `sample_data.csv`  
- Strategy Example:  
  - Buy ATM Call  
  - Sell OTM Call (100 pts away)  
  - Entry at 9:20 AM, Exit at 3:15 PM  
- Calculates Profit/Loss

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- Matplotlib (optional for charts)

---

## 🖥️ Example Output

```bash
Profit/Loss: ₹30
