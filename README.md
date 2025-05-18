# Neural Network from Scratch
I built a Neural Network from Scratch - no TensorFlow, no PyTorch, just math and numpy :))
This Jupyter notebook walks through building a simple two-layer neural network **from scratch** (no deep-learning frameworks) in Python and training it on the MNIST “Digit Recognizer” dataset from Kaggle.

---

## Table of Contents

1. [Introduction](#introduction)  
2. [Dependencies](#dependencies)  
3. [Dataset & Preprocessing](#dataset--preprocessing)  
4. [Model Architecture](#model-architecture)  
5. [Implementation Details](#implementation-details)  
   - Layer definitions  
   - Activation functions (ReLU, Softmax)  
   - One-hot encoding  
6. [Forward & Backward Propagation](#forward--backward-propagation)  
7. [Gradient Descent Training](#gradient-descent-training)  
8. [Results](#results)  
9. [Usage](#usage)  
10. [License](#license)  

---

## Introduction

This notebook demonstrates how to:

- Load and preprocess the MNIST digits dataset (42 000 training examples, 784 input features each)  
- Initialize network parameters with **He initialization**  
- Implement **ReLU** and **Softmax** activation functions  
- Perform **vectorized** forward and backward passes  
- Train using **batch gradient descent** (learning rate 0.1, 1 001 iterations)  
- Evaluate accuracy on the training set  

---

## Dependencies

- Python 3.x  
- [numpy](https://numpy.org/)  
- [pandas](https://pandas.pydata.org/)  
- [matplotlib](https://matplotlib.org/)  

Install via:

```bash
pip install numpy pandas matplotlib
