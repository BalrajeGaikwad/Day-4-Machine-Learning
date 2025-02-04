# Day-4-Machine-Learning
Day 4 Machine Learning



Gradient Descent is an optimization algorithm used to minimize a function by iteratively adjusting its parameters. It is widely used in machine learning and deep learning to optimize models by minimizing the loss function.

How Gradient Descent Works:
Initialize Parameters: Start with random values for the parameters (weights and biases in ML models).
Compute the Gradient: Calculate the derivative (gradient) of the loss function with respect to each parameter.
Update Parameters: Adjust parameters in the direction that reduces the loss using:


∇J(θ) is the gradient of the loss function.
Repeat Until Convergence: Continue updating parameters until changes become negligible or a stopping condition is met.
Types of Gradient Descent:
Batch Gradient Descent (BGD)

Uses the entire dataset to compute gradients in each step.
More stable but slow for large datasets.
Stochastic Gradient Descent (SGD)

Updates parameters for each training sample individually.
Faster but noisier, which may prevent convergence to the optimal point.
Mini-Batch Gradient Descent (MBGD)

Uses small batches of data to update parameters.
Balances stability and speed, making it commonly used in deep learning.
Challenges in Gradient Descent:
Choosing the right learning rate: Too high may cause overshooting, too low may make convergence slow.
Local minima and saddle points: Some functions have points where optimization can get stuck.
Feature scaling: Unnormalized features can slow down convergence.
Optimized Versions of Gradient Descent:
To improve performance, different optimizers are used, such as:

Momentum: Uses past gradients to smooth updates.
Adam (Adaptive Moment Estimation): Adjusts learning rates dynamically for better convergence.
RMSprop: Scales learning rates based on recent gradients.
