# 🧠 Digit Recognition Neural Network

This repository contains a Jupyter Notebook that demonstrates the creation and training of a simple neural network for handwritten digit recognition using the MNIST dataset. The project explores the impact of adding a hidden layer on model accuracy.

---

## 📑 Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Visualization](#visualization)
- [Technologies Used](#technologies-used)

---

## 📌 Project Overview

The goal of this project is to build and train a neural network capable of classifying handwritten digits (0–9). It starts with a basic single-layer neural network and then enhances it by adding a hidden layer to observe improvements in predictive performance. The process includes:

- Data loading
- Preprocessing
- Model definition
- Training
- Evaluation
- Visualization using a confusion matrix

---

## 📊 Dataset

The project utilizes the **MNIST (Modified National Institute of Standards and Technology)** dataset — a large, standard dataset used for image classification.

- **Training Data**: 60,000 images  
- **Test Data**: 10,000 images  
- **Image Format**: 28x28 pixel grayscale images

---

## 🏗️ Model Architecture

### 🔸 Single-Layer Model
- **Input Layer**: Flattened 28×28 pixel images (784 features)
- **Output Layer**: Dense layer with 10 neurons (digits 0–9), sigmoid activation
- **Compilation**: 
  - Optimizer: `adam`  
  - Loss: `sparse_categorical_crossentropy`  
  - Metrics: `accuracy`
- **Training**: 5 epochs

### 🔹 Two-Layer Model (with Hidden Layer)
- **Input Layer**: Flattened 28×28 pixel images (784 features)
- **Hidden Layer**: Dense layer with 100 neurons, `relu` activation
- **Output Layer**: Dense layer with 10 neurons, `sigmoid` activation
- **Compilation**: 
  - Optimizer: `adam`  
  - Loss: `sparse_categorical_crossentropy`  
  - Metrics: `accuracy`
- **Training**: 5 epochs

---

## ✅ Results

The addition of a hidden layer significantly improved accuracy:

| Model              | Accuracy     |
|--------------------|--------------|
| Single-Layer Model | ~92.65%      |
| Two-Layer Model    | ~97.54%      |

This demonstrates that even simple increases in model complexity can yield substantial improvements in performance.

---

## 📈 Visualization

Confusion matrices are used to evaluate model performance, showing the distribution of correct and incorrect predictions for each digit. This provides insight into which digits are more likely to be misclassified.

---

## 🧰 Technologies Used

- **Python 3**
- **TensorFlow & Keras** – Building and training neural networks
- **NumPy** – Numerical operations
- **Matplotlib** – Plotting and visualization
- **Seaborn** – Enhanced plots, especially for confusion matrix

---
