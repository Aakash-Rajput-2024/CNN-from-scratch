
# CNN-from-scratch

## Overview

**CNN from Scratch using NumPy**  
This project implements a Convolutional Neural Network (CNN) from scratch using **pure NumPy**, trained on the **MNIST dataset** for handwritten digit classification.

> No PyTorch, no TensorFlow (except for dataset loading) — everything from forward pass to backpropagation is handcrafted.

---

## Features

- Manual data preprocessing (reshaping, normalizing)
- Custom implementation of:
  - Convolution layer
  - Max pooling
  - ReLU activation
  - Fully connected (Dense) layer
  - Softmax output
  - Batch Normalization (forward and backward)
  - Cross-entropy loss
- Full backpropagation pipeline
- Gradient updates using Stochastic Gradient Descent (SGD)
- Evaluation on MNIST test data

---

## Dependencies

- Python 3.7+
- NumPy
- TensorFlow (only for loading MNIST dataset)
- Matplotlib (optional, for visualization)
- psutil (for memory monitoring)

Install them using:

```bash
pip install numpy tensorflow matplotlib psutil
```

---

## Customization

You can tweak:
- Learning rate
- Batch size
- Network architecture

These modifications may improve performance depending on training conditions.

---

## Learning Objectives

This project is ideal for:

- Understanding the internals of Convolutional Neural Networks
- Learning how forward and backward propagation work
- Building a strong intuition for layer-wise computations and gradients

---

## TODO (Optional Improvements)

- Better learning rate scheduler
- Use momentum or Adam optimizers


---

## Author

**Aakash Rajput**  
[LinkedIn](https://www.linkedin.com/in/aakash-rajput-5191b7313/)
