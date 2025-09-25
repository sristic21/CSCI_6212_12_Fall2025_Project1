# CSCI_6212_12_Fall2025_Project1
Project 1 of Design and Analysis of Algorithms

# Experimental Analysis of the given Nested Loop:

## 📝 Overview
The following program/code sample is to be analyzed:

int j=5
while (j<n/2) {
	int k=5
	while (k<n) {
sum += a[j]*b[k]
k=k*sqrt(2)
}
j= sqrt(3)*j
}

## Prerequisites
In order to run the analysis script, Python 3.x environment is needed with the following libraries:

* **`numpy`**: this is used for mathematical operations, especially for functions such as `np.log2` and `np.polyfit`.
* **`matplotlib`**: this is used to plot the experimental and theoretical results.

The installation can be done using `pip`:
```bash
pip install numpy matplotlib


##CHANGE
## Running the Code

1. Open a terminal and navigate to the project folder:

```bash
cd AsymptoticAnalysis
```

2. Run the Python script:

```bash
python analysis.py
```

3. The script will:

   * Compute experimental runtime for a set of `n` values.
   * Compute theoretical operation counts based on loop constraints.
   * Scale the theoretical values to comparable time units.
   * Print a table comparing experimental runtime, theoretical opearations, and scaled theoretical runtime.
   * Display a graph comparing experimental runtime vs scaled theoretical runtime.

---

## Input Sizes Tested

The following `n` values are used in the experiment:

```python
n_values = [4000, 5000, 6000, 7000, 8000, 9000, 10000,
            20000, 30000, 40000, 50000, 80000, 100000]
```
