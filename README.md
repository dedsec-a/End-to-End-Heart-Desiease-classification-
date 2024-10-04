Heart Disease Classification Using Logistic Regression
This project is an end-to-end machine learning solution that predicts the likelihood of heart disease in a patient. The model is built using logistic regression and is trained on a dataset containing health metrics of individuals.

Table of Contents
Introduction
Dataset
Project Workflow
Modeling
Results
Installation
Usage
Contributing
License
Introduction
Heart disease is one of the leading causes of death worldwide. Early detection through data-driven approaches can help medical professionals intervene more effectively. This project leverages logistic regression, a binary classification algorithm, to predict the presence of heart disease based on patient data.

Dataset
The dataset used for this project contains various features related to the patient’s health, such as:

Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol Level
Maximum Heart Rate Achieved
Exercise Induced Angina
ST Depression (relative to rest)
And more...
The dataset can be found on UCI Machine Learning Repository or similar heart disease datasets. It has been pre-processed for this project to handle missing values and normalize features.

Project Workflow
Data Collection: Collected and explored the heart disease dataset.
Data Preprocessing: Handled missing values, feature scaling, and one-hot encoding for categorical variables.
Model Building: Built and trained a logistic regression model.
Evaluation: Evaluated the model using accuracy, precision, recall, F1-score, and ROC-AUC score.
