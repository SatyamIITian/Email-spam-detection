# Email-spam-detection

This project implements machine learning models to classify whether an email is **spam or not**, based on word frequency and other textual features. It uses the **Spambase dataset** from the UCI Machine Learning Repository.

## 📁 File Structure

- `APR_ASSIGNMENT1_Q1.ipynb`: Jupyter Notebook containing data preprocessing, model training, evaluation, and performance visualization.

## 🎯 Objective

To build an accurate and interpretable model that can automatically classify emails as **spam** or **not spam** using supervised learning techniques.

## 📊 Dataset Overview

The **Spambase dataset** contains 4601 instances and 57 attributes such as:

- Frequency of specific words and characters (e.g., `free`, `money`, `!`)
- Average length of capital letter sequences
- Total number of capital letters

Dataset Source: [UCI ML Repository - Spambase](https://archive.ics.uci.edu/ml/datasets/spambase)

## 🛠️ Features of the Project

- **Data Preprocessing**: Handling missing values, scaling, and feature selection.
- **Model Training**:
  - Logistic Regression
  - Naive Bayes
  - Decision Tree
  - Support Vector Machine (SVM)
- **Evaluation Metrics**:
  - Accuracy
  - Confusion Matrix
  - Precision, Recall, F1-score
  - ROC-AUC

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/email-spam-detection.git
   cd email-spam-detection
