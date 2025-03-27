# Chapter1-1: MNIST Classification

This notebook trains an MLP model on the MNIST dataset using **MSELoss**.

- **MSELoss**: Treats labels as continuous values. Not ideal for classification as it doesn't account for class probabilities.
- **CrossEntropyLoss**: Designed for classification. Applies softmax + log internally to handle class probabilities effectively.