# Deep Learning Optimizers (From Scratch)

This repository contains implementations of popular **optimization algorithms used in Deep Learning**, built from scratch using Python and Jupyter Notebooks.

The focus is on understanding the **mathematics, intuition, and behavior** of each optimizer rather than just using library functions.

---

## 📂 Project Structure



Optimiser/

│── Gradient_Descent.ipynb

│── Stochastic_Gradient_Descent.ipynb

│── Mini_Batch_Gradient_Descent.ipynb

│── Momentum.ipynb

│── Nesterov.ipynb

│── Adagrad.ipynb

│── RMSProp.ipynb

│── Adam.ipynb

│── AdamW.ipynb


---

## Optimizers Implemented

### 🔹 Basic Methods
- Gradient Descent (GD)
- Stochastic Gradient Descent (SGD)
- Mini-Batch Gradient Descent

### 🔹 Momentum-Based
- Momentum
- Nesterov Accelerated Gradient (NAG)

### 🔹 Adaptive Learning
- Adagrad  
- RMSProp  
- Adam  
- AdamW  

---

## 🔍 Optimizer Explanations

### 🔹 Gradient Descent (GD)
- Uses the full dataset for each update  
- Stable but slow for large datasets  
- Can get stuck in local minima  

**Update Rule:**  
θ = θ - α * ∇J(θ)

---

### 🔹 Stochastic Gradient Descent (SGD)
- Updates using one data point at a time  
- Faster but noisy  
- Helps escape local minima  

---

### 🔹 Mini-Batch Gradient Descent
- Uses small batches of data  
- Balanced approach (speed + stability)  
- Most widely used in practice  

---

### 🔹 Momentum
- Uses past gradients to smooth updates  
- Reduces oscillations  
- Speeds up convergence  

---

### 🔹 Nesterov Accelerated Gradient (NAG)
- Looks ahead before updating  
- More accurate than standard momentum  
- Faster convergence  

---

### 🔹 Adagrad
- Adapts learning rate for each parameter  
- Good for sparse data  
- Learning rate decreases over time  

---

### 🔹 RMSProp
- Uses moving average of squared gradients  
- Fixes Adagrad’s learning rate decay issue  
- Works well in non-stationary problems  

---

### 🔹 Adam (Adaptive Moment Estimation)
- Combines Momentum + RMSProp  
- Fast and efficient  
- Works well in most deep learning tasks  

---

### 🔹 AdamW
- Improved version of Adam  
- Better weight decay (regularization)  
- Prevents overfitting  

---

## What This Project Demonstrates

- Step-by-step weight updates  
- Effect of learning rate on convergence  
- Differences between optimizers  
- Handling oscillations and slow convergence  
- Adaptive vs fixed learning rates  

---

## Tech Stack

- Python  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## How to Run

```bash
git clone https://github.com/santhosh1282004/Deep-Learing.git
cd Deep-Learing/Optimiser
jupyter notebook

Run any notebook to see the optimizer in ac
