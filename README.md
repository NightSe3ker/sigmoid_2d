# 📉 Sigmoid Function Visualization in 2D

This project visualizes the **sigmoid activation function** and explores how adjusting its parameters (weight `w` and bias `b`) influences the output curve. It also simulates how sigmoid outputs change for randomly generated input values.

---

## ✅ What This Code Does

- Defines a flexible sigmoid function:  
  \[
  \sigma(x) = \frac{1}{1 + e^{-(wx + b)}}
  \]
- Plots the sigmoid curve over a range of x-values
- Shows how the curve shifts and steepens with different weights and biases
- Applies the sigmoid to random `x` values to visualize predicted outputs

---

## 🛠️ Technologies Used

- Python
- NumPy
- Matplotlib
- (Seaborn & Pandas are imported but not used)

---

## 📈 Visual Output

- A 2D line plot of the sigmoid curve
- A scatter plot showing sigmoid-transformed values of random inputs

---

## 📋 Requirements

Install the following Python packages:

```bash
pip install numpy matplotlib
