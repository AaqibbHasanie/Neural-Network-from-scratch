In this project, I implement a neural network class from scratch using numpy only. I also implement the following functions:

1. *Forward/backward pass & Weight Update:* I implement the forward and backward pass algorithms and avoid any for loop, i.e., use vectorization only.

2. *Optimizers:* I implement full-batch Gradient Descent, Minibatch and Stochastic gradient descent variants.

3. For weights I use standard normal distribution (0 mean and 1 var). Biases are initialized to all zero.

4. **Visualization code**: I also provide a visualization code to plot the learnt decision boundary of my model.

5. *Activation Functions:* I also implement the following activation functions :
- Sigmoid
- ReLU
- Leaky ReLU (leaky slope is fixed at 0.05)

# Importan Points:

- In order to check the efficiency of my model, I use different combination of learning rates, epochs, activation functions, and optimizers to obtain the best results. I perform a total of 5 experiments. 
- I use an artificially generated dataset to test my model for both regression and classification and ultimately shift towards a real dataset to test the model.
- I have provided as a general neural network which can work and give perfect results with any dataset.

Users are welcome to use this model with any dataset and obtain results.

