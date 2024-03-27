In the **initialization** code, I explored different methods for weight initialization in a neural network. Here's a summary of what I did:
1. **Zero Initialization**:initialized all parameters (weights and biases) to zero. However, this approach failed to break symmetry, resulting in poor performance.
2. **Random Initialization**:initialized the weights to large random values (scaled by 10) and biases to zeros. While this approach showed better performance than zero initialization, it had some drawbacks such as slow convergence and the risk of vanishing/exploding gradients.
3. **He Initialization**: used He initialization, which scales the weights by a factor of sqrt(2/previous_layer_size). This method worked well, leading to faster convergence and improved performance compared to the previous initialization methods.(recommended approach)
especially for networks with ReLU activations.



In the **Regularization** code, I explored different methods for weight initialization in a neural network. Here's a summary of what I did:

1. **Non-Regularized Model**
First I implement neural network model without regularization. This serves as a baseline for comparing the performance of regularized models.

**L2 Regularization**
A detailed explanation of L2 regularization is provided, along with its implementation in the neural network model.

**compute_cost_with_regularization**
Instructions for implementing the cost function with L2 regularization and its corresponding Python code are included in this exercise.

**backward_propagation_with_regularization**
Instructions for implementing backward propagation with L2 regularization and its corresponding Python code are included in this exercise.

**Dropout**
Dropout is a regularization technique used to prevent overfitting in neural networks. This section covers the theory behind dropout and its implementation in neural network models.

**Forward Propagation with Dropout**
Instructions for implementing forward propagation with dropout and its corresponding Python code are provided in this subsection.

**forward_propagation_with_dropout**
Instructions for completing the implementation of forward propagation with dropout and its corresponding Python code are included in this exercise.

**Backward Propagation with Dropout**
Instructions for implementing backward propagation with dropout and its corresponding Python code are provided in this subsection.

backward_propagation_with_dropout
Instructions for completing the implementation of backward propagation with dropout and its corresponding Python code are included in this exercise.


