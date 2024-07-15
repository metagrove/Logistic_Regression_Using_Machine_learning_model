# Logistic_Regression_Using_Machine_learning_model
Project Description
This project involves predicting the likelihood of breast cancer using a machine learning model based on logistic regression. Logistic regression is particularly suited for binary classification tasks, where the outcome is either one of two possible values. In this case, we predict whether a given sample is benign or malignant.

Logistic Regression Overview
Logistic Regression is a statistical method used for binary classification problems. It estimates the probability that a given input belongs to a certain class. The logistic regression model uses the sigmoid function to map predicted values to probabilities:

Binary Classification
Binary classification is the process of classifying instances into one of two possible classes. In this project, the classes are:

0: Benign
1: Malignant

Exploratory Data Analysis (EDA):
To understand the relationships and distributions of the features, we used pair plots. Pair plots provide a way to visualize the pairwise relationships between different features and their distributions, aiding in the detection of patterns and potential correlations.

Model Performance:
The model was evaluated on a dataset of breast cancer cases and achieved an accuracy of 98%. To ensure the robustness of the model, we employed the following evaluation metrics:

Accuracy: The ratio of correctly predicted instances to the total instances.
ROC Curve: A graphical representation of the true positive rate versus the false positive rate at various threshold settings.
AUC (Area Under the Curve): Measures the entire two-dimensional area underneath the ROC curve. A higher AUC indicates a better performing model.
Heatmap: Visualizes the confusion matrix to show the number of true positives, true negatives, false positives, and false negatives.

Visualization:
Pair Plots-
Pair plots were used to visualize the distributions and relationships between the features. This helps in understanding the underlying patterns in the data.

ROC Curve and AUC:
The ROC curve and AUC help in visualizing the performance of the binary classification model. 
The closer the ROC curve to the top left corner, the better the model performance. An AUC of 1 represents a perfect model,
while an AUC of 0.5 represents a model with no discriminatory power.

Heatmap:
The heatmap of the confusion matrix provides a detailed view of how well the model is performing in terms of true positive, true negative, false positive,
and false negative predictions.

Final words:
The logistic regression model developed in this project has demonstrated a high level of accuracy in predicting breast cancer. 
The use of pair plots, ROC and AUC curves, along with a confusion matrix heatmap, provides a comprehensive understanding of the model's performance.Installation
Clone the repository and install the necessary dependencies:
----------------------------------------------------------------------------------------------------------------------
Installation:
Copy code
git clone 
cd 
----------------------------------------------------------------------------------------------------------------------
Run the script to train the model and visualize the results:
python train_model.py
----------------------------------------------------------------------------------------------------------------------
Dataset:
The dataset used for this project is the Breast Cancer Wisconsin (Diagnostic) Data Set. Ensure the dataset is in the appropriate directory before running the scripts.


