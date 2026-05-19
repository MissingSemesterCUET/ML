---
title: "Lecture 3 – Neural Networks"
subtitle: "Outline & Learning Objectives"
---

## Overview

Neural networks learn complex, non-linear relationships by stacking layers of parameterized transformations. In this lecture we build a two-layer network from scratch, derive backpropagation, and train it on the MNIST handwritten-digit dataset.

## Learning Objectives

By the end of this lecture you will be able to:

1. **Describe** the architecture of a feedforward neural network (neurons, layers, activations).
2. **Implement** forward propagation with ReLU and softmax.
3. **Derive** the backpropagation algorithm using the chain rule.
4. **Train** a network on MNIST and plot the training curve.
5. **Explain** the roles of learning rate, batch size, and epochs.

## Topics Covered

| # | Topic | Duration |
|---|-------|----------|
| 1 | From logistic regression to neurons | 10 min |
| 2 | Network architecture & notation | 15 min |
| 3 | Activation functions (ReLU, sigmoid, softmax) | 10 min |
| 4 | Forward propagation | 15 min |
| 5 | Backpropagation derivation | 20 min |
| 6 | Coding session: NumPy neural network | 30 min |
| 7 | Training on MNIST & results | 15 min |

## Key Equations

**Forward pass (layer $l$):**
$$z^{[l]} = W^{[l]} a^{[l-1]} + b^{[l]}, \quad a^{[l]} = g(z^{[l]})$$

**Cross-entropy loss (multi-class):**
$$J = -\frac{1}{m}\sum_{i=1}^{m}\sum_{k=1}^{K} y_k^{(i)} \log \hat{y}_k^{(i)}$$

**Weight update:**
$$W^{[l]} := W^{[l]} - \alpha \frac{\partial J}{\partial W^{[l]}}$$

## Resources

- [Slides (interactive notebook)](slides.ipynb)
- [Video recording](video.md)
- 3Blue1Brown, *Neural Networks* series
