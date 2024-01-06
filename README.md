# Parkinsons-Disease-Detection

## Overview
This repository contains a machine learning project aimed at detecting Parkinson's disease from biomedical voice measurements. The project uses the XGBoost algorithm, a powerful machine learning technique for classification tasks. The dataset used includes various voice measure features that are pre-processed, scaled, and fed into an XGBoost Classifier to predict the status of Parkinson's disease.

## Dependencies
- NumPy
- Pandas
- scikit-learn
- XGBoost

These can be installed via pip using the command:

`!pip install numpy pandas scikit-learn xgboost`

## Data
The `parkinsons.data` file includes voice recording measurements from individuals, with each record labeled as having Parkinson's disease or not. Features cover various aspects of voice frequency and amplitude, along with other complex features like harmonic ratios and dynamic complexity.

## Features and Labels
The dataset includes various features extracted from voice measurements, with the 'status' column being the label indicating the presence of Parkinson's disease.

## Preprocessing
The features are scaled between −1 and 1 using MinMaxScaler to normalize the data for optimal performance of the classifier.

## Model Training and Evaluation
An XGBClassifier is trained on the dataset and evaluated using the accuracy metric to determine the effectiveness of the model.

## Usage
To replicate the findings and run the model on your data:
1. Install the required dependencies.
2. Update the dataset path as per your setup.
3. Run the script to train the model and output the accuracy score.

## Results
The output of the script will give you the accuracy of the model on the test set, which indicates how well the model predicts Parkinson's disease.
