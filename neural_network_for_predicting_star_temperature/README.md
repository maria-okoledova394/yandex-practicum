# Neural network for predicting star temperature

### Project description

The observatory wants to introduce machine learning technologies to predict the temperature of stars.

The observatory's database contains the characteristics of 240 stars that have already been studied.

### The purpose of the project
To develop a neural network that will predict the absolute temperature on the surface of a star. The RMSE metric should be less than 4,500.

### Project plan:
1. EDA. Prepare the data. Handle anomalies, missing values, duplicates.
2. Create a simple neural network and train it.
3. Make improvements to the neural network.
3. Analyze models and recommend the best for customer's criteria.

### Conclusion
I built the base model of a neural network, found optimal number of hidden layers, neurons, activation function, initialization of weights.
Improved the RMSE of the model by tuning the model parameters. The RMSE = 3658 of the improved model is on the test data. It's better than the required RNSE of 4500, however, the model performs well in predicting low temperatures and less effectively with high temperatures.

### Libraries used
`pandas`, `PyTorch`, `scikit-learn`, `NumPy`, `Matplotlib`
