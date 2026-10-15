# Build Your First Neural Network — ANN in Keras

## Project Overview

This project demonstrates how to build and train an Artificial Neural Network (ANN) using TensorFlow and Keras for a binary classification task. Using the Pulsar dataset, the model learns patterns from numerical features to classify observations into one of two classes.

The project covers data preprocessing, feature scaling, neural network architecture, model training, performance evaluation, and visualization of training and validation loss.

## Dataset

The project uses the Pulsar dataset (`pulsar_data_train.csv`).

- **Input features:** Eight numerical features describing each observation.
- **Target variable:** `target_class`, representing the binary class label.
- **Problem type:** Binary classification.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- TensorFlow and Keras

## Project Workflow

### 1. Data Preprocessing
- Loaded the dataset and inspected its structure.
- Separated the input features and target variable.
- Split the data into training and testing sets.
- Applied `StandardScaler` to normalize numerical features using training data.

### 2. Neural Network Architecture

The ANN uses the following architecture:

| Layer | Configuration |
|---|---|
| Input | Eight numerical features |
| Hidden Layer 1 | Dense(16, activation="relu") |
| Hidden Layer 2
