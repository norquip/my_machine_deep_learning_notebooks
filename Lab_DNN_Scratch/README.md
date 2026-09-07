# Fully Conneted DNN From Scratch

### 🔬 Part I: From Mathematical Derivation  to Implementation

This project develops a fully connected neural network from its mathematical formulation to its computational implementation from scratch. 
The mathematical expressions for forward and backward propagation, as well as the cost function and gradient computation, are derived using tensor operations while explicitly tracking 
the dimensions and indices of the quantities involved. 
Broadcasting is formulated as the matrix product of the bias and a vector of ones, which is then expressed explicitly in terms of tensor indices.
The computational implementation then uses PyTorch primarily for tensor operations rather than PyTorch's high-level neural-network modules.  I use PyTorch broadcasting  for the bias expansion, 
as it provides a more efficient implementation.
Finally, gradient implementation is checked numerically using finite-difference gradient checking.





## Project Overview



The notebook covers the main steps involved in building and training a fully connected neural network:

### 🧮 Mathematical formulation
Derivation of forward and backward propagation, cost function, and gradients using tensor notation.

### 🔢 Tensor implementation
Explicit treatment of tensor dimensions, indices, and broadcasting.

### 🧠 Training
Parameter updates and training of the fully connected neural network.

### 🔍 Numerical validation
Validation of the analytical gradients using finite-difference gradient checking.




---




### 🔬 Part II: Understanding Overflow and Underflow: Their Effects on te Cost Function

This part extends the fully connected neural network developed in Part I to investigate numerical overflow and underflow in floating-point computations.

The experiments are performed using a simple neural network with architecture \([3,4,2,1]\), consisting of an input layer with 3 neurons, two hidden layers with 4 and 2 neurons, and an output layer with 1 neuron.

The experiments focus on how finite floating-point precision affects the numerical computations involved in forward propagation and the cost function. In particular, they illustrate how overflow and underflow can arise in exponential computations (as in the Sigmoid function) and how these effects propagate through the neural network.

The results provide a numerical perspective on the difference between the mathematical formulation of a neural network and its implementation using finite-precision arithmetic.

## Project Overview

The notebook covers the following numerical experiments:

### 🔢 Floating-point precision

Investigation of the limitations imposed by finite-precision floating-point representation.

### 📈 Numerical overflow

Analysis of the behavior of exponential computations when intermediate values become too large to be represented by the floating-point format.

### 📉 Numerical underflow

Analysis of the behavior of exponential computations when positive values become smaller than the smallest positive value representable by the floating-point format.

### 💰 Effect on the cost function

Investigation of how numerical overflow and underflow affect the computation of the neural network's cost function.

### 🔍 Numerical interpretation

Analysis of the numerical results to understand how finite precision influences the behavior of the implemented neural network.



## Tools

![Python](https://img.shields.io/badge/Python-3.x-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Tensors-orange)
![NumPy](https://img.shields.io/badge/NumPy-Computing-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)




## Repository Structure

```text
Lab_DNN_Scratch/
├── README.md
└── notebook/
    └── Construction_Scratch__DNN.ipynb
    └── Numerical_stability_Experiments.ipynb
```





