# Machine-Learning-Project-3
# 🧬 Breast Cancer Detection Using Microwave Sensor Data

This project involves building a simple **Neural Network (NN)** model to classify breast cancer presence based on **microwave sensor S-parameters**. The main goal is to distinguish between **a 20 mm tumor** and **no tumor** using signal features (S11 to S44). Additionally, the project explores the use of **PyCaret** to compare and automate model selection and evaluation.

---

## 🎯 Objective

- **Design a neural network** to classify tumor presence based on S-parameter data.
- **Evaluate alternative ML models** using the PyCaret library.
- Understand how PyCaret simplifies ML pipelines and improves productivity.

---

## 📦 Dataset Description

- The dataset contains sensor measurements (S11 to S44), including **magnitude and phase** values.
- The target variable represents tumor size:
  - `1`: 20 mm tumor
  - `0`: No tumor

---

## 🧩 Project Steps

### 1. 🔍 Dataset Analysis & Preprocessing

- Handle:
  - **Missing values (nulls)**
  - **Duplicate rows**
  - **Outliers**
- Normalize feature values
- Visualize **feature correlations** using a heatmap
- Ensure the dataset is clean for training and model evaluation

---

### 2. 🤖 Neural Network Model

#### 🔹 Architecture & Training

- **Task**: Binary classification
- **Input**: S-parameter features (S11–S44)
- **Output**: {0: No tumor, 1: 20 mm tumor}
- **Optimizer**: SGD (Stochastic Gradient Descent)
- **Learning Rate**: `0.001`
- **Loss Function**: Binary Cross Entropy or MSE
- **Evaluation Metrics**: Accuracy, F1 Score

---

### 3. 🧪 PyCaret Experimentation

#### 🔹 What is PyCaret?

[PyCaret](https://pycaret.org) is an open-source, low-code machine learning library that automates common tasks like model comparison, hyperparameter tuning, and evaluation.

#### 🔹 Tasks with PyCaret:

- Load and preprocess the dataset using PyCaret's preprocessing tools
- Use **Classification module** to:
  - Compare different models
  - Automatically tune hyperparameters
  - Evaluate results using cross-validation
- Comment on:
  - Model performance vs. your custom NN
  - Ease of use and time savings
  - PyCaret’s interpretability tools

---


## ✅ Deliverables

- Clean and well-documented Python code (Jupyter Notebook or `.py`)
- Visualizations: heatmaps, confusion matrix, learning curves, etc.
- Comparison of Neural Network vs. PyCaret results
- Written summary and justification of the best-performing model


---

## 🙌 Best of Luck!

Feel free to explore, experiment, and ask questions. Good luck with your classification project!

