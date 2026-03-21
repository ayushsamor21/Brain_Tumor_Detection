# 🧠 Brain Tumor Detection using Deep Learning

## 📌 Overview

This project is a **Deep Learning-based Brain Tumor Detection system** that classifies MRI images into different tumor categories using a **Convolutional Neural Network (CNN)**.

The model analyzes brain MRI scans and predicts whether a tumor is present and, if so, its type.

---

## 🎯 Objective

* Automate brain tumor detection from MRI images
* Classify tumors into multiple categories
* Learn and apply core Deep Learning concepts (CNN, preprocessing, training)

---

## 🗂️ Dataset

The dataset is organized into two main folders:

```
Dataset/
│
├── Training/
│   ├── glioma_tumor/
│   ├── meningioma_tumor/
│   ├── no_tumor/
│   └── pituitary_tumor/
│
├── Testing/
│   ├── glioma_tumor/
│   ├── meningioma_tumor/
│   ├── no_tumor/
│   └── pituitary_tumor/
```

Each folder contains MRI images corresponding to its class.

---

## ⚙️ Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Scikit-learn

---

## 🧠 Model Architecture

The model is a Convolutional Neural Network (CNN) consisting of:

* Convolutional Layers (feature extraction)
* MaxPooling Layers (downsampling)
* Flatten Layer
* Dense Layers (classification)
* Dropout (regularization)

---
