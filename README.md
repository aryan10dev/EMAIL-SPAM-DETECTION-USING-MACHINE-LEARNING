# Email Spam Detection Using Machine Learning

## Overview
This project focuses on building a robust spam email detection system using machine learning techniques. By leveraging natural language processing (NLP) and feature engineering, the system classifies emails as spam or non-spam with high accuracy. The project explores multiple machine learning models, compares their performance, and applies advanced techniques like SMOTE to address class imbalance.

---

## Features
- **Preprocessing**: 
  - Tokenization and TF-IDF vectorization for text data.
  - Handling noisy data to improve model robustness.
- **Model Evaluation**:
  - Implemented Logistic Regression, Random Forest, Support Vector Machine (SVM), and Ensemble Learning models.
  - Comprehensive metrics evaluation, including precision, recall, F1-score, and AUC.
- **Class Imbalance Handling**:
  - Applied SMOTE to improve recall and accuracy for the minority spam class.
- **Visualization**:
  - Confusion matrices, precision-recall curves, and ROC curves for comparing model performance.

---

## Results
- **Initial Model Results**: 
  - Accuracy: 74.3%, but with poor recall for spam due to class imbalance.
- **After Applying SMOTE**:
  - Significant improvement in recall and F1-scores for the spam class, making the model more effective for real-world use cases.

---

## Technology Stack
- **Programming Language**: Python
- **Libraries Used**:
  - `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `imbalanced-learn`
- **Development Environment**: Jupyter Notebook

---

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/email-spam-detection.git
   cd email-spam-detection
