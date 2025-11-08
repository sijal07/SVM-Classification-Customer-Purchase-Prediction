# SVM-Classification-Customer-Purchase-Prediction


SVM Classifier for Social Network Ads
This project implements a Support Vector Machine (SVM) classifier to predict whether a user will purchase a product based on their age and estimated salary from the Social Network Ads dataset.

Project Overview
The notebook demonstrates a complete machine learning workflow:

Data loading and preprocessing

Feature scaling

SVM model training and evaluation

Visualization of decision boundaries

Performance metrics calculation

Dataset
The dataset used is Social_Network_Ads.csv, which contains information about users including:

Age

Estimated Salary

Purchased (target variable: 0 = No, 1 = Yes)

Model Details
Algorithm: Support Vector Machine (SVM)

Kernel: Linear

Test Size: 25% of the data

Random State: 0 (for reproducibility)

Key Steps
Data Preprocessing

Imported necessary libraries (NumPy, Pandas, Matplotlib)

Loaded and split the dataset into training and test sets

Applied feature scaling using StandardScaler

Model Training

Initialized SVM classifier with linear kernel

Trained the model on the training data

Model Evaluation

Made predictions on test data

Generated confusion matrix

Calculated accuracy score (88%)

Visualization

Created decision boundary plots for training data

Visualized how the model separates the two classes

Results
The SVM model achieved:

Accuracy: 88%

Confusion Matrix:

text
[[63  5]
 [ 7 25]]
