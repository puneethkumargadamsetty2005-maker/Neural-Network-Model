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
