
# Indus Tower Stock Price Prediction using Simple Linear Regression

## Project Overview

This project builds a stock price prediction model for **Indus Tower Ltd. (INDUSTOWER.NS)** using **Simple Linear Regression (SLR)**. The goal is to predict the **next day's closing stock price based on today's closing price** while validating all key assumptions of regression modeling.

The project demonstrates a complete workflow including:

- Data collection
- Feature engineering
- Model training
- Model evaluation
- Regression assumption testing
- Stock price prediction

---

## Dataset

Source: Yahoo Finance

Ticker:
INDUSTOWER.NS

Data Used:
- Daily closing prices
- 3 months historical data
- Daily interval

---

## Model

Model Used:

Simple Linear Regression

Equation:

Y = β0 + β1X + ε

Where:

Y = Next Day Closing Price  
X = Today's Closing Price

---

## Project Workflow

1. Download stock data using Yahoo Finance API
2. Create target variable (Next Day Close)
3. Split dataset into training and testing sets
4. Train Simple Linear Regression model
5. Evaluate model performance
6. Test regression assumptions
7. Predict next day stock price

---

## Model Evaluation Metrics

The model is evaluated using:

- R² (Coefficient of Determination)
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

These metrics help determine the predictive accuracy of the regression model.

---

## Regression Assumptions Tested

The following statistical assumptions are validated:

1. Linearity
2. Normality of residuals
3. Homoscedasticity
4. Independence of errors

Diagnostic tests used include:

- Shapiro-Wilk Test
- Q-Q Plot
- Residual Plot
- Durbin-Watson Statistic

---

## Libraries Used

- pandas
- numpy
- yfinance
- scikit-learn
- matplotlib
- statsmodels
- scipy

---

## Output

The model predicts the **next day's closing stock price** using the latest available closing price.

---

## Conclusion

The project demonstrates how **Simple Linear Regression can be used to model short-term stock price relationships**. It also highlights the importance of validating regression assumptions to ensure statistical reliability.

While the model captures short-term patterns, stock prices are influenced by many external factors. More advanced machine learning or time-series models can further improve prediction accuracy.

---
