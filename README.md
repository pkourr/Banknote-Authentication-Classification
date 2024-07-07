# Banknote Authentication Classification

### Author: Kouretas Panagtiotis

## Dependencies

![pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)
![numpy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)
![matplotlib](https://img.shields.io/badge/matplotlib-%231DB2F5.svg?style=flat&logo=matplotlib&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-%2300B4D8.svg?style=flat&logoColor=white)


## Overview
This notebook explores the classification of banknotes as genuine or forged using a dataset containing features extracted from images of banknote-like specimens. These images were digitized using an industrial camera typically used for print inspection, with a resolution of about 660 dpi.

## Dataset
The dataset consists of the following features:
1. **Variance** of Wavelet Transformed image (continuous)
2. **Skewness** of Wavelet Transformed image (continuous)
3. **Curtosis** of Wavelet Transformed image (continuous)
4. **Entropy** of image (continuous)
5. **Class** (integer) - the target variable indicating whether the banknote is genuine or forged.

## Objectives
The primary goal is to apply various classification algorithms to this dataset and compare their performance to determine the most effective method for this classification task.

## Content Summary

### 1. Introduction
- Overview of the dataset and the problem statement.

### 2. Importing Libraries and Loading the Dataset
- Importing necessary libraries such as pandas, numpy, scikit-learn, matplotlib, and seaborn.
- Loading the dataset from a URL and assigning column names.

### 3. Data Exploration
- Displaying the first few rows of the dataset.
- Checking for missing values.
- Analyzing the distribution of the target variable.
- Descriptive statistics of the dataset.
- Visualizing the distribution of features using histograms.
- Creating a correlation matrix and visualizing it using a heatmap.

### 4. Data Preprocessing
- Splitting the dataset into training and testing sets.
- Standardizing the features using `StandardScaler`.

### 5. Model Training and Evaluation
Several classification algorithms are applied to the dataset:
- **Logistic Regression**
  - Training and evaluating a logistic regression model.
  - Printing accuracy, confusion matrix, and classification report.
- **Support Vector Machine (SVM)**
  - Training and evaluating an SVM model.
  - Printing accuracy, confusion matrix, and classification report.
- **Decision Tree**
  - Training and evaluating a decision tree model.
  - Printing accuracy, confusion matrix, and classification report.
- **Random Forest**
  - Training and evaluating a random forest model.
  - Printing accuracy, confusion matrix, and classification report.

### 6. Model Comparison
- Comparing the accuracy scores and classification reports from the different models to identify the best performing model.

## Conclusion
- Summarizing the findings and determining the most effective classification algorithm based on the evaluation metrics.

## How to Run
1. Ensure all dependencies are installed.
2. Open the notebook and run the cells sequentially to load the dataset, preprocess the data, train the models, and evaluate their performance.

## Acknowledgements
- The dataset used in this project is publicly available from the UCI Machine Learning Repository.
