# Breast-Cancer-Prediction

# Overview
This project analyzes a breast cancer dataset to build and evaluate machine learning models that classify tumors as benign or malignant. The dataset comprises numerical features extracted from digitized images of fine needle aspirate (FNA) samples of breast masses.

# Dataset Information
The dataset contains 569 samples, with no missing values. The class distribution includes 357 benign cases and 212 malignant cases. Each sample is described by 30 numerical features, representing cell nuclei properties based on their mean, standard error, and worst-case values.

# Models Implemented
Three classification models were trained and evaluated:

Logistic Regression

K-Nearest Neighbors (KNN)

Support Vector Machines (SVM)

# Performance Metrics
Logistic Regression and SVM achieved an accuracy of 98.24%, demonstrating their strong predictive capabilities with an AUC of 1.00. KNN performed slightly lower, achieving an accuracy of 96.49% with an AUC of 0.98.

# Key Findings
Logistic Regression and SVM provided exceptional classification accuracy, making them strong candidates for breast cancer prediction. KNN also performed well but was slightly less accurate than the other models.

# Visualizations
The project includes various exploratory data analysis techniques such as heatmaps, pairplots, and feature distributions to understand the dataset better. Additionally, confusion matrices and ROC curves were plotted to assess model performance.
# Conclusion
The analysis highlights the efficiency of machine learning models in breast cancer classification. Logistic Regression and SVM demonstrate high reliability in medical diagnosis, achieving near-perfect separation between malignant and benign tumors.
