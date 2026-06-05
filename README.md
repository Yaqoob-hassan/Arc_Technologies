<div align="center">

# 🧠 Arc Technologies — Machine Learning Portfolio

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)](LICENSE)

> A curated collection of end-to-end Machine Learning projects spanning classification, regression, and deep learning — built as part of the **Arc Technologies** internship / training program.

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Projects](#-projects)
  - [Email Spam Detection](#-email-spam-detection)
  - [House Price Prediction](#-house-price-prediction)
  - [Iris Flower Classification](#-iris-flower-classification)
  - [MNIST Digit Recognition](#-mnist-digit-recognition)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Repository Structure](#-repository-structure)
- [Author](#-author)

---

## 🔍 Overview

This repository contains four machine learning projects covering core concepts in supervised learning, natural language processing, and computer vision. Each project follows a complete ML workflow:

```
Data Collection → EDA → Preprocessing → Model Training → Evaluation → Insights
```

All projects are implemented in **Jupyter Notebooks** using Python and the standard ML ecosystem (scikit-learn, TensorFlow/Keras, pandas, matplotlib).

---

## 📁 Projects

---

### 📧 Email Spam Detection

**Folder:** `Email_Spam_Project/`

**Objective:** Build a binary text classifier to distinguish spam emails from legitimate (ham) ones.

| Detail | Info |
|--------|------|
| **Type** | Binary Classification / NLP |
| **Dataset** | SMS Spam Collection / Custom Email Dataset |
| **Algorithms** | Multinomial Naive Bayes, Logistic Regression |
| **Techniques** | TF-IDF Vectorization, Text Preprocessing, Stop-word Removal |

**Key Highlights:**
- Text cleaning pipeline (lowercasing, punctuation removal, stemming)
- TF-IDF feature extraction to convert raw text into numerical vectors
- Compared multiple classifiers with precision, recall, F1-score evaluation
- Focused on minimizing false negatives (missed spam) while maintaining inbox integrity

---

### 🏠 House Price Prediction

**Folder:** `House_Price_Prediction/`

**Objective:** Predict residential property prices using structural and locational features via regression models.

| Detail | Info |
|--------|------|
| **Type** | Regression |
| **Dataset** | Housing dataset (Kaggle / UCI) |
| **Algorithms** | Linear Regression, Ridge, Lasso, Random Forest Regressor |
| **Metrics** | MAE, MSE, RMSE, R² Score |

**Key Highlights:**
- Comprehensive Exploratory Data Analysis (EDA) with correlation heatmaps
- Feature engineering and outlier treatment
- Hyperparameter tuning for optimal model performance
- Visualized predicted vs. actual prices to assess model fit

---

### 🌸 Iris Flower Classification

**Folder:** `Iris_Flower_Project/`

**Objective:** Classify iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — based on sepal and petal measurements.

| Detail | Info |
|--------|------|
| **Type** | Multi-class Classification |
| **Dataset** | UCI Iris Dataset (150 samples, 4 features, 3 classes) |
| **Algorithms** | K-Nearest Neighbors, SVM, Decision Tree, Logistic Regression |
| **Metrics** | Accuracy, Confusion Matrix, Classification Report |

**Key Highlights:**
- Pairplot and distribution analysis to visualize feature separability
- Decision boundary visualization for intuitive model understanding
- Cross-validation to ensure generalizable results
- Ideal introductory project demonstrating the full ML pipeline

---

### 🔢 MNIST Digit Recognition

**Folder:** `Mnist_Project/`

**Objective:** Recognize handwritten digits (0–9) from grayscale 28×28 pixel images using deep learning.

| Detail | Info |
|--------|------|
| **Type** | Multi-class Image Classification |
| **Dataset** | MNIST (70,000 images — 60K train / 10K test) |
| **Architecture** | Convolutional Neural Network (CNN) |
| **Framework** | TensorFlow / Keras |

**Key Highlights:**
- Image normalization and reshaping for CNN input
- Conv2D → MaxPooling → Flatten → Dense architecture
- Achieved high test accuracy with dropout regularization
- Visualized misclassified samples for error analysis

---

## 🛠 Tech Stack

| Category | Libraries / Tools |
|----------|-------------------|
| **Language** | Python 3.8+ |
| **Notebooks** | Jupyter Notebook |
| **Data Manipulation** | NumPy, pandas |
| **Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | scikit-learn |
| **Deep Learning** | TensorFlow, Keras |
| **NLP** | NLTK, scikit-learn (TF-IDF) |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8+ and pip installed.

### 1. Clone the Repository

```bash
git clone https://github.com/Yaqoob-hassan/Arc_Technologies.git
cd Arc_Technologies
```

### 2. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras nltk jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Navigate to any project folder and open the `.ipynb` file to get started.

---

## 📂 Repository Structure

```
Arc_Technologies/
│
├── Email_Spam_Project/
│   └── Email_Spam_Detection.ipynb
│
├── House_Price_Prediction/
│   └── House_Price_Prediction.ipynb
│
├── Iris_Flower_Project/
│   └── Iris_Flower_Classification.ipynb
│
├── Mnist_Project/
│   └── MNIST_Digit_Recognition.ipynb
│
└── README.md
```

---

## 👨‍💻 Author

**Yaqoob Hassan**
Machine Learning Enthusiast | Arc Technologies

[![GitHub](https://img.shields.io/badge/GitHub-Yaqoob--hassan-181717?style=flat-square&logo=github)](https://github.com/Yaqoob-hassan)

---

<div align="center">

*Built with ❤️ during the Arc Technologies ML Program*

⭐ If you find this repository helpful, please consider giving it a star!

</div>
