# ML Activity 2: Simple House Price Prediction (Linear Regression)

## Activity Description
Build a simple Linear Regression model that predicts house price from house size, evaluate it, and visualize the results.

## Dataset
- **House Prices dataset** (`house-prices.csv`), source: PASTE_DATASET_SOURCE_LINK_HERE
- 128 rows x 8 columns, CSV
- Input feature: `SqFt` | Target: `Price`

## Work Completed
- Inspected the data (shape, data types, missing values, duplicates, summary statistics)
- Selected `SqFt` as the feature and `Price` as the target (`Home` ID column not used)
- Scatter plot of size vs price
- 80:20 train-test split (102 train, 26 test)
- Trained a Linear Regression model
- Compared actual and predicted prices
- Evaluated with MAE, MSE, RMSE and R²
- Actual vs Predicted plot
- Predicted the price of a new 2,000 sq ft house

## Key Results
- Equation: Price = -17,889.36 + 74.04 x SqFt
- MAE: 15,945.55 | MSE: 415,765,840.64 | RMSE: 20,390.34 | R²: 0.295
- Predicted price for 2,000 sq ft: about $130,181
- Size is useful but explains only part of the price variation

## Files
- `ML_activity_2.ipynb`: notebook
- `house-prices.csv`: dataset

## Faculty Profile
[Princy Verma on GitHub](https://github.com/Princy2129)

## Acknowledgement
This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: [https://github.com/Princy2129](https://github.com/Princy2129)
