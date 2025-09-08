# Breast Cancer Classification (Ex 15.17)

This repository contains my solution for **Exercise 15.17: Binary Classification with the Breast Cancer Dataset** from the textbook.

## 📘 Project Description
The project uses the **Breast Cancer Wisconsin Diagnostic Dataset** (built into scikit-learn) to perform **binary classification** (malignant vs benign tumors).  
Multiple machine learning classifiers were evaluated and compared using accuracy scores and cross-validation.

## ⚙️ Steps Implemented
- Loading the dataset
- Checking sample and target sizes
- Splitting data into training/testing sets
- Creating and training a **GaussianNB** model
- Making predictions and scoring the model
- Generating confusion matrix and classification report
- Visualizing the confusion matrix
- Performing **10-Fold Cross-Validation**
- Running multiple classifiers (GaussianNB, KNN, Logistic Regression, SVC) to find the best one

## 📊 Results
- GaussianNB Test Accuracy: ~0.93  
- Best model (by CV mean accuracy): *Logistic Regression* (slightly higher accuracy than others)

## 🛠️ Tools & Libraries
- Python 3
- scikit-learn
- NumPy
- Pandas
- Matplotlib

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/breast-cancer-classification.git
   cd breast-cancer-classification
