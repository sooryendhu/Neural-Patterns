# Soor
Title: Enhanced Neural Network with Dilated Convolutions and Parallel Branches for MNIST Classification

Overview:
This project aimed to improve the performance of a neural network for the MNIST digit classification task by incorporating dilated convolutions and parallel branches. The implementation was visualized using Netron.app, and the model was trained on the MNIST dataset to assess its accuracy.

Key Components:

Neural Network Architecture:

The neural network architecture was designed to include dilated convolutions and parallel branches to capture both local and global features effectively.
Dilated convolutions were introduced to increase the receptive field without significantly increasing the number of parameters.
Parallel branches were incorporated to process different aspects of the input simultaneously, enhancing the model's ability to learn diverse features.
Visualization using Netron.app:

Netron.app was utilized to visualize the neural network architecture, providing an intuitive and interactive representation of the model's structure.
The visualization helped in understanding the flow of data through different layers and inspecting the connectivity of dilated convolutions and parallel branches.
Training on MNIST Dataset:

The model was trained on the MNIST dataset, which consists of 28x28 grayscale images of handwritten digits (0-9).
The training process involved optimizing the model's parameters using a suitable optimization algorithm, such as stochastic gradient descent (SGD) or Adam.
The accuracy of the model was monitored during training to assess its performance on the digit classification task.
Evaluation and Results:

The trained model was evaluated on a separate test set from the MNIST dataset to measure its accuracy and generalization ability.
Results were analyzed to determine the impact of dilated convolutions and parallel branches on the model's performance compared to a baseline neural network.
