# The Perceptron

## Overview

This Jupyter Notebook demonstrates the implementation of the Perceptron algorithm, a type of linear classifier, on a given dataset. The Perceptron is a supervised learning algorithm used for binary classifiers, which makes it a suitable choice for this dataset.

## Dataset

The dataset used in this notebook is the University of Wisconsin Hospitals Breast Cancer Dataset binary classification dataset, which includes features pertaining to tumores and whether or not each patient has breast cancer. The goal of the classification problem is to determine whether the tumors are malignant or benign. The dataset can be found ![here](https://github.com/scikit-learn/scikit-learn/blob/6e9039160/sklearn/datasets/_base.py#L746). The breast cancer dataset was chosen because it is linearly separable, making it an ideal candidate for the Perceptron algorithm.

## Why Perceptron?

The Perceptron algorithm is suitable for this dataset because:
- **Linearly Separable Data**: The Perceptron works well with linearly separable data, which means it can find a hyperplane that separates the two classes.
- **Simplicity**: The Perceptron is simple to implement and understand, making it a good starting point for binary classification tasks.

## Contents

- **Data Preprocessing**: Steps to clean and prepare the dataset for training.
- **Perceptron Implementation**: Detailed implementation of the Perceptron algorithm.
- **Model Training**: Training the Perceptron on the dataset.
- **Evaluation**: Assessing the performance of the trained model using appropriate metrics.
- **Visualization**: Visualizing the decision boundary and the classification results.

## Usage

To run the notebook, ensure you have the necessary dependencies installed. You can install them using:

```bash
pip install -r requirements.txt
```

Open the Jupyter Notebook and execute the cells to see the Perceptron in action.


