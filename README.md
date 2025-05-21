TCS Stock Analysis
Python
License
A Python project to analyze TCS stock data, visualize trends, and predict closing prices using Linear Regression and Moving Average.
Overview
This project processes historical TCS stock data, performs exploratory data analysis (EDA), engineers features, and builds predictive models. It uses basic libraries (pandas, numpy, matplotlib, seaborn, sklearn).
Features
Preprocessing: Handles missing values and outliers.

EDA: Visualizes price trends, moving averages, and correlations.

Features: Adds daily returns, lag prices, and date-based features.

Models: Linear Regression and Moving Average prediction.

Evaluation: Metrics include MSE, MAE, and R-Squared.

Dataset
TCS_stock_data.csv includes:
Date, Open, High, Low, Close, Volume, Dividends, Stock Splits

Source: Download from Yahoo Finance.

Installation
Clone the repo:

git clone https://github.com/your-username/tcs-stock-analysis.git
cd tcs-stock-analysis

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

Add TCS_stock_data.csv to the project root.

Usage
Open TCS_Stock_Analysis.ipynb in Jupyter Notebook:

Run cells sequentially to:
Load and preprocess data

Perform EDA

Train and evaluate models

Save the Linear Regression model

Project Structure

tcs-stock-analysis/
├── TCS_stock_data.csv          # Dataset (user-provided)
├── TCS_Stock_Analysis.ipynb    # Jupyter Notebook
├── TCS_Linear_Regression.pkl   # Saved model (generated)
├── README.md                   # Documentation

Results
EDA: Strong correlation between price columns; moving averages show trends.

Models: Linear Regression achieves high R-Squared (~0.99); Moving Average is a simple baseline.

Visualizations compare actual vs. predicted prices.
