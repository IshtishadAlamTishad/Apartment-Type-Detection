# Apartment-Type-Detection

## Multi-Class Classification with Neural Network

In this model I implemented a three hidden layer neural network for multi-class classification using a synthetic dataset. The neural network is trained to classify data points into five distinct classes: Normal, Triplex, Luxury, Duplex, and High Rise based on input features related to square feet and floor level.

## Dataset
![1](https://github.com/IshtishadAlamTishad/Apartment-Type-Detection/assets/96460346/d5f5f5dc-a314-44ee-af3a-f0a06c0b5cfb)

The synthetic dataset consists of 1000 data points, with 2 features. Each data point is labeled with one of the following classes:
- Normal (1)
- Triplex (2)
- Luxury (3)
- Duplex (4)
- High Rise (5)

## Model Architecture
Features : Area & Floor Level

The neural network has the following architecture:
- Input Layer: 2 Neurons 
- Hidden Layer 1: 500 neurons
- Hidden Layer 2: 500 neurons
- Hidden Layer 3: 500 neurons
- Output Layer: 5 neurons (one for each class)

The model uses the sigmoid activation function for the hidden layers and the softmax activation function for the output layer.

## Training

The model is trained for 10000 epochs with a learning rate of 0.1. Training loss is monitored and plotted over time to visualize the training process.

![2](https://github.com/IshtishadAlamTishad/Apartment-Type-Detection/assets/96460346/73fd3415-7486-4e19-879c-ce153cfbd952)

## Results

After training, the model achieved an accuracy of 92.23% on the test set, demonstrating its effectiveness in classifying the synthetic data.

![acc2](https://github.com/IshtishadAlamTishad/Apartment-Type-Detection/assets/96460346/04738c22-eb2d-4ca4-9cf2-09edd0298c8d)

