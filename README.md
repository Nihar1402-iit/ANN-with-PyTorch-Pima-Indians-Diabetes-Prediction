# ANN with PyTorch: Pima Indians Diabetes Prediction

This repository contains a Python project using PyTorch to build and train an Artificial Neural Network (ANN) for predicting diabetes based on the Pima Indians Diabetes Dataset.

## Project Overview

The goal of this project is to create a simple neural network to classify whether a patient has diabetes or not based on various health measurements (such as glucose level, BMI, etc.).

The Pima Indians Diabetes Dataset is a commonly used dataset for classification tasks in machine learning, and this project uses PyTorch to demonstrate how to build, train, and evaluate an ANN on this dataset.

## Key Features

- Uses PyTorch as the deep learning framework.
- Implements a fully connected feedforward ANN.
- Includes data preprocessing, model training, and evaluation steps.
- Tracks training loss across epochs.
- Visualizes the training loss curve.

## Dataset

The Pima Indians Diabetes dataset consists of 8 features (independent variables) and 1 target (dependent variable). Each row in the dataset represents a patient, and the target column indicates whether the patient has diabetes (`1`) or not (`0`).

## Installation

To run this project, ensure you have the following installed:

- Python 3.x
- PyTorch
- Matplotlib
- Pandas
- Scikit-learn

You can install the dependencies using the following command:

```bash
pip install torch matplotlib pandas scikit-learn
