# Neural-network
Implementation of Neural network from scratch

# **Neural Network from Scratch in Python**

## **Overview**
This project demonstrates how to build a simple neural network from scratch using Python. The implementation does not use machine learning libraries like TensorFlow or PyTorch. Instead, it focuses on understanding the fundamentals of neural networks, including forward propagation, backpropagation, and gradient descent.

## **Features**
- Fully connected neural network
- Supports multiple layers
- Implements activation functions (Sigmoid, ReLU)
- Backpropagation for training
- Gradient descent optimization
- Works on classification problems


## **Implementation Details**

### **1. Neural Network Architecture**
The network consists of an input layer, hidden layers, and an output layer. Each layer applies weights, biases, and an activation function.

### **2. Activation Functions**
- **Sigmoid**: Used for binary classification
- **ReLU (Rectified Linear Unit)**: Prevents vanishing gradient problem

### **3. Forward Propagation**
The forward pass computes the output by applying weights and activation functions sequentially across layers.

### **4. Backpropagation**
The backpropagation algorithm computes gradients using the chain rule and updates weights to minimize error.


## **Results & Visualization**
After training, you can visualize the loss function using `matplotlib` to see how the model improves over time.



