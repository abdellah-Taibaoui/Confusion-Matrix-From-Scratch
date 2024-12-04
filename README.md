# Confusion Matrix Implementation from Scratch

This repository contains a **Jupyter Notebook** that demonstrates how to implement a **Confusion Matrix** from scratch. The implementation is compared with the confusion matrix provided by **scikit-learn** to ensure correctness. The repository also includes a test Excel file for evaluating the implementation with sample data.

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Contents](#contents)


---

## Overview

A confusion matrix is a key evaluation metric in classification tasks, summarizing the performance of a model by showing the counts of true positives, true negatives, false positives, and false negatives. This project provides:
- A step-by-step implementation of the confusion matrix from scratch.
- A comparison of the custom implementation with the scikit-learn `confusion_matrix()` function.
- An example dataset for testing, provided in an Excel file.

This repository is ideal for learning about confusion matrices and understanding how they are calculated programmatically.

---

## Features

- **Confusion Matrix from Scratch**:
  - Calculates the counts of TP, TN, FP, and FN directly from prediction and ground truth arrays.
  - Provides an in-depth look at the logic behind confusion matrix construction.

- **Comparison with Scikit-learn**:
  - Validates the custom implementation by comparing it with `sklearn.metrics.confusion_matrix`.

- **Excel Test File**:
  - Includes a sample Excel file (`test_data.xlsx`) with example predictions and ground truth labels for testing the implementation.

---

## Contents

The repository includes:
1. **Notebook**:
   - `confusion_matrix_from_scratch.ipynb`: A Jupyter Notebook demonstrating the custom implementation, scikit-learn comparison, and sample usage.

2. **Excel File**:
   - `test_data.xlsx`: Contains columns for ground truth labels and predicted labels to test the confusion matrix implementation.

---

