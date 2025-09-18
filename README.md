Linear Regression with Gradient Descent
Overview

This project demonstrates linear regression using batch gradient descent and stochastic gradient descent (SGD). Input features and target values are scaled to improve model convergence and performance.

Key Features

Scales features and target values to a consistent range for faster and more stable training.

Implements batch gradient descent, updating weights and bias using the entire dataset each iteration.

Implements stochastic gradient descent (SGD), updating weights and bias using a single random sample per iteration.

Tracks mean squared error (MSE) during training to monitor learning progress.

Supports converting scaled predictions back to the original range for interpretation.

Visualizes cost versus epoch to show how the model improves over time.

Usage

Prepare your dataset by separating features and target values.

Scale the data to normalize values.

Train the model using batch gradient descent or stochastic gradient descent.

Monitor training using the cost recorded during epochs.

Visualize results to see how the model’s error decreases.

Convert predictions back to the original scale using inverse transformation.

Benefits

Ensures faster convergence of gradient-based algorithms.

Handles datasets with different feature scales efficiently.

Provides insight into model performance during training.

Easy to adapt for small or large datasets.

Conclusion

This project highlights how data scaling and gradient descent techniques improve linear regression training, enabling accurate predictions and efficient learning.
