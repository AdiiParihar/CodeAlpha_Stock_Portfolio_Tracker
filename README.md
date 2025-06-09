# 📈 Stock Portfolio Tracker (Python)

A simple command-line based stock portfolio tracker built with Python.

This tool allows users to input their stock holdings (e.g., AAPL, TSLA), calculate the total investment based on predefined prices, and view a neat summary of their portfolio.

---

## 💡 Features

- 🧾 Input your stock names and quantities
- 💰 Calculates total investment based on fixed prices
- 📊 Displays a clean portfolio summary
- ✅ User-friendly menu using `match-case` control flow
- 🔧 Easy to expand with real-time data, file I/O, or profit/loss tracking

---

## 🚀 How to Use

1. **Run the script**
    ```bash
    python portfolio_tracker.py
    ```

2. **Choose an option**:
    - `1` to input stock details
    - `2` to view portfolio summary and balance
    - `3` to exit

---

## 🛠 Technologies Used

- Python 3.x
- Core Python concepts:
  - `dict` for data storage
  - `functions`, `loops`, `match-case`
  - `input()` for CLI interaction

---

## 📦 Sample Stock Price Database (can be edited)

```python
stock_prices = {
    "AAPL": 180,
    "TSLA": 250,
    "GOOG": 120,
    "MSFT": 290
}
