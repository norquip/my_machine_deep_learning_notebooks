\# DNN From Scratch



A fully connected Deep Neural Network implemented from scratch using \*\*PyTorch tensors and tensor operations\*\*.



The project develops the neural network from its mathematical formulation to its computational implementation, with emphasis on tensor dimensions, index notation, forward propagation, backward propagation, and gradient computation.



\## Project Overview



The notebook covers the main steps involved in building and training a fully connected neural network:



\- Data preprocessing

\- Network architecture

\- Forward propagation

\- Activation functions

\- Loss computation

\- Backward propagation

\- Gradient computation

\- Parameter updates

\- Model training



The implementation uses PyTorch primarily for tensor operations rather than PyTorch's high-level neural-network modules.



\## From Equations to Implementation



For a layer $l$, the forward propagation is defined by



$$
Z^{\[l]} = W^{\[l]}A^{\[l-1]} + b^{\[l]},
$$



followed by the activation function



$$
A^{\[l]} = g^{\[l]}(Z^{\[l]}).
$$



The mathematical expressions are translated into tensor operations while explicitly tracking the dimensions and indices of the quantities involved.



Backward propagation is derived using the chain rule and implemented through the corresponding gradients with respect to the model parameters and activations.



\## Tools



\- Python

\- PyTorch

\- NumPy

\- Matplotlib



\## Repository Structure



```text

Lab\_DNN\_Scratch/

│

├── README.md

│

└── notebook/

&#x20;   └── Construction\_Scratch\_\_DNN.ipynb

