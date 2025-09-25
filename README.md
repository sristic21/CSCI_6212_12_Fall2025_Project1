## CSCI_6212_12_Fall2025_Project1
Project 1 of Design and Analysis of Algorithms

# Experimental Analysis of the given Nested Loop:

# Overview
The following program/code sample is to be analyzed:
```c
int j=5
while (j<n/2) {
	int k=5
	while (k<n) {
sum += a[j]*b[k]
k=k*sqrt(2)
}
j= sqrt(3)*j
}
```
## Inputs (n) Tested for:

The following `n` values have been used in the experiment:

```python
N_vals=[1_000_000, 13_250_000, 25_500_000, 37_750_000, 50_000_000]
```

## Prerequisites
In order to run the analysis script, Python 3.x environment is needed with the following libraries:

* **`numpy`**: this is used for mathematical operations, especially for functions such as `np.log2` and `np.polyfit`.
* **`matplotlib`**: this is used to plot the experimental and theoretical results.

The installation can be done using `pip`:
```bash
pip install numpy matplotlib
```

##CHANGE
## Procedure to run the code

1. In order to get the program running, a suitable terminal is required through which the project folder can be navigated and accessed.

```bash
cd DesignAndAnalysis_Algorithms
```

2. Run the Python script:

```bash
python project1.py
```

3. The script performs the following tasks:

   * It performs a computation for the experimental runtime for a set of `n` values.
   * It performs a computation for the theoretical operation counts based on loop constraints.
   * It scales the theoretical values to comparable time units (by calculating a suitable scaling factor `C`).
   * It finally prints a table that contrasts and compares the curves obtained by the experimental runtime against the theoretical operations and the scaled theoretical runtime.
   * It also displays a graph comparing experimental runtime vs scaled theoretical runtime for a better understanding of the growth rates exhibited by the two runtimes.

---
