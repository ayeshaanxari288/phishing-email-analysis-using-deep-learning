# phishing-email-analysis-using-deep-learning
Comparative analysis of Logistic Regression, FNN, RNN, and LSTM models for phishing email detection using NLP and deep learning techniques.

# Comparative Analysis of Neural Architectures for Phishing Emails

## Overview

This project focuses on phishing email detection using both traditional machine learning and deep learning techniques. The objective is to compare progressively complex neural architectures and analyze their effectiveness for phishing email classification.

The project evaluates:
- Logistic Regression
- Feedforward Neural Network (FNN)
- Recurrent Neural Network (RNN)
- Long Short-Term Memory (LSTM)

The assignment also includes comprehensive evaluation, error analysis, and robustness testing.

---

# Objectives

- Detect phishing emails using NLP techniques
- Compare traditional ML and neural architectures
- Analyze model performance using multiple evaluation metrics
- Study precision-recall tradeoffs in phishing detection
- Perform qualitative error analysis and robustness testing

---

# Dataset

Dataset used:
- Phishing Email Dataset

Possible Sources:
- Kaggle
- Hugging Face

The dataset contains labeled phishing and legitimate emails used for binary text classification.

---

# Project Structure

```text
comparative-analysis-phishing-email-detection/
│
├── dataset/
│   └── phishing_emails.csv
│
├── notebooks/
│   └── 23F-0012_NLP_Assignment2.ipynb
│
├── models/
│   ├── logistic_regression.pkl
│   ├── fnn_model.pth
│   ├── rnn_model.pth
│   └── lstm_model.pth
│
├── screenshots/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── loss_curve.png
│   └── reliability_diagram.png
│
├── report/
│   └── report.pdf
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Models Implemented

## 1. Logistic Regression
- TF-IDF vectorization
- Baseline NLP classifier
- Hyperparameter tuning

## 2. Feedforward Neural Network (FNN)
- Dense neural architecture
- Dropout regularization
- Early stopping

## 3. Recurrent Neural Network (RNN)
- Sequence modeling
- Embedding layer
- Sequential text processing

## 4. Long Short-Term Memory (LSTM)
- Memory cells and gates
- Long-range dependency handling
- Improved sequential learning

---

# Evaluation Metrics

The following metrics were used:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- AUC Score
- Brier Score
- Reliability Diagram

---

# Why Recall Matters in Phishing Detection

Recall is especially important in phishing detection because failing to identify a phishing email may result in:
- Credential theft
- Financial loss
- Malware infection
- Security breaches

A model with higher recall minimizes false negatives and improves cybersecurity protection.

---

# Error Analysis

The best-performing model was analyzed using:
- Misclassified email examples
- Adversarial phishing inputs
- Out-of-distribution testing

The analysis revealed limitations in:
- Ambiguous language
- Short email content
- Sophisticated phishing attempts

---

# Technologies Used

- Python
- Scikit-learn
- PyTorch
- TensorFlow/Keras
- NLTK
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# How to Run

## Install dependencies

```bash
pip install -r requirements.txt
```

## Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
23F-0012_NLP_Assignment2.ipynb
```

---

# Results

- Logistic Regression established a strong baseline.
- FNN improved nonlinear feature learning.
- RNN captured sequential patterns in text.
- LSTM achieved the best performance and training stability.

The study demonstrates how increasing architectural complexity impacts phishing detection performance and computational cost.

---

# Author

Ayesha Imran  
23F-0012  
FAST National University  
Natural Language Processing (NLP)

---

# License

This project is for academic and educational purposes only.
