# 🚀 Benchmarking Optimization Algorithms (SGD, Momentum, NAG)

## 📌 Overview
This project benchmarks and compares the performance of different gradient-based optimization algorithms used in machine learning. The goal is to analyze how quickly and effectively each optimizer converges while minimizing loss.

The optimizers implemented and evaluated in this project include:

- Stochastic Gradient Descent (SGD)
- Momentum
- Nesterov Accelerated Gradient (NAG)

---

## 🎯 Objective

The main objectives of this project are:

- To implement core optimization algorithms from scratch
- To compare their convergence behaviour
- To analyze optimization speed and stability
- To visualize loss reduction across iterations

---

## ⚙️ Optimizers Implemented

### 1. Stochastic Gradient Descent (SGD)
The basic optimization algorithm that updates parameters using the gradient of the loss function.

### 2. Momentum
Momentum accelerates SGD by accumulating past gradients to smooth updates and reduce oscillations.

### 3. Nesterov Accelerated Gradient (NAG)
NAG improves momentum by computing the gradient at the “look-ahead” position, resulting in faster and more informed updates.

---

## 🧪 Experimental Setup

- Language: Python
- Libraries: NumPy, Matplotlib
- Training approach: Iterative gradient updates
- Evaluation metric: Loss vs iterations

---

## 📊 Results & Visualization

The performance of optimizers is evaluated using:

- 📉 Loss vs Iterations graph
- ⚡ Convergence speed comparison
- 📈 Stability of optimization path

> (Insert your plotted graphs here by adding screenshots in the repo)

---

## 🔍 Key Observations

- NAG converges faster compared to SGD and Momentum
- Momentum provides smoother convergence than SGD
- SGD is simple but slower in reaching optimal loss
- NAG’s look-ahead gradient leads to better trajectory planning

---

## 📁 Project Structure
Benchmark-estimation-optimizers/
│
├── benchMark_NAG.ipynb
├── results
└── README.md

---

## 🚀 Future Improvements

- Add Adam and RMSProp optimizers
- Compare performance across different learning rates
- Benchmark on real datasets (e.g., MNIST)
- Measure computation time vs accuracy trade-off

---

## 💼 Relevance

This project demonstrates practical understanding of:

- Optimization in Machine Learning
- Gradient-based learning methods
- Performance benchmarking
- Numerical experimentation and analysis



---

## ⭐ If you found this useful
Give the repo a star ⭐ and feel free to fork or contribute!
