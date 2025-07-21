# Motorcycle Price Estimator

This project uses historical eBay listing data to estimate whether a motorcycle for sale is fairly priced. By training a regression model on features such as mileage, model year, and make, we can predict expected prices and compare them to new listings.

## Features

- Cleans and preprocesses real eBay motorcycle listings
- Trains a Random Forest model to predict motorcycle prices
- Evaluates performance with MAE, RMSE, and R²
- Includes visualisations of predictions and feature importances

## Key Tools

- Python (pandas, scikit-learn, seaborn, matplotlib)
- One-hot encoding for categorical features
- Random Forest Regression

## Future Ideas

- Include depreciation analysis by year, mileage or engine size
- Include data for eBay auctions, not just "Buy it now" option
- Use NLP to glean more information from the Condition Description, and to tidy up the Make and Colour columns
