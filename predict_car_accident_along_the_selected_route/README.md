# Predict car accident along the selected route

### Project description

The task is to create an accident prediction system for a carsharing company. 

After the driver has booked a car, got in the car and chosen a route, the system should assess the level of risk. If the risk level is high, the driver will see a warning and recommendations along the route.

### The purpose of the project
To understand whether it is possible to predict an accident based on historical data from one of the regions.

### Project plan:
1. Statistical analysis of accident factors.
2. Select the necessary factors for analysis and building the model. Prepare data based on customer's requirements.
2. Create different learning models.
3. Analyze the results, compare quality metric, time of work, features importance.
4. Conclude is it possible to create an accident risk assessment system.

### Conclusion
The best model is CatBoostClassifier model with f1 = 0.69 in the test sample.

The current model predicts slightly better than the basic one. On this dataset, the task of creating an adequate risk assessment system cannot be resolved. Perhaps it is possible to create good accident forecasting system if add features: the speed of the car at the time of the accident, age, experience of the driver.

### Libraries used
`pandas`, `scikit-learn`, `CatBoost`, `Matplotlib`, `SQLAlchemy`, `seaborn`
