# Eigen Decomposition Using Python

## Aim

To find the eigenvalues and eigenvectors of a given matrix using Python.

## Problem Statement

Find the eigenvalues and eigenvectors of the matrix:

    [ 2  1 ]
A = [ 1  2 ]

## Objective

The objective of this program is to:

- Create a matrix using NumPy.
- Perform eigen decomposition.
- Find eigenvalues.
- Find corresponding eigenvectors.
- Display the results.

## Requirements

- Python 3.x
- NumPy

Install NumPy using:

    pip install numpy

## Algorithm

1. Import NumPy.
2. Create the given matrix.
3. Use `numpy.linalg.eig()` to calculate eigenvalues and eigenvectors.
4. Store the results.
5. Display the eigenvalues.
6. Display the eigenvectors.

## Python Code

```python
import numpy as np

A = np.array([[2, 1],
              [1, 2]])

# Eigen decomposition
eigenvalues, eigenvectors = np.linalg.eig(A)

print("Matrix:")
print(A)

print("\nEigenvalues:")
print(eigenvalues)

print("\nEigenvectors:")
print(eigenvectors)
