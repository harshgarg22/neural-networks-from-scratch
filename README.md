# Neural Networks and Optimizers from Scratch

This project implements the core components of neural networks and several essential optimization techniques using only **Python** and **NumPy**. The goal was to build a rock-solid understanding of the underlying mathematics for better knowledge and technical interview preparation.

## Implemented Core Components

A basic skeletal code was followed across all the notebooks that implements the following building blocks:

* **Forward Pass**
* **Backward Pass (Backpropagation)** 
* **ReLU Activation** 
* **Softmax Activation combined with Cross Entropy Loss**



## Implemented Optimization Algorithms

Various gradient descent techniques were built from scratch to manage the weight updates during training:

| Optimizer | Core Mechanism |
| :--- | :--- |
| **Vanilla Gradient Descent** | Standard descent using a fixed learning rate. |
| **Learning Rate Decay** | Gradually reduces the learning rate over epochs. |
| **Momentum** | Uses a velocity term to accelerate training. |
| **AdaGrad** | Adaptive learning rates per parameter based on past gradients. |
| **RMSProp** | Uses an exponentially decaying average of squared gradients. |
| **AdaDelta** | An extension that removes the need for a manually set global learning rate. |

## Motivation

The primary purpose of this repository is **deep learning interview preparation** and **fundamental knowledge reinforcement**. By avoiding high-level frameworks (like PyTorch or TensorFlow) and writing the code manually, I ensured a comprehensive understanding of the math and calculus behind the entire training process.

## Source

The concepts and techniques implemented here were heavily influenced by the educational content provided by **Vizuara**.

* **Source:** [https://www.youtube.com/@vizuara](https://www.youtube.com/@vizuara)