---
title: "Lecture 3: Unsupervised Learning"
---

## Learning Objectives

By the end of this lecture, you will be able to:
- Define Unsupervised Learning and its primary goals.
- Understand and implement K-Means Clustering.
- Explain the concept of Dimensionality Reduction using PCA.
- Identify use cases for Anomaly Detection.
- Differentiate between various clustering techniques.

## What is Unsupervised Learning?

Unsupervised Learning involves training a model on data that has no labels. The model must find the underlying structure or distribution in the data on its own.

### Key Tasks

1.  **Clustering:** Grouping similar data points together (e.g., K-Means, Hierarchical Clustering).
2.  **Dimensionality Reduction:** Reducing the number of random variables under consideration (e.g., PCA, t-SNE).
3.  **Association:** Discovering rules that describe your data (e.g., people who buy X also buy Y).

## Clustering Techniques

### 1. K-Means Clustering
Partitions the data into $K$ clusters. Each data point belongs to the cluster with the nearest mean (centroid).

### 2. Hierarchical Clustering
Builds a hierarchy of clusters either through a top-down or bottom-up approach.

## Principal Component Analysis (PCA)

PCA is a dimensionality reduction technique that transforms high-dimensional data into a lower-dimensional form while retaining as much variance as possible. It's often used for:
- Data visualization
- Noise reduction
- Speeding up other ML algorithms

## Anomaly Detection

Identifying rare items, events, or observations which raise suspicions by differing significantly from the majority of the data. Useful in:
- Credit card fraud detection
- Network security
- Industrial equipment monitoring

::: {.callout-note}
### Reflection
Think about how you could use Unsupervised Learning on a dataset of customer purchase history!
:::
