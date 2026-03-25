# 🧠 Binary Classification of Brain MRI Images for Tumor Detection

[![Python](https://img.shields.io/badge/Python-3.10-blue)]()
[![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-ff6f00)]()
[![Keras](https://img.shields.io/badge/Keras-Neural%20Networks-red)]()
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)]()
[![Status](https://img.shields.io/badge/Project-Completed-brightgreen)]()
[![License](https://img.shields.io/badge/License-MIT-lightgrey)]()

👤 Author: Nuru Siraj Mohammed  
🤖 Machine Learning & AI Graduate – Smart AI LLC  

---

## 📖 Project Overview

This project focuses on **binary classification of brain MRI images** to detect the presence of tumors using **deep learning techniques**.

The system classifies MRI scans into:
- ✅ Tumor
- ❌ No Tumor

This work demonstrates the application of **AI in medical imaging**, supporting early detection and decision-making.

---

## 🎯 Objectives

- Build a reliable **tumor detection model**
- Preprocess and enhance MRI images  
- Train deep learning models for classification  
- Evaluate performance using medical-relevant metrics  
- Visualize model decisions (Explainable AI)

---

## 📊 Dataset

- 🧠 Brain MRI Images  
- 📂 Classes:
  - Tumor
  - No Tumor  
- 🖼️ Format: JPEG/PNG images  

---

## 🏗️ Project Structure
brain-mri-tumor-classification/
│
├── data/
│ ├── train/
│ ├── test/
│
├── notebooks/
│ └── mri_classification.ipynb
│
├── src/
│ ├── preprocessing.py
│ ├── model.py
│ ├── train.py
│
├── models/
│ └── best_model.h5
│
├── results/
│ ├── confusion_matrix.png
│ ├── accuracy_curve.png
│ ├── loss_curve.png
│ ├── sample_predictions.png
│
├── requirements.txt
└── README.md


---

## ⚙️ Methodology

### 🔹 Data Preprocessing
- Image resizing (e.g., 224×224)
- Normalization
- Data augmentation (rotation, flipping, zoom)
- Noise reduction

---

### 🔹 Model Architecture

#### ✅ Baseline Model
- CNN (Convolutional Neural Network)
- ReLU activation
- MaxPooling layers
- Fully connected layers

#### ✅ Advanced Model
- Transfer Learning (ResNet50 / VGG16)
- Fine-tuning top layers
- Dropout for regularization

---

## 🧠 Training Strategy

- Train/Validation/Test split  
- Early stopping  
- Learning rate tuning  
- Batch normalization  

---

## 📈 Evaluation Metrics

| Metric     | Description |
|------------|------------|
| Accuracy   | Overall correctness |
| Precision  | True positive reliability |
| Recall     | Sensitivity (critical in healthcare) |
| F1-score   | Balance between precision & recall |

---
