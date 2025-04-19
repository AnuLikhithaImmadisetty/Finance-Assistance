# 💸 Finance Assistance

A desktop-based portfolio management tool designed to help investors monitor and analyze their stock investments using Python. This project focuses on predicting stock prices and managing a user's portfolio efficiently, featuring a range of modules like Matplotlib, Pandas, and MplFinance for data visualization and analysis.

## 📌 Features

- 🔐 Secure login with user ID and password  
- 📈 Add, view, and sell shares in your portfolio  
- 💰 Calculate portfolio worth and gains  
- 📊 Candlestick chart visualization of stocks using MplFinance  
- 🧠 Stock price prediction logic (using Yahoo Finance)  
- 🛠 Easily modify credentials  

## 🛠️ Tech Stack

- **Language**: Python 3.10.6  
- **Libraries Used**:  
  - `matplotlib`  
  - `mplfinance`  
  - `pandas_datareader`  
  - `pickle`  
  - `sys`, `datetime`  
- **Platform**: Cross-platform (Windows, macOS, Linux)

## ⚙️ Functional Modules

- `log_in()` – Handles user authentication  
- `add_portfolio()` – Adds shares to the portfolio  
- `remove_portfolio()` – Removes shares from the portfolio  
- `save_portfolio()` – Saves the current portfolio  
- `show_portfolio()` – Displays the list of current holdings  
- `portfolio_worth()` – Calculates the current value of the portfolio  
- `portfolio_gains()` – Calculates gains/losses over time  
- `plot_chart()` – Visualizes stock performance as candlestick charts  
- `change_credentials()` – Changes user password  
- `change_id()` – Changes user ID  

## 📂 Project Structure

```
📁 Finance-Assistance/
├── credential.pkl                # Stores login credentials
├── portfolio.pkl                 # Stores portfolio data
├── financial_assistance.py      # Main source code
├── FINANCE ASSISTANCE Report.pdf # Documentation b
├── Financial Assistance - PPT # PPT 
└── README.md                    # This file
```

## 💻 How to Run

1. **Clone the repository**
```
git clone https://github.com/AnuLikhithaImmadisetty/Finance-Assistance.git
```

2. **Install required packages**
```
pip install matplotlib mplfinance pandas_datareader
```

3. **Run the application**
```
python financial_assistance.py
```

## 📸 Sample Output

Upon successful login, the terminal menu provides options such as:

- Add, remove, or save shares  
- View portfolio worth and gains  
- Plot stock data charts  
- Change credentials  

> Example stocks used: AAPL (Apple), TSLA (Tesla), GS (Goldman Sachs)

## 🧪 Future Enhancements

- Add Graphical User Interface (GUI) with Tkinter or PyQt  
- Expand to other investment types (crypto, mutual funds, real estate)  
- Use databases instead of `.pkl` for storage  
- Implement authentication and encryption for security  
- Integrate with real-time stock APIs for better performance  

## 📄 License

This project was submitted as a project at SRM University–AP. It is intended for educational purposes and personal use.
