# Comparative evaluation of different Value at Risk estimations
This project models conditional volatility and estimates Value-at-Risk (VaR) for a portfolio of six major European indices (CAC40, DAX, SMI, FTSE100, IBEX35, MDAXI) using SAS.

## Structure

* `data/` – Folder that contains price of the stock indices
* `memoire_S2` – script SAS of the volatility modeling and VaR computation
* `memoire_S2.sas.pdf` – Report of the project with results, litterature review and backtesting

## Methods

* **GARCH(1,1) Student-t** 
* **EWMA** 
* **Kalman Filter (stochastic volatility)**

## Usage
1. Load data from `data/` in SAS
2. Run scripts in `code/`
