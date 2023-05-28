# Finance Projects using Python


## ARIMA model for time series prediction
- [Code](https://github.com/KathyrnC/Finance-Projects/blob/main/ARIMA%20Model%20for%20Time%20Series%20Analysis%20and%20Prediction.ipynb)
  - Stationarity Check - Dataset: [lusmelec.csv](https://github.com/KathyrnC/Finance-Projects/blob/main/lusmelec.csv)
  - Get ACF and PACF for ARMA datasets
        - Datasets: [ARMA1.csv](https://github.com/KathyrnC/Finance-Projects/blob/main/ARMA1.csv) and [ARMA2.csv](https://github.com/KathyrnC/Finance-Projects/blob/main/ARMA2.csv)
  - Effect of p and q values on metrics (AIC, BIC, HQIC) to determine choice of model - Dataset: [arma202.csv](https://github.com/KathyrnC/Finance-Projects/blob/main/arma202.csv)
  - Application on Stock Price Data from Yahoo! Finance
  - Data Smoothing Techniques: Exponential Smoothing, Lowess Smoothing, Convolution Smoothing

## Credit scoring modelling
Objective: Develop a credit scorecard
- [Code](https://github.com/KathyrnC/Finance-Projects/blob/main/Credit%20Scoring.ipynb)
  - Exploratory Data Analysis and Treating Missing Data
  - Calculation of Weight of Evidence (WOE), Information Value (IV), and Monotonic values on all features to determine whether to incldue or reject feature in developing scorecard model
  - Manual Scorecard Generation (WOE matrix transformation and Logistic Regression)
  - Model Performance Evaluation
- Dataset: [loan_train.CSV](https://github.com/KathyrnC/Finance-Projects/blob/main/loan_train.csv)


## Monte carlo simulation on structured product returns
Problem: Probability computation of early redemption of [structured product](https://drive.google.com/file/d/1kQvQsjlCOoIERHARx8cNbGTJACO9IJRN/view), given that the qualification for early redemption on each early redemption date below is that each equity in the product mush be at least 85% of it's value on the validation date:
  - 1. 20thovember 2019
  - 2. 20th May 2020
  - 3. 20th November 2020
  - 4. 20th May 2021

[Code](https://github.com/KathyrnC/Finance-Projects/blob/main/Monte%20Carlo%20Simulation%20on%20Structured%20Products.ipynb)
- Extract Stock Price Data from Yahoo! Finance
- Average and Standard Deviation computation
- Monte Carlo simulations on each equity to each early redemption date using the Brownian Motion model
- Computation of Probability of redemption on each valuation date.


