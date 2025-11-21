 📈 Mutual Fund / Portfolio Analysis Using NIFTY50 Stock Data

This project performs an end-to-end Mutual Fund style portfolio analysis using daily closing prices of NIFTY50 stocks.
The analysis includes data cleaning, return calculation, risk metrics, correlation study, portfolio construction, rolling volatility, drawdown analysis, and efficient frontier simulation.

It is designed to simulate how mutual fund research teams evaluate performance, risk, and portfolio efficiency.

📂 Dataset

File: nifty50_closing_prices (1).csv

Time Period: 2024–2025

Frequency: Daily

Columns:

Date

49 NIFTY50 stock symbols

Values: Daily closing prices (float)

🎯 Project Objectives

The goal of this project is to:

Analyze the performance of NIFTY50 stocks

Evaluate the risk and volatility of each stock

Identify top performing stocks

Explore correlation & diversification potential

Build an equal-weight mutual fund portfolio

Measure drawdowns and rolling volatility

Simulate random portfolios to visualize the efficient frontier

Provide insights useful for mutual fund research & portfolio optimization

🛠 Technologies Used
Area	Tools
Programming	Python 3
Data Handling	pandas, numpy
Visualization	matplotlib
Portfolio Analytics	numpy, random simulations
Environment	Jupyter Notebook / Any Python IDE
🔍 Analysis Workflow
✔ 1. Data Cleaning

Convert Date to datetime

Handle missing values using forward fill

Sort by date

Structure time-series data for analysis

✔ 2. Return Calculations

Daily Returns

Cumulative Returns

Annualized Returns

Annualized Volatility

Sharpe Ratio (risk-adjusted return)

✔ 3. Stock Ranking

Top 6 stocks based on cumulative returns

Performance vs volatility

Return distribution analysis

📊 Visualizations Generated
1️⃣ Cumulative Returns (Top 6 Stocks)

Shows how the top-performing stocks have grown over time.

2️⃣ Correlation Heatmap (All NIFTY50 Stocks)

Used to understand diversification potential and market clustering.

3️⃣ Risk vs Return Scatter Plot

Annual Return → Y-axis
Annual Volatility → X-axis
Identifies efficient and risky stocks.

4️⃣ Annual Returns Histogram

Shows distribution of returns across all NIFTY50 stocks.

5️⃣ Rolling 60-Day Volatility Chart

Evaluates risk trends over time for top stocks.

6️⃣ Equal-Weight Portfolio Drawdown Curve

Measures downsides and worst-case behaviour of diversified portfolio.

7️⃣ Efficient Frontier Simulation

Scatter chart of 2000 simulated random portfolios:
Shows trade-off between risk and return.

🧮 Key Metrics Computed
Metric	Description
Daily Returns	% change day-to-day
Cumulative Returns	Growth since start
Annual Return	Yearly expected return
Volatility	Risk measure
Sharpe Ratio	Return per unit of risk
Rolling Volatility	Time-varying risk
Drawdown	Fall from previous highs
