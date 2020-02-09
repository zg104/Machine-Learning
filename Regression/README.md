# Regression

https://daviddalpiaz.github.io/r4sl/regression-overview.html

## Regression (Numeric Response)
1 What do we want? To make predictions on unseen data. (Predicting on data we already have is easy…) In other words, we want a model that generalizes well. That is, generalizes to unseen data.


2 How we will do this? By controlling the complexity of the model to guard against overfitting and underfitting.
+ Model Parameters
+ Tuning Parameters


3 Why does manipulating the model complexity accomplish this? Because there is a bias-variance tradeoff.


4 How do we know if our model generalizes? By evaluating metrics on test data. We will only ever fit (train) models on training data. All analyses will begin with a test-train split. For regression tasks, our metric will be RMSE.
