# Linear Regression with Different Loss Functions

This Jupyter Notebook demonstrates the implementation of linear regression on an Air Quality Dataset from UC Irvine which can be found [here](https://archive.ics.uci.edu/dataset/360/air+quality). The dataset includes 9358 instances of and air data (like temperature, humidity, and chemical makeup) which consists of real numbers and some correlations — perfect for demonstrating linear regression.

## Description

Linear regression is a fundamental machine learning algorithm used for predicting a continuous target variable based on one or more input features. It assumes a linear relationship between the input features and the target variable. The goal is to find the best-fitting line that minimizes the error between the predicted and actual values.

### Loss Functions Used:
- **MSE (Mean Squared Error)**: Measures the average of the squares of the errors—that is, the average squared difference between the estimated values and the actual value. It is sensitive to outliers.
- **MSLE (Mean Squared Logarithmic Error)**: Penalizes underestimation more than overestimation.
- **MAE (Mean Absolute Error)**: Measures the average magnitude of errors in a set of predictions, without considering their direction.
- **Huber Loss**: Combines the best properties of both MAE and MSE, being less sensitive to outliers in data.

## Dataset

The dataset used in this notebook can be found at the following link:
[Air Quality Dataset](https://archive.ics.uci.edu/dataset/360/air+quality)


## Steps to Run the Code
1. **Clone the Repository**:
    ```sh
    git clone <[repository-url](https://github.com/Becxster/INDE-577.git)>
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
    Open linear_regression.ipynb from the Jupyter interface.
4. **Run the Cells**