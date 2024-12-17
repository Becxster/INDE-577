# The Perceptron

## Overview

This Jupyter Notebook demonstrates the implementation of the Perceptron algorithm, a type of linear classifier, on a given dataset. The Perceptron is a supervised learning algorithm used for binary classifiers, which makes it a suitable choice for this dataset.

## Dataset

There are two datasets used in this notebook (1): The [UCI Machine Learning Repository - Seeds Dataset](https://archive.ics.uci.edu/dataset/236/seeds), which contains geometrical properties of wheat kernels belonging to three different varieties of wheat and (2): the [University of Wisconsin Hospitals Breast Cancer Dataset](https://github.com/scikit-learn/scikit-learn/blob/6e9039160/sklearn/datasets/_base.py#L746), a binary classification dataset which includes features pertaining to tumors and whether or not each patient has breast cancer.

## UCI Seeds Dataset:


The **Seeds Dataset** is from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/seeds) used primarily for classification tasks. 
### Data Characteristics

- **Number of Instances:** 210
- **Number of Attributes:** 7 (all numerical)
- **Class Labels:** 3 distinct wheat varieties (Kama, Rosa and Canadian)

### Attributes

The dataset comprises seven continuous features that describe the geometrical properties of wheat seeds:

1. **Area:** Area of the seed (unit: mm²)
2. **Perimeter:** Perimeter of the seed (unit: mm)
3. **Compactness:** Compactness = \(4\pi \times \text{Area} / \text{Perimeter}²\)
4. **Length of Kernel:** Length of the seed (unit: mm)
5. **Width of Kernel:** Width of the seed (unit: mm)
6. **Asymmetry Coefficient:** Asymmetry coefficient of the seed
7. **Length of Kernel Groove:** Length of the groove (unit: mm)

### Class Labels

Each instance in the dataset is labeled with one of three wheat varieties:

| **Label** | **Wheat Variety** |
|-----------|--------------------|
| **1**     | **Kama**           |
| **2**     | **Rosa**           |
| **3**     | **Canadian**       |


#### Citation

You can download the Seeds Dataset directly from the [UCI Repository](https://archive.ics.uci.edu/ml/datasets/seeds). 

## Breast Cancer Dataset:

 The University of Wisconsin Hospitals Breast Cancer Dataset is a binary classification dataset, which includes features pertaining to tumors and whether or not each patient has breast cancer. The goal of the classification problem is to determine whether the tumors are malignant or benign. The dataset can be found [here](https://github.com/scikit-learn/scikit-learn/blob/6e9039160/sklearn/datasets/_base.py#L746). The breast cancer dataset was chosen because it is linearly separable, making it an ideal candidate for the Perceptron algorithm.

 ### Data Characteristics

- **Number of Instances:** 569  
- **Number of Attributes:** 30 (all numerical)  
- **Class Labels:** 2 distinct classes (Malignant and Benign)

### Attributes

The dataset comprises 30 continuous features derived from the digitized image of a fine needle aspirate (FNA) of a breast mass. The features describe properties of the cell nuclei:

1. **Radius (mean):** Mean distance from center to perimeter of the cell nuclei.
2. **Texture (mean):** Standard deviation of gray-scale values in the cell nuclei.
3. **Perimeter (mean):** Mean perimeter of the cell nuclei.
4. **Area (mean):** Mean area of the cell nuclei (unit: pixels²).
5. **Smoothness (mean):** Local variation in the radius lengths.
6. **Compactness (mean):** Compactness = \((\text{Perimeter}²) / \text{Area} - 1.0\).
7. **Concavity (mean):** Severity of concave portions of the cell contour.
8. **Concave Points (mean):** Number of concave portions of the contour.
9. **Symmetry (mean):** Symmetry of the cell nuclei.
10. **Fractal Dimension (mean):** Measure of the complexity of the cell contour ("coastline approximation").  
11-20. **Worst Values:** The largest (worst) value for each of the above 10 features.  
21-30. **Standard Error:** The standard error for each of the above 10 features.

### Class Labels

Each instance in the dataset is labeled with one of two classes:

| **Label** | **Diagnosis**      |
|-----------|--------------------|
| **0**     | **Benign**         |
| **1**     | **Malignant**      |

#### Citation

You can download the Breast Cancer Dataset directly from the [scikit-learn github](https://github.com/scikit-learn/scikit-learn/blob/6e9039160/sklearn/datasets/_base.py#L746). 

## Why Perceptron?

The Perceptron algorithm is suitable for these datasets because:
- **Linearly Separable Data**: The Perceptron works well with linearly separable data, which means it can find a hyperplane that separates the two classes. Both of these datasets are *mostly* linearly seperable.
- **Simplicity**: The Perceptron is simple to implement and understand, making it a good starting point for binary classification tasks.

## Contents

- **Data Preprocessing**: Steps to clean and prepare the dataset for training.
- **Perceptron Implementation**: Detailed implementation of the Perceptron algorithm.
- **Model Training**: Training the Perceptron on the dataset.
- **Evaluation**: Assessing the performance of the trained model using appropriate metrics.
- **Visualization**: Visualizing the decision boundary and the classification results.

## Steps to Run the Code
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/Becxster/INDE-577.git
    cd <repository-directory>
    ```

2. **Install Dependencies**: Ensure you have the required Python packages installed. You can install them using:
    ```sh
    pip install -r requirements.txt
    ```

3. **Open the Jupyter Notebook**: Launch Jupyter Notebook from the command line:
    ```sh
    jupyter notebook
    ```
    Open Perceptron.ipynb from the Jupyter interface.
4. **Run the Cells**


