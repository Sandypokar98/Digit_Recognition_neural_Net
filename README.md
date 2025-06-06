# 🧠 Digit Recognition Neural Network

This project implements a neural network to recognize handwritten digits using the MNIST dataset. The model is developed and trained in a Jupyter Notebook using TensorFlow/Keras.

## 📁 Files

- `Digit_Recognition_Neural_Net.ipynb`: Main notebook with data loading, preprocessing, model building, training, and evaluation.
- `README.md`: Project documentation.

## 🔍 Overview

- Load and visualize the MNIST dataset
- Preprocess and normalize input data
- Build a feedforward neural network using Keras
- Train and evaluate the model
- Visualize predictions and performance

## 📊 Dataset

- **Source**: MNIST Digits (from Keras datasets)
- **Details**: 70,000 grayscale 28x28 images of digits (0–9)
  - Training: 60,000
  - Testing: 10,000

## 🧱 Model Architecture

- Input Layer: 784 neurons (28×28 flattened)
- Hidden Layers: Dense layers with ReLU activation
- Output Layer: 10 neurons (softmax for classification)

## 🧪 Tools & Libraries

- Python 3.x
- Jupyter Notebook
- TensorFlow / Keras
- NumPy
- Matplotlib
