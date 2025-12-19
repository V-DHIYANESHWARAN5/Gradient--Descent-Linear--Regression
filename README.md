# Gradient Descent from Scratch (Linear Regression)

This project implements Gradient Descent from scratch to understand how linear
regression optimization works internally. The results are compared with
scikit-learn’s closed-form LinearRegression.

---

## Dataset
Advertising Dataset (Kaggle / ISLR)
- Features: TV, Radio, Newspaper
- Target: Sales

---

## Implemented Algorithms
- Batch Gradient Descent (single feature)
- Cost vs Iterations visualization
- Multi-Feature Gradient Descent
- Stochastic Gradient Descent (SGD)
- Mini-Batch Gradient Descent
- Comparison with scikit-learn LinearRegression

---

## Mathematical Foundation
Linear Regression:
y = mx + b

Cost Function (MSE):
J = (1/n) Σ (yᵢ − ŷᵢ)²

Gradients:
∂J/∂m = -(2/n) Σ xᵢ (yᵢ − ŷᵢ)  
∂J/∂b = -(2/n) Σ (yᵢ − ŷᵢ)

Update Rule:
θ = θ − α ∇J

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## How to Run
```bash
pip install -r requirements.txt
python gradient_descent_project.py
