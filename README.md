# JAX-Linear-Regression
This project leverages the power of JAX, a high-performance numerical computing library, to implement a simple linear regression model using gradient descent. The objective is to generate synthetic data, perform linear regression, and visualize the optimization process through loss plotting.

# Key Features:

## Data Generation:

Generates synthetic data that simulates a linear relationship with added noise.
Provides a realistic dataset for testing the linear regression model.
Linear Regression Model:

Implements a linear regression model to fit the generated data.
Uses a mean squared error (MSE) loss function to evaluate the model's performance.
Gradient Descent Optimization:

Utilizes gradient descent to iteratively update model parameters (slope and intercept).
Computes gradients using JAX's automatic differentiation capabilities for efficient optimization.
Loss Calculation and Visualization:

Calculates the loss at each epoch during the training process.
Plots the loss over epochs to visualize the optimization progress.
## Performance Metrics:

Provides the final optimized slope and intercept values.
Outputs the final mean squared error (MSE) to assess model accuracy.
## Technologies Used:
JAX: For high-performance numerical computing and automatic differentiation.
Matplotlib: For visualizing the loss over epochs.
Usage:
## Run the Script:

Execute the provided Python script to generate synthetic data, train the linear regression model, and visualize the results.

## Interpret the Results:

Review the printed optimized slope, intercept, and final loss.
Analyze the loss plot to understand the model's convergence behavior.
