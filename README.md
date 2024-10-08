# Machine-Learning-Model-Selection-and-Class-Balancing
This repository contains a comprehensive tutorial on Machine Learning Model Selection for Multivariate Analysis with Anonymized Data. It covers data preprocessing, class balancing strategies (specifically undersampling), and model evaluation, leading to the deployment of the best-performing machine learning model.

Table of Contents

Overview
Dataset
Preprocessing
Class Balancing
Model Training
Model Evaluation
How to Use
Technologies Used
Author
Overview

In this project, we go step-by-step from the definition of the business problem to selecting the best machine learning model and preparing it for deployment. The dataset used is anonymized, adding a layer of complexity as the variables lack descriptions. The project covers the following:

Data Preprocessing: Handling missing data, outliers, and scaling.
Class Balancing: Using undersampling to address the class imbalance problem.
Model Selection: Training multiple models, applying cross-validation, and optimizing hyperparameters.
Model Deployment: Choosing the best model for deployment based on various evaluation metrics.
Dataset

The dataset is anonymized and includes 179 columns—178 input features and 1 target variable. The target variable indicates whether or not a customer renewed their insurance policy.

Preprocessing

Steps involved in preprocessing include:

Handling missing values.
Scaling numerical features.
Addressing outliers.
Splitting the data into training, validation, and test sets, while preserving the prevalence of the target class.
Class Balancing

Due to the imbalance in the target class (20% positive, 80% negative), the project implements undersampling on the majority class to balance the dataset for training.

Model Training

Several machine learning models are trained, with and without hyperparameter tuning. The models are evaluated using cross-validation to ensure robustness.

Model Evaluation

Various metrics are used to evaluate model performance, including:

Accuracy
Precision
Recall
F1-Score
ROC-AUC
The best-performing model is selected for deployment.

How to Use

Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/machine-learning-model-selection.git
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebooks for data preprocessing, model training, and evaluation.
Technologies Used

Python 3.x
Pandas
NumPy
Scikit-learn
Matplotlib/Seaborn
Pickle
Author

Leonardo Anello
