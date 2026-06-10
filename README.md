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
