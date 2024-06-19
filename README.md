# Machine Learning Project

This repository contains a notebook demonstrating a comprehensive machine learning workflow, from data loading and preprocessing to model training and evaluation.

## Introduction

This project is a complete walkthrough of a machine learning pipeline. It covers everything from data loading and preprocessing to training various models and evaluating their performance. The aim is to provide a hands-on example of how different machine learning algorithms can be applied to a dataset and compared based on various performance metrics.

## Content

The notebook covers the following sections:

1. **Libraries**: Importing necessary libraries for data manipulation, model building, and evaluation, including:
   - pandas and numpy for data manipulation.
   - scikit-learn for model building and evaluation.
   - imbalanced-learn for handling imbalanced datasets.
   - tensorflow and keras for building neural networks.

2. **Load Dataset**: Loading and displaying the dataset using pandas.

3. **Preprocessing**: Data cleaning and preprocessing steps to prepare the dataset for model training, including:
   - Handling missing values.
   - Encoding categorical variables.
   - Normalizing and scaling features.
   - Handling class imbalance using techniques like SMOTE (Synthetic Minority Over-sampling Technique).

4. **Model Building**: Training various machine learning models including:
   - **Random Forest Classifier**: An ensemble method using multiple decision trees.
   - **K-Nearest Neighbors (KNN)**: A simple, instance-based learning algorithm.
   - **Support Vector Machine (SVM)**: A powerful classification algorithm.
   - **Neural Network**: Using tensorflow and keras to build and train neural network models.
   - **Logistic Regression**: A linear model for binary classification.

5. **Model Evaluation**: Evaluating the performance of the models using metrics such as:
   - **Accuracy**: The proportion of correctly classified instances.
   - **Precision**: The proportion of true positive results among all positive predictions.
   - **Recall**: The proportion of true positive results among all actual positives.
   - **F1-Score**: The harmonic mean of precision and recall.
   - **Confusion Matrix**: A table to describe the performance of a classification model.

## Dataset

The dataset used in this project is included within the notebook. Ensure that the dataset file `mhealth_raw_data.csv` is present in the same directory as the notebook.
