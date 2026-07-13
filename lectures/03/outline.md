---
title: "Lecture 3 – Pandas"
subtitle: "Outline & Learning Objectives"
---

## Overview

Pandas is the cornerstone of data analysis and manipulation in Python. This lecture introduces you to the two primary Pandas data structures: Series and DataFrames. You will learn how to construct them from various sources, inspect their properties, perform indexing and slicing, read external files, apply boolean masking, modify tabular structures, and aggregate or group data to extract key insights. By the end of this lecture, you will have a solid foundation for cleaning and preparing datasets for machine learning.

## Learning Objectives

By the end of this lecture you will be able to:

1. **Create and initialize** Pandas Series and DataFrames using lists, NumPy arrays, and dictionaries.
2. **Inspect** the properties, shape, and metadata of Series and DataFrames.
3. **Access and slice** data using direct indexing, label-based indexing (`.loc`), and position-based indexing (`.iloc`).
4. **Load datasets** from CSV, JSON, and JSON Lines (jsonl) formats.
5. **Apply boolean masking** with logical operators (`&`, `|`, `~`) and string matching (`.str.contains()`) to filter datasets.
6. **Explain the benefits** of using `df.loc[filter]` over `df[filter]` to avoid the `SettingWithCopyWarning`.
7. **Manipulate columns** by creating, dropping, and renaming them, and understand how the `inplace` parameter works.
8. **Compute summary statistics** and perform grouped operations using aggregate functions and `.groupby()`.

## Topics Covered

- **Pandas Data Structures**
    - **New Series**
        - Creating a Series with a list
            - Specifying custom index labels
        - Creating a Series with a NumPy array
        - Creating a Series with a dictionary
    - **New DataFrame**
        - Creating a DataFrame with a list
            - Specifying column names
            - Specifying custom index labels
        - Creating a DataFrame with a dictionary
- **Properties & Attributes**
    - `.index` — index (row labels) of the DataFrame/Series
    - `.columns` — column labels of the DataFrame
    - `.shape` — dimensionality (rows, columns)
    - `.size` — total number of elements
    - `.ndim` — number of dimensions
- **Diagnostic Methods**
    - `.head()` — view the first $N$ rows
    - `.tail()` — view the last $N$ rows
    - `.sample()` — view a random selection of rows
    - `.info()` — view a concise summary of the DataFrame (data types, non-null values, memory usage)
    - `.describe()` — generate descriptive statistics
- **Indexing & Slicing**
    - Direct indexing (selecting columns, slicing rows)
    - Label-based indexing (`.loc`)
    - Position-based integer indexing (`.iloc`)
- **Data Loading**
    - Reading CSV files (`pd.read_csv()`)
    - Reading JSON files (`pd.read_json()`)
    - Reading JSON Lines files (`pd.read_json(..., lines=True)`)
- **Data Manipulation & Iteration**
    - Sorting by column values (`.sort_values()`)
    - Iterating over rows (`.iterrows()`)
    - Creating, dropping, and renaming columns
        - Dropping columns (`.drop()`)
        - Renaming columns (`.rename()`)
        - Understanding the `inplace` parameter
- **Boolean Masking & Filtering**
    - Filtering rows based on conditions
    - Why use `df.loc[filter]` instead of `df[filter]` (preventing `SettingWithCopyWarning`, safe assignment)
    - Combining conditions with logical operators: `&` (AND), `|` (OR), `~` (NOT)
    - Filtering using string patterns (`.str.contains()`)
- **Aggregations & Grouping**
    - Common aggregate functions: `.min()`, `.max()`, `.mean()`, `.sum()`, `.count()`
    - Custom or multiple aggregations using `.agg()`
    - Grouped operations with `.groupby()`

## Resources

- [Class Notes](notebook.ipynb)
- [Video recording](video.md)
