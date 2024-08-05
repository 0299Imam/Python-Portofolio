# **Analysis Of Backpropagation Artificial Neural Network Method For Brain Cancer Cell Recognition**

### Overview
This repository contains a Python notebook analyzing the effectiveness of the Backpropagation Artificial Neural Network (ANN) 
method for recognizing brain cancer cells. The goal of this project is to evaluate how well this neural network approach can 
classify brain cancer cells based on provided datasets.

### Table of Contents
Introduction
Getting Started
Usage
Results

### Introduction
This project utilizes the Backpropagation ANN method to classify brain cancer cells. 
The analysis includes data preprocessing, model training, and evaluation to determine 
the performance of the ANN model in a cancer cell recognition task.

Key features of the project include:

Data preprocessing and augmentation
Model architecture and hyperparameter tuning
Evaluation metrics and performance analysis

### Getting Started

Prerequisites
To run this project, you'll need the following Python libraries:

- numpy
- pandas
- matplotlib
- scikit-learn
- keras
- tensorflow


### Usage
The notebook includes the following sections:

- Data Loading: Loading and exploring the dataset.
- Data Preprocessing: Cleaning and preparing data for the model.
- Model Training: Building and training the Backpropagation ANN model.
- Evaluation: Assessing the model's performance and visualizing results.

You can modify the notebook cells as needed to fit your analysis requirements.

### Results
The neural network model for brain cancer cell recognition achieved the following results:

- Final training accuracy: 79.28%
- Final validation accuracy: 79.87%

Performance metrics:

- Precision: 84.62%
- Recall: 81.48%
- Overall accuracy: 76.62%

The model was trained for 200 epochs. The training and validation accuracy increased over time, 
with the validation accuracy stabilizing around 79-80% in the later epochs.

A confusion matrix was generated to evaluate the model's performance:
- [[88 16]
- [20 30]]
  
This indicates:

- 88 true negatives
- 30 true positives
- 16 false positives
- 20 false negatives

The results suggest the model has reasonable predictive power for distinguishing between cancerous and non-cancerous brain cells, 
but there is still room for improvement. Further optimization of the model architecture and hyperparameters could potentially enhance its performance.
Visualizations of the training process, including accuracy and loss curves for both training and validation sets, were generated to provide
insight into the model's learning progression over time.
