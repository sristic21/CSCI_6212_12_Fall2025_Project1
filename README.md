# CSCI_6212_12_Fall2025_Project1
Project 1 of Design and Analysis of Algorithms

# Experimental Analysis of O(log² n) Nested Loops

## 📝 Overview
This repository contains a Python script used to experimentally verify the time complexity of a nested loop structure, where both the outer and inner loop variables grow geometrically.

The theoretical analysis concluded that the algorithm's time complexity is **$T(n) = O(\log^2 n)$**. The script measures runtime for large input sizes and uses polynomial regression to fit a quadratic curve to the $\log_2(n)$ values, confirming this scaling behavior.

## ⚙️ Prerequisites
To successfully run this analysis script, you need a Python 3 environment and the following libraries:

* **`numpy`**: For mathematical operations, especially `np.log2` and `np.polyfit`.
* **`matplotlib`**: For plotting the experimental and theoretical results.

You can install them using `pip`:
```bash
pip install numpy matplotlib
