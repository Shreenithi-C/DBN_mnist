Dimensionality Reduction on MNIST using Deep Belief Networks (DBN)

This project implements dimensionality reduction using Deep Belief Networks (DBN) to enhance feature extraction and digit classification on the MNIST dataset.

Overview

The MNIST dataset contains 70,000 images of handwritten digits (0–9), each of size 28x28 pixels. With 784 features per image, dimensionality reduction helps reduce complexity and improve performance.

In this project, we:
- Reduced input dimensionality using stacked Restricted Boltzmann Machines (RBMs)
- Built a Deep Belief Network (DBN) to learn hierarchical features
- Trained a classifier on the reduced data to achieve high accuracy

Technologies Used

- Python 
- PyTorch 
- NumPy
- Matplotlib

Model Architecture

- Input: 784-dimensional MNIST images
- Dimensionality reduction using RBM layers
- Fully connected neural network for classification
- Softmax output for digit prediction (0–9)

Results

- Achieved **94.36% accuracy** on the MNIST test set
- Reduced feature space without major loss of information
- Improved training efficiency with regularization


