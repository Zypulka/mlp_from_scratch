# MLP from Scratch — University Lab Project

This repo is a **course/lab project** where I implement a **Multilayer Perceptron (MLP) from scratch**.  
No ready-made neural network libraries are used — everything MLP-related is implemented manually (using basic matrix operations).

## What’s inside

- **MLP architecture**
  - configurable number of layers / neurons
  - weights + biases
- **Training (backpropagation)**
  - full-batch and mini-batch updates
- **Optimizers**
  - Adam
  - RMSProp
- **Classification**
  - Softmax output layer 
- **Activation functions**
  - sigmoid, linear, tanh, ReLU
- **Overfitting control**
  - weight regularization
  - early stopping using a validation split

## Notebooks (weekly topics)

- `01_mlp_baseline.ipynb` — basic MLP + manual tuning on simple regression sets  
- `02_mlp_backprop.ipynb` — backprop training + batch vs full-batch + weight tracking  
- `03_mlp_adam_rmsprop.ipynb` — Adam vs RMSProp comparison  
- `04_mlp_softmax.ipynb` — classification with softmax  
- `05_mlp_activations.ipynb` — activation functions comparison  

- `06_mlp_regularization.ipynb` — regularization + early stopping (overfitting)
