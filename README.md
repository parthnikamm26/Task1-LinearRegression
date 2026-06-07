# House Price Prediction using Linear Regression

A machine learning project built as part of my AI/ML internship at Sumerix Global.

## About the Project

Used the California Housing Dataset to build a Linear Regression model that predicts median house prices based on features like income, location, house age, etc.

## Dataset

California Housing Dataset from scikit-learn  
20,640 samples | 8 features | no missing values

## What I did

- loaded and explored the dataset using pandas
- checked distributions, correlations and missing values
- plotted heatmap and price distribution graphs
- split data into 80% train and 20% test
- trained a LinearRegression model using scikit-learn
- evaluated using MAE, RMSE and R2 score
- plotted actual vs predicted and residual graphs
- saved the model as a pickle file

## Results

| Metric | Value |
|--------|-------|
| MAE | 0.5332 |
| RMSE | 0.7456 |
| R2 Score | 0.5758 |

The model explains about 57% of the variance in house prices. MedInc (median income) turned out to be the strongest predictor which makes sense.

## Files

- `task1_ml_linear_regression.ipynb` - main notebook with all code and plots
- `report.pdf` - project report summarizing findings
- `house_price_model.pkl` - saved trained model
- `eda_plots.png` - correlation heatmap and price distribution
- `model_plots.png` - actual vs predicted and residual plot

## Libraries Used

pandas, numpy, scikit-learn, matplotlib, seaborn

## What I learned

This was my first proper ML project. Got hands on experience with the complete ML workflow from data loading all the way to saving the model. The residual plot showed that linear regression has limitations here and a model like Random Forest would probably do better.
EOF
