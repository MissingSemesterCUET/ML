---
title: "Lecture 2 – Maths for ML, NumPy & Pandas"
subtitle: "Outline & Learning Objectives"
---

## Overview

A hands-on dive into the mathematical foundations that power Machine Learning — vectors, matrices, and key operations — using NumPy for fast numerical computing and Pandas for structured data manipulation. By the end, you'll be comfortable thinking in terms of arrays and DataFrames.

## Learning Objectives

By the end of this lecture you will be able to:

1. **Understand** vectors and matrices from both a physics and mathematics perspective.
2. **Perform** vector and matrix operations using NumPy — dot products, transpose, reshaping, and broadcasting.
3. **Distinguish** element-wise operations from matrix multiplication (Hadamard product vs dot product).
4. **Create** and manipulate Pandas DataFrames and Series for tabular data.
5. **Apply** filtering, grouping, and basic aggregations on real-world datasets using Pandas.

## Topics Covered
- Mindset
    - It's not diffcult
    - Jumping around
- Motivation
    - DL is just maths+data
    - PyTorch is like a wrapper on NumPy
- Vectors
    - Vectors in physics
    - Vectors in CS/Math
        - Same as physics, just represented differently
        - Why it's easier in higher dimensions
        - Column vectors and row vectors
    - Vectors vs. Sets
        - Order
        - Duplicates
    - Example
        - Feature vector ${(x_i, y_i)}_{i=1}^N$
    - Vector Operations (exercise)
        - Vector addition
        - Scalar multiplication
        - Hadamard product
        - Dot product
    - Numpy
        - Vector addition
        - Scalar multiplication
        - Hadamard product
        - Dot product
- Matrices
    - Definition: 2D array
    - Indexing (in math notation)
        - entry
        - column
        - row
    - Matrix Operations (exercise)
        - Matrix addition
        - Scalar multiplication
        - Hadamard product
        - Matrix multiplication
            - Example: cgpa calculation (mat-vec)
        - Frobenius norm
            - Example: recommendation system
    - Numpy
        - Matrix addition
        - Scalar multiplication
        - Hadamard product
        - Matrix multiplication
        - Frobenius norm
        - Indexing matricies
            - Preferred way
            - Alternative
        - Matrix Shape
        - Reshaping
        - Transpose
            - Column vectors and row vectors
    - Vector are 1D Matrix (for us)
        - Dot product as Matrix multiplication
- Tensors
    - Definitions: Scalars, Vectors, Matrices and, more
    - Tensors in numpy
        - `ndarray`
        - Example: 3D array
        - Transpose of 1D tensors
        - Broadcasting rules
            - Example: matrix + scalar
            - Example: matrix + column vector
            - Example: matrix + row vector
            - The rules
            - Example: row vector + column vector
- More on Numpy
    - types
    - Common constructors
        - `np.ones`
        - `np.zeros`
        - `np.eye`
        - `np.arange`
        - `np.linspace`
- Norms
    - L2 Norm
        - Exercise
        - with dot product
        - `np.linalg.norm`
    - L1 Norm
        - Exercise
    - L-max Norm
    - Lp Norm

## Resources

- [Slides (interactive notebook)](notebook.ipynb)
- [Video recording](video.md)
