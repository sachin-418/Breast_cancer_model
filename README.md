# Breast Cancer Prediction using Logistic Regression
# Project Overview

This project implements a Logistic Regression model to classify breast cancer tumors as Malignant (M) or Benign (B) using the Breast Cancer Wisconsin dataset.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, prediction, and performance evaluation.

# Objective

Build a classification model that can accurately predict whether a tumor is malignant or benign based on diagnostic measurements.

# Dataset
Dataset: Breast Cancer Wisconsin Dataset
File: data.csv
Target Variable: diagnosis
M → 1 (Malignant)
B → 0 (Benign)

# Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

# Project Workflow
Import required libraries
Load the dataset
Explore the dataset
Handle missing and duplicate values
Encode the target variable
Perform feature preprocessing
Split the dataset into training and testing sets
Train a Logistic Regression model
Make predictions
Evaluate the model using classification metrics

# Machine Learning Algorithm

Algorithm Used: Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for binary classification. It predicts the probability of an input belonging to one of two classes using the Sigmoid function.

# Model Evaluation

The model was evaluated using:

Accuracy Score
Precision
Recall
F1-Score
Confusion Matrix
Classification Report

The trained model achieved approximately 97% classification accuracy on the test dataset.

# Project Structure
├── LogisticReg_PROJECT.ipynb
├── data.csv
└── README.md
🚀 How to Run
Clone the repository
git clone https://github.com/your-username/your-repository.git
Install the required libraries
pip install pandas numpy matplotlib seaborn scikit-learn
Open the notebook
jupyter notebook LogisticReg_PROJECT.ipynb

or run it using Google Colab.

# Learning Outcomes

Through this project, I learned:

Data preprocessing techniques
Feature encoding
Train-test splitting
Logistic Regression
Model evaluation for classification
Performance metrics such as Precision, Recall, F1-Score, and Accuracy
Building an end-to-end machine learning classification pipeline

# Future Improvements
Hyperparameter tuning
Cross-validation
Feature selection
Model deployment using Flask or FastAPI
Comparing Logistic Regression with other classification algorithms

# Author

Developed as part of my Machine Learning learning journey to understand Logistic Regression and binary classification using Python and Scikit-learn.
