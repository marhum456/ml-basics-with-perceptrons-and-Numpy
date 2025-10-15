# Neural Network Examples & Tasks

This repository contains a comprehensive collection of **30 practical examples** and **13 hands-on coding tasks** demonstrating the implementation and training of various types of neural networks—from basic perceptrons to multi-layer architectures—using Python and NumPy.

All examples focus on **real-world binary classification problems** across diverse domains such as healthcare, marketing, automotive systems, energy, and more.

---

## 📁 Structure Overview

### 🧠 Neural Network Types Covered

1. **Single-Layer Single Perceptron (with function)**
   - Examples 1–10: Email response prediction, equipment failure detection, CLV prediction, etc.

2. **Single-Layer Single Perceptron (without function)**
   - Examples 1–10: Same use cases with hardcoded weights/bias.

3. **Multi-Layer Perceptron (MLP) with fixed/variable neurons**
   - Examples 1–10: Deeper architectures with 2 hidden layers.

4. **Single-Layer Multi-Perceptron (parallel perceptrons)**
   - Examples 1–10: Multiple independent perceptrons for same input.

---

### 📝 Coding Tasks (Q1–Q13)

| Task | Description |
|------|-------------|
| **Q1** | Single neuron with user-defined inputs, weights, bias; show output |
| **Q2** | Single perceptron with sigmoid activation; display all parameters |
| **Q3** | Single perceptron with randomly generated weights & bias |
| **Q4** | Two-layer network (3 neurons each); forward propagation (two methods: functions & class) |
| **Q5** | Two-layer network with **variable neuron counts** per layer |
| **Q6** | Two-layer network with **randomly generated inputs, weights, and biases** |
| **Q7** | Single-layer perceptron on a **4-sample dataset** (3 features); show predictions |
| **Q8** | Multi-layer perceptron on same dataset; show layer-wise outputs |
| **Q9** | Single-layer network with **loss computation** (binary cross-entropy) |
| **Q10** | Multi-layer network with **loss computation** |
| **Q11** | **Backpropagation & training** for single-layer network (10 epochs, early stopping) |
| **Q12** | **Backpropagation & training** for multi-layer network |
| **Q13** | Compare **4 optimizers**: GD, SGD, Mini-batch GD, AdaGrad (with loss plots) |

---

## 🧰 Technologies Used

- **Language:** Python 3.x

- **Libraries:**
  - **NumPy** – Numerical computations
  - **Matplotlib** – Visualization
  - **Scikit-learn** – Model evaluation
  - **IPython / Jupyter** – Interactive notebooks

---

## 📊 Key Insights

### Single-Layer Perceptrons (SLP):
- Efficient for simple binary tasks.
- Limited by linear separability.

### Multi-Layer Perceptrons (MLP):
- Handles non-linear relationships effectively.
- Provides better generalization on complex datasets.

### Performance Gain:
- MLPs show improved accuracy and recall when compared to SLPs.
- The addition of hidden layers allows for learning more complex data representations.

## 📚 How to Use

1. Each example/task is self-contained with:
   - Input features
   - Weights & bias (user-defined or random)
   - Forward propagation logic
   - Output prediction (with probability)
2. Tasks Q11–Q13 include **training loops**, **loss tracking**, and **weight updates**.
3. Q13 includes **visualization** of optimizer performance over epochs.

> 💡 **Note**: All code snippets assume a Jupyter Notebook environment (uses `IPython.display.Image` for diagrams, though images are not included in this repo).
---

## 📄 License

This educational material is provided for learning purposes. Code is based on standard NumPy implementations of neural networks.

---

> ✨ **Ideal for students, educators, and practitioners learning the fundamentals of neural networks and backpropagation from scratch.**
