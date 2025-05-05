This notebook demonstrates how to create and use Machine Learning pipelines in Python 
using the scikit-learn library. The primary objective is to streamline model training and 
evaluation processes by chaining together data preprocessing and model fitting steps.

Introduction to ML pipelines
Loading and preparing the Breast Cancer dataset
Creating a pipeline with MinMaxScaler and SVC
Training and evaluating the model
Hyperparameter tuning using GridSearchCV
Comparing pipeline performance with manual steps

Results
The notebook illustrates that using pipelines:
Reduces data leakage risks.
Makes hyperparameter tuning easier and cleaner.
Produces results comparable or superior to manual modeling steps.

Key Concepts
Pipeline: Combines preprocessing and modeling steps to ensure cleaner and more reproducible code.
MinMaxScaler: Normalizes features to a specific range.
Support Vector Classifier (SVC): A classification algorithm.
GridSearchCV: Performs exhaustive hyperparameter tuning.
