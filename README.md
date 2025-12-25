# MNIST Neural Network from Scratch (NumPy)

This repository contains a Jupyter notebook implementing a fully-connected neural network trained on the MNIST handwritten digits dataset using only NumPy.

No high-level machine learning libraries (PyTorch, TensorFlow models, scikit-learn) are used for the network itself. All forward propagation, backpropagation, and gradient descent are implemented manually.

## Overview

1. Architecture: `784 -> 16 -> 16 -> 10`
2. Activations: ReLU (hidden layers), Softmax (output)
3. Loss: Cross-entropy
4. Optimization: Batch gradient descent
5. Accuracy: ~95% on test data
6. Implementation style: Object-oriented (single `NeuralNetwork` class)
7. One Jupyter notebook (`.ipynb`) containing:
  - Data loading and preprocessing
  - Neural network implementation from scratch
  - Training loop
  - Loss curve visualization
  - Accuracy evaluation
  - Random test image predictions with plots

## Dependencies

```bash
pip install -r requirements.txt
```
