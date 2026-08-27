# Single-layer-perceptron
Overview

This project implements a Single Layer Perceptron from scratch for binary classification using the Banknote Authentication Dataset from the UCI Machine Learning Repository.

The main objective is to understand how an artificial neuron works, implement the perceptron learning algorithm without using a ready-made perceptron model, visualize the training process, and evaluate its performance.

Objective

Understand the artificial neuron model and implement the perceptron learning algorithm end to end: weighted sum → step activation → prediction → error-driven weight/bias update, then evaluate the trained classifier on real data.

Key Takeaways

The dataset is nearly, but not perfectly, linearly separable in 4D — training error plateaus around 12–20 misclassified samples rather than reaching zero within 50 epochs.
Variance and Skewness are the most discriminative features (highest correlation with class label).
The perceptron converges on AND/OR/NOT but cannot converge on XOR, since XOR is not linearly separable — a hidden layer (MLP) is required to solve it.
