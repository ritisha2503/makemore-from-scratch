# makemore-from-scratch

A complete from-scratch implementation of character-level neural language models inspired by Andrej Karpathy’s **makemore** series.
This repository progressively builds deep learning models from simple probabilistic approaches to modern neural architectures using **PyTorch**.

The project focuses on understanding *how neural networks actually work under the hood* by implementing everything step-by-step instead of relying on high-level abstractions.

---

## 📚 Topics Covered

* Bigram Language Models
* Probability & Frequency-Based Modeling
* Neural Network Fundamentals
* Manual Backpropagation
* Multi-Layer Perceptrons (MLPs)
* Batch Normalization
* Learning Rate Scheduling
* Recurrent Neural Networks (RNNs)
* Convolutional Neural Networks (CNNs)
* WaveNet-Style Architectures
* Character-Level Text Generation
* Embeddings & Context Windows
* PyTorch Tensor Operations

---

## 🧠 Implementations

### 1. Bigram Model

Built a statistical character-level language model using frequency counts and probability matrices.

### 2. Neural Bigram Model

Implemented a trainable neural network version using PyTorch tensors and gradient descent.

### 3. MLP Language Model

Created a multi-layer perceptron with character embeddings and hidden layers for next-character prediction.

### 4. Manual Backpropagation

Derived and implemented gradients manually to deeply understand computational graphs and optimization.

### 5. Batch Normalization

Implemented batch normalization and analyzed its effect on training stability and convergence.

### 6. Recurrent Neural Networks (RNNs)

Built sequential models capable of learning temporal dependencies in text generation tasks.

### 7. Convolutional Neural Networks (CNNs)

Explored temporal convolutions for sequence modeling and efficient context extraction.

### 8. WaveNet-Style Model

Implemented hierarchical dilated convolution blocks inspired by WaveNet architectures for improved sequence prediction.

---

## ⚙️ Tech Stack

* Python
* PyTorch
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 🎯 Goals of the Project

* Understand neural networks from first principles
* Learn how backpropagation works internally
* Implement language models without relying on high-level APIs
* Explore the evolution from simple statistical models to deep architectures
* Gain intuition for training dynamics and optimization

---

## 🚀 Running the Project

Clone the repository:

```bash
git clone https://github.com/ritisha2503/makemore-from-scratch.git
cd makemore-from-scratch
```

Install dependencies:

```bash
pip install torch numpy matplotlib jupyter
```

Run the notebooks/scripts to train and generate names:

```bash
jupyter notebook
```

---

## ✨ Sample Output

Example generated names from trained models:

```text
elyse
calield
cala
quaven
izaia
hanayi
smaire
elyza
damiyiah
josalino
franzosway
muhamned
exxlly
daela
pahlia
zylah
leelany
iyomi
behmona
ashvin
```

---

## 📖 Reference

Inspired by Andrej Karpathy’s legendary neural networks series:

* makemore
* Neural Networks: Zero to Hero

---

## 🌱 What I Learned

This project helped me develop a strong intuition for:

* gradient-based optimization
* tensor operations
* neural network training
* sequence modeling
* architecture design
* debugging deep learning systems
* implementing ML systems from scratch

---

## 📌 Repository Structure

```text
bigram/
mlp/
backprop/
cnn/
dataset/
```

---

## ⭐ Acknowledgements

Huge thanks to Andrej Karpathy for creating one of the most intuitive and educational deep learning series available online.
