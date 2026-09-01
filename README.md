# 🧠 Machine Learning — KNTU Homework Collection

<p align="center">
  <strong>Machine Learning Homework Solutions</strong><br>
  <sub>Implementation • Mathematical Foundations • Deep Learning • Transformers</sub>
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge\&logo=pytorch\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge\&logo=latex\&logoColor=white)

</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-homeworks">Homeworks</a> •
  <a href="#-topics-covered">Topics</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-repository-structure">Structure</a>
</p>

---

## 📌 Overview

This repository contains my solutions and implementations for the **Machine Learning** course assignments at **K. N. Toosi University of Technology (KNTU)**.

The main goal of these assignments was not only to apply existing machine learning libraries, but also to develop a deeper understanding of the **mathematical foundations, internal mechanisms, implementation details, and practical behavior of modern machine learning models**.

The repository gradually moves from classical machine learning concepts toward modern deep learning architectures, including **attention mechanisms and Transformer-based language models**.

> **From mathematical foundations → algorithmic implementation → deep learning → Transformers.**

---

## 🎯 Learning Objectives

Throughout these assignments, the focus was on:

* Understanding the mathematical foundations of machine learning
* Implementing algorithms rather than treating models as black boxes
* Working with numerical optimization and gradient-based learning
* Understanding neural network architectures at a lower level
* Implementing and analyzing convolutional operations
* Working with PyTorch and tensor-based computation
* Understanding attention mechanisms
* Implementing Multi-Head Self-Attention
* Building Transformer components
* Training and experimenting with a miniature GPT-style language model
* Understanding text generation and sampling strategies
* Analyzing experimental results and model behavior

---

# 📚 Homeworks

## HW1 — Machine Learning Foundations

The first assignment focuses on fundamental machine learning concepts and establishes the mathematical and computational foundation for the later assignments.

### Core topics

* Supervised Learning
* Regression
* Classification
* Optimization
* Gradient-based learning
* Model evaluation
* Mathematical formulation of learning problems

### Main goal

Develop an understanding of **how learning algorithms work internally**, rather than relying exclusively on high-level APIs.

---

## HW2 — Neural Networks & Convolutional Operations

The second assignment moves toward neural networks and lower-level deep learning implementation.

### Core topics

* Neural network computation
* Convolutional operations
* Tensor manipulation
* PyTorch
* Forward propagation
* Backpropagation
* Gradient computation
* Parameter analysis
* Bottleneck architectures

### Implementation focus

Parts of the assignment require implementing neural-network operations at a lower level, providing a more detailed view of what happens inside deep learning frameworks.

---

## HW3 — Machine Learning / Deep Learning

HW3 continues the progression toward more advanced machine learning and deep learning concepts.

### Focus areas

* Model implementation
* Experimental analysis
* Training and evaluation
* Neural network concepts
* Computational reasoning
* Result interpretation

The assignment combines theoretical understanding with practical implementation.

---

## HW4 — Advanced Machine Learning

HW4 extends the previous concepts toward more advanced machine learning and deep learning techniques.

The emphasis is placed on:

* Practical model development
* Experiment design
* Training procedures
* Model analysis
* Understanding the effect of architectural and hyperparameter choices

---

## HW5 — Attention, Transformers & MiniGPT

The final assignment represents the transition from conventional deep learning toward modern sequence modeling and Transformer-based architectures.

### Core topics

* Tokenization
* Embeddings
* Self-Attention
* Multi-Head Self-Attention
* Transformer Blocks
* Causal Language Modeling
* MiniGPT
* Autoregressive generation
* Sampling strategies

### Conceptual pipeline

```text
Raw Text
   │
   ▼
Tokenization
   │
   ▼
Token Embeddings
   │
   ▼
Positional Information
   │
   ▼
Multi-Head Self-Attention
   │
   ▼
Transformer Block
   │
   ▼
Language Modeling Head
   │
   ▼
Next-Token Prediction
   │
   ▼
Autoregressive Generation
```

The objective is to understand the main components behind modern Transformer-based language models and how they work together to perform sequence generation.

---

# 🧩 Topics Covered

| Area            | Topics                                   |
| --------------- | ---------------------------------------- |
| Classical ML    | Regression, Classification, Optimization |
| Optimization    | Gradient Descent, Gradient Computation   |
| Neural Networks | Forward Pass, Backpropagation            |
| Deep Learning   | Neural Network Architectures             |
| CNNs            | Convolution, Tensor Operations           |
| PyTorch         | Tensors, Modules, Autograd               |
| Attention       | Self-Attention, Query/Key/Value          |
| Transformers    | Multi-Head Attention, Transformer Blocks |
| NLP             | Tokenization, Embeddings                 |
| Language Models | Causal LM, Next-Token Prediction         |
| Generative AI   | Autoregressive Generation, Sampling      |

---

# 🛠️ Tech Stack

### Programming

* **Python**

### Scientific Computing

* **NumPy**

### Deep Learning

* **PyTorch**

### Interactive Development

* **Jupyter Notebook**

### Documentation

* **LaTeX**

---

# 📂 Repository Structure

```text
KNTU-ML-HWs/
│
├── HW1-IML/
│   ├── Python / Jupyter implementations
│   ├── Reports
│   └── Assignment materials
│
├── HW2-IML/
│   ├── Python / Jupyter implementations
│   ├── Reports
│   └── Assignment materials
│
├── HW3-IML/
│   ├── Python / Jupyter implementations
│   ├── Reports
│   └── Assignment materials
│
├── HW4-IML/
│   ├── Python / Jupyter implementations
│   ├── Reports
│   └── Assignment materials
│
├── HW5-IML/
│   ├── Python / Jupyter implementations
│   ├── Reports
│   └── Assignment materials
│
└── README.md
```

---

# 🔬 Implementation Philosophy

A major principle throughout this repository is:

> **Understand the mechanism, not just the API.**

Whenever possible, the assignments are approached by examining the underlying mathematics and computational operations behind the models.

This includes reasoning about:

* Mathematical formulations
* Tensor dimensions
* Forward computations
* Gradient flow
* Parameterization
* Optimization
* Architectural design
* Model behavior

This approach helps bridge the gap between using machine learning libraries and understanding what those libraries are actually doing underneath.

---

# 📈 Learning Progression

The repository represents a gradual progression through the machine learning stack:

```text
Mathematical Foundations
        │
        ▼
Classical Machine Learning
        │
        ▼
Optimization & Gradients
        │
        ▼
Neural Networks
        │
        ▼
Convolutional Operations
        │
        ▼
Deep Learning with PyTorch
        │
        ▼
Self-Attention
        │
        ▼
Multi-Head Attention
        │
        ▼
Transformer Architecture
        │
        ▼
MiniGPT
        │
        ▼
Autoregressive Text Generation
```

---

# 🎓 Academic Context

**Course:** Machine Learning
**Institution:** K. N. Toosi University of Technology (KNTU)
**Repository:** Homework Solutions & Implementations

---

# 👨‍💻 Author

**Hamed Behroozi**

Artificial Intelligence Student
K. N. Toosi University of Technology

---

<p align="center">
  <sub>Built as part of the journey from understanding machine learning algorithms to implementing modern deep learning architectures.</sub>
</p>
