# Neural Networks From Scratch 🧠

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Latest-orange.svg)](https://numpy.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive repository demonstrating the implementation of fundamental Neural Network architectures and optimization algorithms from the ground up, without relying on high-level deep learning frameworks like TensorFlow or PyTorch.

## 🚀 Project Overview

This project serves as a deep dive into the mathematical foundations of machine learning. By implementing algorithms from scratch, I've explored the inner workings of parameter initialization, propagation cycles, and optimization strategies.

### 📂 Key Implementations

#### 1. MNIST Digit Recognizer
A multi-layer perceptron (MLP) built to classify handwritten digits from the famous MNIST dataset.
- **Architecture**: Input Layer (784 neurons) → Hidden Layer (ReLU) → Output Layer (Softmax).
- **Manual Implementation**:
  - **Forward Propagation**: Linear transformations and activation functions.
  - **Backward Propagation**: Deriving gradients for weights and biases using calculus (chain rule).
  - **Optimization**: Standard Gradient Descent.
- **Performance**: Achieved **~90% accuracy** on the validation set using purely NumPy-based operations.

#### 2. Salary Prediction using Gradient Descent
A regression-based approach to predict salary based on years of experience, focusing on the mechanics of optimization.
- **Focus**: Understanding the convergence of cost functions.
- **Concept**: Implementing and visualizing the Gradient Descent algorithm for simple linear models.

## 🛠 Tech Stack

- **Language**: Python
- **Libraries**: 
  - `NumPy`: For high-performance matrix computations.
  - `Pandas`: For data manipulation and preprocessing.
  - `Matplotlib`: For visualizing training progress and data distributions.
- **Environment**: Jupyter Notebooks / Google Colab.

## 🧠 Core Concepts Mastered

- **Mathematical Foundations**: Partial derivatives, Matrix calculus, and Linear Algebra.
- **Activation Functions**: ReLU, Softmax, Sigmoid.
- **Optimization**: Cost functions (MSE, Cross-Entropy), Learning rate scheduling, and Gradient Descent.
- **Model Evaluation**: Accuracy metrics, validation splitting, and prediction visualization.

## 🏃 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/neural-networks-from-scratch.git
   ```
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib
   ```
3. Open the Jupyter notebooks:
   ```bash
   jupyter notebook
   ```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Developed with a passion for understanding the "Why" behind the "How" in Machine Learning.*
