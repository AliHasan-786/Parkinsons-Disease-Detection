# Parkinsons-Disease-Detection

## Overview
This repository contains a machine learning project aimed at detecting Parkinson's disease from biomedical voice measurements. The project uses the XGBoost algorithm, a powerful machine learning technique for classification tasks. The dataset used includes various voice measure features that are pre-processed, scaled, and fed into an XGBoost Classifier to predict the status of Parkinson's disease.

## Dependencies
- NumPy
- Pandas
- scikit-learn
- XGBoost

These can be installed via pip using the command:
```bash
!pip install numpy pandas scikit-learn xgboost

## Data
The dataset parkinsons.data contains biomedical voice measurements from individuals, labeled with whether they have Parkinson's disease.

## Features and Labels
The dataset includes various features extracted from voice measurements, with the 'status' column being the label indicating the presence of the disease.

## Preprocessing
The features are scaled between -1 and 1 using MinMaxScaler to normalize the data for optimal performance of the classifier.

## Model Training and Evaluation
An XGBClassifier is trained on the dataset and evaluated using the accuracy metric to determine the effectiveness of the model.

## Usage
To replicate the findings and run the model on your data:

## Install the required dependencies.
Replace /content/parkinsons.data with the path to your dataset.
Execute the script to train the model and evaluate its performance.
Results
The output of the script will give you the accuracy of the model on the test set, which indicates how well the model is able to predict the status of Parkinson's disease.


