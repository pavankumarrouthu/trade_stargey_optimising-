# trade_stargey_optimising-
# 📈 Trading Strategy Optimizer

This project implements and backtests a simple **SMA crossover trading strategy** using mock historical stock data. It identifies buy and sell signals based on the relationship between short-term and long-term moving averages.

## 🚀 Features

- Generates mock stock price data using random walk
- Calculates 20-day and 50-day Simple Moving Averages (SMA)
- Identifies buy/sell signals based on SMA crossovers
- Visualizes equity curves with clear entry/exit markers
- Outputs CSV of results for further analysis

## 💻 Tech Stack

- Python
- pandas, numpy, matplotlib
- Jupyter Notebook

## 📊 Example Output

![Equity Curve](plots/equity_curve.png)

## 🗂️ Project Structure

trading-strategy-optimizer/
├── trading_strategy_optimizer.ipynb
├── sample_stock_data.csv
├── plots/
│ └── equity_curve.png
└── README.md
