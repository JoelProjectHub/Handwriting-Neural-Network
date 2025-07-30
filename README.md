# 📝 Handwriten Digits Neural Network (MNIST CNN)

This project implements a **Convolutional Neural Network (CNN)** to classify handwritten digits using the **MNIST dataset**.  
It includes a custom data loader for raw IDX files, a TensorFlow/Keras CNN model, and performance visualizations like training curves and a confusion matrix.

---

## 📂 Project Overview
- **Dataset:** MNIST (60,000 training + 10,000 test images)
- **Task:** Classify digits (0–9) from 28×28 grayscale images
- **Frameworks:** TensorFlow/Keras, NumPy, Matplotlib, scikit-learn
- **Accuracy:** ~99% on the test set

---

## ⚙️ Features
- ✅ CNN architecture with two convolutional layers and pooling
- ✅ Training & validation accuracy/loss plots
- ✅ Confusion matrix to visualize classification performance
- ✅ Misclassification analysis to identify weak spots

---

## 🧠 Model Architecture
- **Conv2D (32 filters, 3×3, ReLU)** – Low-level feature extraction  
- **MaxPooling2D (2×2)** – Downsampling  
- **Conv2D (64 filters, 3×3, ReLU)** – Higher-level feature extraction  
- **MaxPooling2D (2×2)** – Further downsampling  
- **Flatten** – Convert feature maps into a vector  
- **Dense (128, ReLU)** – Fully connected hidden layer  
- **Dense (10, Softmax)** – Output layer for digit classification  

---

## 📈 Performance
- Achieved **~99%** accuracy on the test set.
- Training vs. validation metrics are plotted to monitor overfitting.
- Confusion matrix highlights common misclassifications (e.g., 4 vs. 9).
