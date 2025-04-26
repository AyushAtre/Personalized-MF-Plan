# Personalized-MF-Plan

# Overview
This project analyzes the closing prices of NIFTY50 companies, identifies low-risk, high-return stocks, and simulates future investment growth using systematic investment plans (SIP).
The goal is to build a smart stock-based portfolio inspired by mutual fund strategies.

# Technologies Used
Python (Pandas, NumPy, Matplotlib)
Data Analysis
Data Visualization
Financial Metrics Calculation

# Project Workflow
Data Cleaning
Converted date column to datetime format.
Handled missing data using forward-fill.

Stock Trend Visualization
Plotted stock price trends for 50 NIFTY companies over ~1 month (August 2024).
Highlighted overall market movement.

Volatility & Growth Rate Analysis
Calculated standard deviation (volatility) for each company.
Calculated average daily % growth.

ROI Calculation
Computed Return on Investment (ROI%) between first and last dates for each stock.

Smart Mutual Fund Stock Selection
Selected stocks with:
Above-median ROI
Below-median volatility
Allocated weights inversely proportional to volatility (low-risk stocks get higher weight).

Investment Strategy Simulation
Monthly SIP: ₹5,000/month
Investment periods: 1, 3, 5, 7, and 10 years
Calculated expected future values based on average portfolio ROI.

Risk & Return Comparison
Compared mutual-fund-style stocks vs fastest growth rate stocks for both risk (volatility) and expected return (ROI).

# Conclusion:
This project demonstrates how data-driven stock selection and portfolio simulation can help investors make smarter decisions.
By combining risk (volatility) and return (ROI) metrics, it is possible to create safer and more profitable investment strategies — similar to real-world mutual funds.

# Future Improvements
Add Sharpe Ratio for risk-adjusted return comparison.
Implement Modern Portfolio Theory (MPT) for optimized weights.
Expand analysis to 6 months or 1 year data.
Add VaR (Value at Risk) calculation for risk management.
