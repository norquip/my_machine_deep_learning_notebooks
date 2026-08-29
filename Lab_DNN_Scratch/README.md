# Fully Conneted DNN From Scratch

### 🔬 From Mathematical derivation  to Implementation

This project develops a fully connected neural network from its mathematical formulation to its computational implementation from scratch. 
The mathematical expressions for forward and backward propagation, as well as the cost function and gradient computation, are derived using tensor operations while explicitly tracking 
the dimensions and indices of the quantities involved. 
Broadcasting is formulated as the matrix product of the bias and a vector of ones, which is then expressed explicitly in terms of tensor indices.
The computational implementation then uses PyTorch primarily for tensor operations rather than PyTorch's high-level neural-network modules.
Finally, the analytical gradients are validated numerically using finite-difference gradient checking.





## Project Overview



The notebook covers the main steps involved in building and training a fully connected neural network:

### 🧮 Mathematical formulation
Derivation of forward and backward propagation, cost function, and gradients using tensor notation.

### 🔢 Tensor implementation
Explicit treatment of tensor dimensions, indices, and broadcasting in matrix and tensor notation.

### 🧠 Training
Parameter updates and training of the fully connected neural network.

### 🔍 Numerical validation
Validation of the analytical gradients using finite-difference gradient checking.



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
```





