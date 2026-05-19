---
title: "Lecture 2 – Logistic Regression & Classification"
subtitle: "Outline & Learning Objectives"
---

## Overview

Logistic regression extends linear models to classification problems. We'll explore the sigmoid function, derive the binary cross-entropy loss, and build a classifier that distinguishes between two classes with clear decision boundaries.

## Learning Objectives

By the end of this lecture you will be able to:

1. **Explain** why linear regression fails for classification tasks.
2. **Derive** the logistic (sigmoid) function and its properties.
3. **Formulate** the binary cross-entropy cost function.
4. **Implement** logistic regression with gradient descent.
5. **Visualize** decision boundaries in 2D feature space.
6. **Compute** accuracy, precision, recall, and F1-score.

## Topics Covered

| # | Topic | Duration |
|---|-------|----------|
| 1 | Classification vs. regression | 10 min |
| 2 | Sigmoid function | 10 min |
| 3 | Binary cross-entropy loss | 15 min |
| 4 | Gradient derivation | 15 min |
| 5 | Coding session: from-scratch classifier | 25 min |
| 6 | Decision boundaries | 10 min |
| 7 | Evaluation: confusion matrix, precision, recall, F1 | 15 min |

## Key Equations

**Sigmoid:**
$$\sigma(z) = \frac{1}{1 + e^{-z}}$$

**Cost function:**
$$J(\theta) = -\frac{1}{m}\sum_{i=1}^{m}\left[y^{(i)}\log(h_\theta(x^{(i)})) + (1 - y^{(i)})\log(1 - h_\theta(x^{(i)}))\right]$$

## Resources

- [Slides (interactive notebook)](slides.ipynb)
- [Video recording](video.md)
