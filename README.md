# Pattern Recognition Assignment 2023

This repository contains the solution to the 2023 PR assignment. 
Part of the Pattern Recognition Course 2023-2024 ▪︎ School of Electrical and Computer Engineering at Aristotle University of Thessaloniki (AUTh)

The assignment is divided into four main parts, each focusing on different classification techniques using provided datasets. 
Below is an overview of the tasks accomplished in each part.

## Table of Contents
- [Part A: Bayes Classifier](#part-a-bayes-classifier)
- [Part B: k-NN Classifier](#part-b-k-nn-classifier)
- [Part C: SVM Classifier](#part-c-svm-classifier)
- [Part D: Custom Dataset Classification](#part-d-custom-dataset-classification)
- [Files](#files)

## Part A: Bayes Classifier

- **Task**: Load the dataset, split it into training and test sets (50%-50%), and train a Bayes classifier using the Maximum Likelihood method.
- **Methods**:
  - Same covariance matrix for all classes.
  - Different covariance matrix for each class.
- **Visualization**:
  - Plot the test data and highlight misclassified samples.
  - Display regions corresponding to each class.
- **Evaluation**: Calculate the average classification error on the test set and determine which method yields better results.

## Part B: k-NN Classifier

- **Task**: Train a k-Nearest Neighbors (k-NN) classifier using the same training set from Part A.
- **Methods**:
  - Evaluate for k = 1, ..., 10.
- **Visualization**:
  - Plot the data and regions corresponding to each class.
- **Evaluation**: Compare the results with those from Part A by calculating the average classification error on the test set.

## Part C: SVM Classifier

- **Task**: Train a Support Vector Machine (SVM) classifier using the same dataset and split method as in Parts A and B.
- **Methods**:
  - Linear SVM.
  - RBF kernel SVM, with experiments on hyperparameter tuning.
- **Evaluation**: Analyze and compare the results based on the average test set error for each SVM method.

## Part D: Custom Dataset Classification

- **Task**: Utilize `datasetC.csv` and `datasetCTest.csv` for this part.
- **Methods**:
  - Design and implement a big grid search to find the best Neural Network architecture.
  - Evaluate the model on the test dataset.
- **Visualization**:
  - Highlight misclassified samples in the test data.
  - Plot regions corresponding to each class.
    
## Files

- `Team42-AC.ipynb`: Jupyter notebook containing the code for Parts A, B, and C.
- `Team42-D.ipynb`: Jupyter notebook containing the code for Part D.
- `labels42.npy`: Numpy file containing the label vector from Part D.
- `Team42.pdf`: Presentation slides detailing the solution for all parts (A to D).
