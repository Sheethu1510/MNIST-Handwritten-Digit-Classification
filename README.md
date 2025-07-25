# MNIST Handwritten Digit Classification with TensorFlow

This project demonstrates a simple neural network built using TensorFlow and Keras to classify handwritten digits (0–9) from the MNIST dataset.

## Overview

The goal is to build and train a feedforward neural network that can accurately classify grayscale images of digits drawn by hand. This is a foundational project in deep learning and computer vision.

## Dataset

- **MNIST**: 60,000 training images and 10,000 testing images of digits from 0 to 9.
- Each image is a 28x28 grayscale pixel grid.

## Model Architecture

- Input Layer: Flatten (28x28 → 784 features)
- Hidden Layer: Dense(128) with ReLU activation
- Output Layer: Dense(10) with softmax activation (for multi-class classification)

