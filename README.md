# Neural Network from Scratch
I built a Neural Network from Scratch - no TensorFlow, no PyTorch, just math and numpy :))
This Jupyter notebook walks through building a simple two-layer neural network **from scratch** (no deep-learning frameworks) in Python and training it on the MNIST “Digit Recognizer” dataset from Kaggle.

---

## Table of Contents

1. [Aim](#aim)  
2. [Dependencies](#dependencies)  

## Aim

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
