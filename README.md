# Udacity MLE - Capstone Summary
## Predicting Diabetes Readmissions

This repository contains code and documents related to my final project for Udacity's Machine Learning Engineer Nano-degree. All libraries imported within the workbooks come pre-installed on a standard ml.t2.medium Sagemaker notebook instance.

#### Capstone Proposal
Proposal document outlining the general problem statement and anticipated approach.
#### Capstone Summary
Detail summary of project design, implementation, and results.
#### Data_Ingest.ipynb
Script to read in raw data and save to data/ directory.
#### Data_Prep.ipynb
Script to process and explore raw data. Creates X and y numpy arrays (training algorithm inputs)
#### Train_Model_LinLearner.ipynb
Script to fit and tune a Sagemaker LinearLearner Classifier. Also provides code to perform batch inference/evaluation
#### Train_Model_XGBoost.ipynb
Script to fit and tune a Sagemaker XGBoost Classifier. Also provides code to perform batch inference/evaluation
