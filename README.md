# Handwritten Character & Digit Classifier

## 📌 Overview

This project implements a multi-model pipeline for handwritten character and digit classification using EMNIST/MNIST dataset.

---

## ⚙️ Tasks Implemented

### 1. Edge Detection

* Manual implementation of:

  * Sobel Operator
  * Laplacian Operator
* Compared results with OpenCV built-in functions

### 2. Fully Connected Neural Networks

* Model 1: No hidden layer
* Model 2: One hidden layer
* Compared accuracy and loss

### 3. CNN from Scratch

* Conv2D → MaxPooling → Dense
* Used Batch Normalization and Dropout
* Analyzed overfitting over 20 epochs

### 4. Transfer Learning (MobileNetV2)

* Used pretrained model with frozen base
* Fine-tuned top layers

### 5. Mini-VGG Architecture

* Implemented 2 VGG-style blocks
* Compared performance with CNN & MobileNetV2

### 6. Feature Map Visualization

* Visualized intermediate convolution outputs

---

## 📊 Results Summary

* CNN significantly outperformed FC networks
* MobileNetV2 achieved highest accuracy
* Dropout reduced overfitting
* Feature maps showed hierarchical feature learning

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

---

## 📁 Dataset

* MNIST / EMNIST dataset

---

## 👨‍💻 Author

Farman
