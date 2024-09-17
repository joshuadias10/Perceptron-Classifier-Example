# Perceptron Learning Algorithm

## Overview
This repository demonstrates the implementation of the **Perceptron Learning Algorithm** using Python and the `scikit-learn` library. The perceptron is a simple linear binary classifier, fundamental to understanding machine learning. This example uses a generated dataset to train and test the model.

## Dataset
The dataset is generated using the `make_classification` function from `sklearn.datasets`. It contains:
- 1000 samples
- 10 input features
- No redundant features

## Code Explanation

1. **Data Generation**:
   We use `make_classification` to generate a random binary classification dataset with no redundant features.

2. **Model**:
   The perceptron model is created using the `Perceptron` class from `sklearn.linear_model`.

3. **Training**:
   The perceptron is trained on the generated dataset.

4. **Prediction**:
   After training, the model predicts the class of a given sample.

## Sample Output
```
Predicted Class: 1
```
