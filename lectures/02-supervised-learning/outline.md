---
title: "Lecture 2: Supervised Learning"
---

## Learning Objectives

By the end of this lecture, you will be able to:
- Explain the concept of Supervised Learning.
- Distinguish between Regression and Classification tasks.
- Understand the basics of Linear and Logistic Regression.
- Build and evaluate a simple Decision Tree model.
- Use key evaluation metrics like Accuracy, Precision, and Recall.

## What is Supervised Learning?

Supervised Learning is the most common type of ML where the model is trained on a labeled dataset. A labeled dataset means that for every input, the correct output (or "label") is already known.

### Regression vs. Classification

- **Regression:** Predicting a continuous numerical value (e.g., house prices, stock trends).
- **Classification:** Predicting a discrete category or class (e.g., spam vs. not spam, cat vs. dog).

## Key Algorithms

### 1. Linear Regression
Used for regression tasks. It finds the best-fit line that minimizes the difference between predicted and actual values.

### 2. Logistic Regression
Despite its name, it's used for binary classification. It outputs the probability of an input belonging to a certain class.

### 3. Decision Trees
A tree-like model that makes decisions based on feature values. It's intuitive and can handle both regression and classification.

## Evaluation Metrics

To know how well our model is performing, we use:
- **Mean Squared Error (MSE):** For regression.
- **Accuracy:** Percentage of correct predictions.
- **Precision & Recall:** Critical for imbalanced datasets.
- **F1-Score:** The harmonic mean of precision and recall.

::: {.callout-warning}
### Overfitting
Be careful of overfitting! A model that performs perfectly on training data but poorly on new data is not useful in production.
:::
