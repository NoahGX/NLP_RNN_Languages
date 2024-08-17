# Natural Language Processing: Predicting Surname Origins using Recurrent Neural Networks

## Overview
The purpose of this Jupyter Notebook is to provide an in-depth exploration and implementation of a machine learning model designed to predict the language origin of surnames. The model is built using PyTorch and employs a Recurrent Neural Network (RNN) to classify surnames into their corresponding languages based on a trained dataset of international surnames.

## Features
- **Data Processing**: Includes steps for preparing the surname data for training, such as converting surnames into tensors.
- **Model Building**: Utilizes a custom RNN for surname language classification.
- **Training Loop**: Implements a training loop that logs the loss and accuracy metrics, adjusting weights to improve predictions over epochs.
- **Evaluation**: Provides functions to evaluate the model’s performance on a test set.
- **Prediction**: Offers a utility to predict the language origin of new input surnames.

## Usage
- Run each cell sequentially in order to observe the data processing, model training, and evaluation steps.
- Utilize the prediction function provided to test the model with new surnames.

## Prerequisites
- Python 3.x
- PyTorch
- Matplotlib (for visualization)

## Input
- A list of surnames and their corresponding language origins for training the model.
- Individual surnames for which the language origin is to be predicted.

## Output
- Model training outputs including loss metrics and accuracy.
- Predictions of language origin for new surnames, along with the probability scores.

## Notes
- The accuracy of predictions can be improved by increasing the diversity and size of the training dataset.
- Further enhancements can be explored through the use of advanced RNN architectures like LSTM or regularization techniques to reduce overfitting.