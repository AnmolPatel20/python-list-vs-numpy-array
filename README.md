# python-list-vs-numpy-array
This repository contains a Jupyter notebook that benchmarks the execution time of element-wise multiplication using:  - ✅ Python Lists - ✅ NumPy Arrays
The goal is to highlight the performance difference between native Python operations and optimized NumPy operations for numerical computations.

---

## 📚 Contents

- `speedtest.ipynb`: Jupyter Notebook with benchmark tests comparing list and array multiplications.

---

## 🚀 What It Does

1. Creates two sequences of integers (e.g. from 0 to 999).
2. Multiplies them element-wise using:
   - Native Python list comprehension
   - NumPy's vectorized operations
3. Measures and compares execution time using the `time` module.

---

## 📈 Sample Output

Python list multiplication time: 0.00121 seconds
NumPy array multiplication time: 0.00014 seconds

