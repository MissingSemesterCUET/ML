---
title: "Lecture 1 – Linear Regression"
subtitle: "Outline & Learning Objectives"
---

## Overview

Linear regression is the starting point for supervised learning. In this lecture we derive the model from first principles, implement gradient descent in NumPy, and evaluate our predictions on a real-world dataset.

## Learning Objectives

By the end of this lecture you will be able to:

1. **Define** the linear regression hypothesis $h_\theta(x) = \theta^T x$.
2. **Derive** the Mean Squared Error (MSE) cost function and explain why it is convex.
3. **Implement** batch gradient descent from scratch in Python.
4. **Interpret** a loss curve and diagnose learning-rate issues.
5. **Evaluate** model performance using $R^2$, MAE, and RMSE.

## Topics Covered

| # | Topic | Duration |
|---|-------|----------|
| 1 | What is supervised learning? | 10 min |
| 2 | Hypothesis, parameters, and features | 15 min |
| 3 | Cost function (MSE) | 15 min |
| 4 | Gradient descent — intuition & math | 20 min |
| 5 | Coding session: NumPy implementation | 25 min |
| 6 | Learning rate & convergence | 10 min |
| 7 | Evaluation metrics (R², MAE, RMSE) | 15 min |

## Key Equations

**Hypothesis:**
$$h_\theta(x) = \theta_0 + \theta_1 x_1 + \cdots + \theta_n x_n$$

**Cost function:**
$$J(\theta) = \frac{1}{2m} \sum_{i=1}^{m} \left( h_\theta(x^{(i)}) - y^{(i)} \right)^2$$

**Gradient descent update:**
$$\theta_j := \theta_j - \alpha \frac{\partial}{\partial \theta_j} J(\theta)$$

## Resources

- [Slides (interactive notebook)](slides.ipynb)
- [Video recording](video.md)
- Andrew Ng, *Machine Learning* — Week 1
