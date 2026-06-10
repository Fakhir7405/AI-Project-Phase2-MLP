# 🤖 AI Project — MNIST Digit Classification (Phase 2)

---

## 📌 Project Overview

This project focuses on **image classification of handwritten digits using the MNIST dataset**.  
It is an academic machine learning and deep learning project comparing a traditional neural network (MLP) with a Convolutional Neural Network (CNN).

---

## 📊 Dataset Used — MNIST

The MNIST dataset contains **70,000 grayscale images of handwritten digits (0–9)**, each of size **28×28 pixels**.

- Training set: 60,000 images  
- Test set: 10,000 images  
- Features: 784 pixel values (flattened)  
- Target: Digit label (0–9)  

### Sources:
- TensorFlow / Keras  
- Yann LeCun MNIST dataset  
- Kaggle dataset  

---

## 🧠 Models Implemented

### 1️⃣ Multi-Layer Perceptron (MLP)
- Implemented using `sklearn.neural_network.MLPClassifier`
- Architecture: `784 → 256 → 128 → 64 → 10`
- Activation: ReLU
- Optimizer: Adam
- Used as a **baseline model for comparison**

---

### 2️⃣ Convolutional Neural Network (CNN)
- Implemented using TensorFlow / Keras
- Architecture:

Conv2D → MaxPooling → Conv2D → MaxPooling → Flatten → Dense → Dropout → Output

- Optimizer: Adam
- Loss Function: Categorical Cross-Entropy
- Designed specifically for image feature extraction and classification

---

## 📈 Evaluation Metrics

Both models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📊 Results

### 🔹 MLP
- Test Accuracy: ~97%  
- Some misclassifications observed (e.g., visually similar digits)

### 🔹 CNN
- Test Accuracy: ~99%  
- Better generalization  
- Fewer misclassifications  
- Stable convergence during training  

---

## ⚖️ Comparison

- MLP is a strong baseline but struggles with spatial patterns.
- CNN captures edges, curves, and stroke structures effectively.
- CNN significantly outperforms MLP on MNIST classification.

---

## 🎯 Conclusion

The MNIST dataset was successfully modeled using both approaches.  
MLP achieved strong baseline performance (~97%), while CNN achieved superior accuracy (~99%) due to its ability to learn spatial features.

**Final conclusion: CNN is the better model for handwritten digit classification.**

---