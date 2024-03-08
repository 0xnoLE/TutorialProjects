Micrograd Lab (Neural Network Simulation from Scratch!)
This is a great lab ledby Andrej Karpathy!

https://www.youtube.com/watch?v=VMj-3S1tku0&t=4249s&ab_channel=AndrejKarpathy

Objective:

This is the most step-by-step spelled-out explanation of backpropagation and training of neural networks. It only assumes basic knowledge of Python and a vague recollection of calculus.

Basic Information

Neural Networks

Neural networks are a core technology in AI, inspired by the structure and function of the human brain. At a basic level, a neural network is a series of algorithms that attempt to recognize underlying relationships in a set of data through a process that mimics the way the human brain operates. Neural networks are used for a variety of tasks, including but not limited to, pattern recognition, classification, and prediction.

Neural networks consist of layers of interconnected nodes or "neurons", with each layer designed to perform specific transformations on its input data. These layers are typically categorized into three types:

Input Layer: The initial layer that receives the input data.
Hidden Layers: One or more layers that perform computations and feature extractions.
Output Layer: The final layer that produces the prediction or classification.
Backpropagation: The Heart of Learning
Backpropagation is a fundamental algorithm used for training neural networks. It allows the network to adjust its internal parameters (weights and biases) based on the error of the output compared to the expected result. Essentially, backpropagation calculates the gradient (the derivative of the error with respect to each parameter) of the error function by propagating the error backward through the network. This process involves two main phases:

Forward Pass: The input data is passed through the network layer by layer until it reaches the output. Each neuron applies a weighted sum on its inputs, followed by a non-linear activation function.

Backward Pass (Backpropagation): The error is calculated at the output and propagated back through the network, layer by layer, updating the weights and biases according to how much they contributed to the error. This is typically achieved using the gradient descent optimization algorithm or one of its variants.

Arbitrary Numbers in Backpropagation
In explaining backpropagation, we often use arbitrary numbers for weights, biases, inputs, and the learning rate to illustrate how the algorithm adjusts the network's parameters to minimize the error. These numbers serve to provide a concrete example of the calculations involved in backpropagation, making the abstract concepts more tangible and easier to understand.

By iteratively adjusting the weights and biases through backpropagation, the neural network learns to perform its task with increasing accuracy. This learning process continues until the network reaches a satisfactory level of performance or a specified number of iterations.

This lab will further explore the concept of backpropagation and its role in training neural networks, using practical examples and exercises.
