# Car price prediction

### Project description

The service for the sale of used cars is developing an application to attract new customers. It allows you to quickly find out the market value of your car. Historical data is at your disposal: technical specifications, complete sets and prices of cars. You need to build a model to determine the cost.

Important to the customer:
- prediction quality;
- prediction speed;
- training time.

### The purpose of the project
To build a model for predicting the cost of cars in accordance with the criteria of the customer.

### Project plan:
1. Prepare the data. Handle anomalies, remove uninformative and low-quality data, handle missing values, get rid of duplicates.
2. Train models `LinearRegression`, `RandomForestRegressor`, `CatBoostRegressor`, `LGBMRegressor`. Find optimal parameters for them.
3. Analyze models and recommend the best for customer's criteria.

### Conclusion
The LGBMRegressor model turned out to be the best model for customer's criteria: prediction quality, training time and prediction time. The value of the RMSE metric = 1535 in the test sample, the training time is 1.93 seconds, the prediction time is 0.3 seconds.

### Libraries used
`pandas`, `scikit-learn`, `LightGBM`, `CatBoost`, `NumPy`, `Matplotlib`
