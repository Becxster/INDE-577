# Titanic Dataset Overview

The Titanic dataset contains data about passengers aboard the Titanic, including demographic and ticket details. In this jupyter notebook, I explore decision trees and regression trees on the Titanic dataset.

## Dataset Details

### Columns:
1. **PassengerId**: A unique identifier for each passenger.
2. **Survived**: The survival status of the passenger (0 = Not Survived, 1 = Survived).
3. **Pclass**: The ticket class of the passenger (1 = First, 2 = Second, 3 = Third).
4. **Name**: The name of the passenger.
5. **Sex**: The gender of the passenger (male/female).
6. **Age**: The age of the passenger (may contain missing values).
7. **SibSp**: The number of siblings or spouses aboard the Titanic.
8. **Parch**: The number of parents or children aboard the Titanic.
9. **Ticket**: The ticket number.
10. **Fare**: The price paid for the ticket.
11. **Cabin**: The cabin number (may contain missing values).
12. **Embarked**: The port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

### Key Features:
- **Target Variable**: `Survived` (indicates survival status).
- **Categorical Variables**: `Pclass`, `Sex`, `Embarked`.
- **Numerical Variables**: `Age`, `Fare`.
- **Family Relationships**: `SibSp` and `Parch` allow insights into family size and its impact on survival.

### Missing Data:
- The dataset contains missing values in columns such as `Age`, `Cabin`, and `Embarked`.

You can find the dataset on Kaggle at the [Titanic Kaggle Competition](https://www.kaggle.com/c/titanic/data).

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
    Open decision_trees.ipynb from the Jupyter interface.
4. **Run the Cells**