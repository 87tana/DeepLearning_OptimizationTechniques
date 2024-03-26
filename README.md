In the **initialization** code, I explored different methods for weight initialization in a neural network. Here's a summary of what I did:

1. **Zero Initialization**:initialized all parameters (weights and biases) to zero. However, this approach failed to break symmetry, resulting in poor performance.

2. **Random Initialization**: We initialized the weights to large random values (scaled by 10) and biases to zeros. While this approach showed better performance than zero initialization, it had some drawbacks such as slow convergence and the risk of vanishing/exploding gradients.

3. **He Initialization**: We used He initialization, which scales the weights by a factor of sqrt(2/previous_layer_size). This method worked well, leading to faster convergence and improved performance compared to the previous initialization methods.

Overall, we observed that proper initialization of weights is crucial for the effective training of neural networks. He initialization emerged as a recommended approach, especially for networks with ReLU activations.
