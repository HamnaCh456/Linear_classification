# Linear Classification with Hinge Loss

This repository contains a simple implementation of linear classification using hinge loss, optimized via batch gradient descent.

## 🧠 Overview

- Binary classification on a small dataset
- Loss function: **Hinge Loss** (commonly used in SVMs)
- Optimization: **Gradient Descent**
- Language: **Python** with **NumPy**

## 📁 Dataset

A hardcoded toy dataset with 3 training examples:

```python
trainExamples = [
    ((0, 2), 1),
    ((-2, 0), 1),
    ((1, -1), -1),
]
