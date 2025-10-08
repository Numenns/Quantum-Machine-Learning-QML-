# What Does Quantum Bring to ML?
- **Superposition and entanglement:** allow representing many states at once, expanding the data space.  
- **Quantum interference:** helps highlight meaningful patterns and reduce noise.  
- **Potential advantages:** faster computation, richer data representations, and new learning methods.  
- **Current limitations:** quantum computers are still small and noisy (we are in the **NISQ** — *Noisy Intermediate-Scale Quantum* — era).  

---

## Types of QML Models

| Type | Brief Description |
|------|-------------------|
| **Hybrid Classical–Quantum** | Combine classical components (like optimization and training) with parameterized quantum circuits. These are the most common today. |
| **Quantum Kernels** | Map classical data into quantum states and use quantum inner products to perform classification. |
| **VQC (Variational Quantum Classifiers)** | Quantum circuits with tunable parameters that learn to classify data based on measurements. |

---

## Practical Goal
Get familiar with tools such as **Qiskit**, **PennyLane**, or **TensorFlow Quantum**, and try simple experiments using **quantum simulators**.  
These experiments help understand how classical and quantum components work together in hybrid models.

---

## Recommended Videos

[![Quantum Machine Learning Explained](https://img.youtube.com/vi/NqHKr9CGWJ0/maxresdefault.jpg)](https://www.youtube.com/watch?v=NqHKr9CGWJ0)  

[![Hybrid Quantum–Classical Machine Learning](https://img.youtube.com/vi/tKb2tHm8DC0/maxresdefault.jpg)](https://www.youtube.com/watch?v=tKb2tHm8DC0)  
---

## Explainig the Code

[This code](https://github.com/Numenns/QSVC_using_Qiskit.ipynb) organizes and separates customer data using a mix of classical machine learning and quantum computing.

Step by step:

Loads customer data — such as income, spending, and credit history.
It also includes a column showing whether each customer defaulted (did not pay) or did not default (paid normally).

Prepares the data — cleans it, normalizes it, and splits it into two parts:

one part to train the model,

another part to test it.

Reduces the data (using PCA) to keep only the most important features that help distinguish customers.

Uses a quantum model — this model converts the data into a quantum representation and learns how to divide the customers into two groups:

those likely to default,

and those likely to pay.

Evaluates how well the model learned to separate the groups.
The results (94% accuracy, 0.96 AUC) show that it effectively divides the data between the two types of customers.

In short, this program takes customer data, analyzes it, and uses a quantum model to learn how to separate who will pay and who will not. It does not sort the data like a list but divides it into clear groups based on behavior.
