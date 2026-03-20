# Theory Report

## What is Data Analysis?

Data analysis is the process of collecting, cleaning, transforming, and interpreting data to discover useful insights, identify patterns, and support better decision-making. It turns raw data into meaningful information that can solve business problems.

## Steps to Plan a Data Science Project

1. Understand the business problem.
2. Define the objective.
3. Collect data from multiple sources.
4. Clean and preprocess the data.
5. Perform exploratory data analysis.
6. Engineer useful features.
7. Build and evaluate machine learning models.
8. Interpret results.
9. Present or deploy the final solution.

## Machine Learning Problem Statement

The machine learning task in this project is a binary classification problem: predict whether a customer will churn based on demographic details, purchase behavior, and support-related variables.

## What Are Tensors?

A tensor is a mathematical object used to represent data in multiple dimensions. A scalar is a 0D tensor, a vector is a 1D tensor, a matrix is a 2D tensor, and higher-dimensional arrays are tensors. Tensors are widely used in machine learning because they efficiently store features, labels, and model parameters.

## NumPy Tensor Example

import numpy as np

scalar = np.array(5)
vector = np.array([1, 2, 3])
matrix = np.array([[1, 2], [3, 4]])
tensor_3d = np.array([[[1, 2], [3, 4]], [[5, 6], [7, 8]]])

print(scalar.shape)
print(vector.shape)
print(matrix.shape)
print(tensor_3d.shape)
