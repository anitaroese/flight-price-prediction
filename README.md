# ✈️ Flight Price Prediction: When to Buy

**Status:** 🚧 In progress (expected completion: November 2026)

## Overview
Airfare changes constantly, which makes it hard to know the best time to buy a ticket. This project uses machine learning to predict U.S. domestic flight prices and recommend whether a traveler should **buy now** or **wait**.

## Goals
1. **Predict ticket prices** with linear regression
2. **Recommend when to buy** with logistic regression, labeling each fare as "buy now" or "wait"

## Dataset
**[Flight Prices](https://www.kaggle.com/datasets/dilwong/flightprices)** (Kaggle)
- One-way U.S. domestic flight fares listed on Expedia
- Collected between April 16, 2022 and October 5, 2022
- Includes search date, flight date, origin and destination airports, fare, airline, number of stops, travel duration, and seats remaining

> The dataset is too large to store on GitHub. Download it from Kaggle using the link above.

## Approach
- **Data cleaning:** handle missing values, remove duplicates, and work with a manageable sample of the data
- **Feature engineering:**
  - Days between search date and flight date (booking lead time)
  - Route (origin → destination)
  - Airline
  - Day of week and month of travel (seasonality)
  - Nonstop vs. connecting flights
- **Models:**
  - Linear regression to forecast total fare
  - Logistic regression to classify fares as "buy now" vs. "wait"
- **Evaluation:**
  - Regression: RMSE, MAE, R²
  - Classification: accuracy, precision, recall, F1-score, confusion matrix

## Tools
Python · Pandas · scikit-learn · Matplotlib · Google Colab

## Project Structure
```
flight-price-prediction/
├── notebooks/   # Google Colab notebooks
└── README.md
```

## Results
*Coming soon.*

## Author
**Anita Roese**, Computer Science, Xavier University of Louisiana
[LinkedIn](https://linkedin.com/in/anitaroese) · [GitHub](https://github.com/anitaroese)
