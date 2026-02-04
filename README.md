# Neural-Network-Model
import torch
→ I am importing PyTorch to work with tensors and perform deep learning operations.

import torch.nn as nn
→ I am importing the neural network module to create layers and build a model easily.

nn.Sequential()
→ I am creating a neural network where layers are connected one after another in order.

nn.Linear(2, 4)
→ The model takes 2 input values and converts them into 4 hidden neurons.

nn.ReLU()
→ I am using ReLU activation to remove negative values and help the model learn better.

nn.Linear(4, 1)
→ This is the output layer which converts 4 values into 1 final output.

1️⃣ import torch

This line loads PyTorch

PyTorch is used for:

Handling numbers as tensors

Performing mathematical operations

Training deep learning models
 2️⃣ import torch.nn as nn

torch.nn contains neural network tools

nn is a short name for convenience

It helps us create:

Layers

Activation functions

Complete models
nn.Sequential(...)

nn.Sequential means:

“Execute layers one after another”

Output of one layer becomes input to the next layer
4️⃣ nn.Linear(2, 4) → First Layer

This is a fully connected layer

2 inputs → 4 neurons

Each input is multiplied by weights and added with bias
5️⃣ nn.ReLU() → Activation Function

ReLU = Rectified Linear Unit

Rule:

If value < 0 → 0
If value ≥ 0 → same value
nn.Linear(4, 1) → Output Layer

Takes 4 values from hidden layer

Produces 1 final output

Used for:

Regression problems

Binary classification (with sigmoid later)
