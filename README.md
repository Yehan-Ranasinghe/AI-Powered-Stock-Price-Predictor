# AI-Powered-Stock-Price-Predictor

## Overview
This project is a simple **AI-Powered Stock Price Predictor** that fetches real-time stock data, trains a **Linear Regression** model, and predicts future stock prices. The model is built using **Python**, leveraging data science libraries like **yFinance, Scikit-Learn, Pandas, and Matplotlib**.

## Features
- Fetches **real-time stock data** from Yahoo Finance
- Prepares data by converting dates into numerical values
- Trains a **Linear Regression Model** to predict stock prices
- Evaluates model performance with **Mean Absolute Error (MAE)** and **Mean Squared Error (MSE)**
- **Visualizes actual vs. predicted prices** using Matplotlib
- Predicts **future stock prices** based on historical trends

## Tech Stack
- **Python**
- **yFinance** (Fetch stock data)
- **Scikit-Learn** (Machine Learning)
- **Matplotlib & Seaborn** (Data Visualization)
- **Pandas & NumPy** (Data Processing)

## Installation & Usage
### Prerequisites
Make sure you have **Python 3.x** installed. Then install the required dependencies:
```sh
pip install yfinance pandas numpy scikit-learn matplotlib seaborn
```

### Running the Script
```sh
python stock_price_predictor.py
```
The default stock symbol is **AAPL (Apple Inc.)**. You can modify the `ticker` variable in the script to predict other stocks.

## Example Output
```
MAE: 2.45
MSE: 6.72
Future Predictions:
Day 366: $145.67
Day 367: $146.23
...
```
A plot will also be displayed showing actual vs. predicted stock prices.

## Future Enhancements
- Add support for **more advanced ML models** like Random Forest or LSTMs
- Implement **real-time stock price monitoring**
- Create a **Flask API** to expose predictions via a web interface

## License
This project is open-source under the **MIT License**.

## Author
[Yehan Ranasinghe](https://github.com/your-github)


