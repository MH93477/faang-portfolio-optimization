# FAANG Portfolio Optimization using Python 

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=flat&logo=Jupyter&logoColor=white)
![PyPortfolioOpt](https://img.shields.io/badge/PyPortfolioOpt-Optimization-blue)

This project evaluates and optimizes a portfolio of FAANG stocks using modern portfolio theory.

##  Objective
- Calculate expected return and Sharpe ratio of an equally-weighted portfolio
- Construct a minimum volatility portfolio
- Build a portfolio that maximizes the Sharpe ratio using PyPortfolioOpt

##  Tools & Libraries
- Python
- pandas, NumPy, matplotlib
- PyPortfolioOpt

##  Key Results
###  Equal-weight Portfolio
- **Expected Daily Return**: `0.0009366970530650012`
- **Annualized Sharpe Ratio (Rf = 0%)**: `0.7221868020795013`

###  Minimum Volatility Portfolio
AAPL 0.39842
AMZN 0.14911
GOOGL 0.38290
META 0.00000
NFLX 0.06957

- **Annualized Volatility**: `0.3030736711547463`

###  Maximum Sharpe Ratio Portfolio
AAPL 0.78744
AMZN 0.00000
GOOGL 0.19970
META 0.00000
NFLX 0.01286

- **Annualized Sharpe Ratio**: `0.8821809421501468`

##  Files
- `FAANG_Portfolio_Optimization.ipynb` — Full notebook
- `faang_stocks.csv` — Historical stock data (2020–2023)

##  Dataset Source
- Provided by DataCamp

##  Certification
Completed as part of [Finance Fundamentals in Python Track on DataCamp]
