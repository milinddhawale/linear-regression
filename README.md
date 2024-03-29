# What Is Mean Square Error(Loss) Function:
It is a commonly used loss function in regression problems, including linear regression.It measures the average squared difference between the predicted values and the actual values.

## The formula for mean Square Error is as follows:
MSE=1/n n∑i=1n(y pred,i−y true,i^)2

**Here:**

**n** is the number of data points in the dataset.

**y pred, i** is the predicted value for the i-th data point.

**y true, i** is the true(actual)value for the i-th data point.

The MSE is calculated by the mean (average)of the squared differences between predicted and true values for all data points. Squaring the difference penalizes larger errors more than smaller errors.

In the context of the provided code, the mean_square function calculates the mean square error between the predicted values generated by the **linear regression model** **(y_pred)** and the true values **(y_true)**. This is a crucial part of the training process, as the goal is to minimize the mean square error during optimization. The **optimization algorithm (Stochastic Gradient Descent** in this case) adjusts the model parameters **(weights and bias)** to minimize this error, resulting in a better-fitted model to the training data.

# What is Stochastic Gradient Descent (SGD) Optimizer:

Stochastic Gradient Descent (SGD) is an optimization algorithm commonly used in machine learning and deep learning for minimizing the loss function during the training of a model. The term "stochastic" refers to the fact that each iteration uses only a subset of the entire dataset (a mini-batch) rather than the entire dataset, making it more computationally efficient.
