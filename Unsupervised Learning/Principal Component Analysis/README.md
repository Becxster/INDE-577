# Principal Component Analysis (PCA)
Principal Component Analysis (PCA) is a dimensionality reduction technique that transforms high-dimensional data into a lower-dimensional space by identifying directional vectors (principal components) with the most variance. To do this, we compute the eigenvectors and eigenvalues of the data's covariance matrix or using Singular Value Decomposition (SVD) to project the data onto these components. In this notebook, I use PCA on the UCI Wine Dataset to find the best projections onto the 2-Dimensional Plane to separate the types of wine into clusters. 


## UCI Wine Dataset

The Wine dataset contains chemical analysis results of wines grown in the same region in Italy but derived from three different cultivars. 

---

### Dataset Overview
- **Source**: UCI Machine Learning Repository
- **Link**: [Wine Dataset](https://archive.ics.uci.edu/dataset/109/wine) and [csv mirror](https://gist.github.com/tijptjik/9408623)
- **Type**: Multivariate Dataset
- **Instances**: 178
- **Attributes**: 13 features (continuous) and 1 target variable (categorical)

---

### Features
The dataset includes 13 chemical and physical properties of wines:
1. Alcohol
2. Malic acid
3. Ash
4. Alcalinity of ash
5. Magnesium
6. Total phenols
7. Flavanoids
8. Nonflavanoid phenols
9. Proanthocyanins
10. Color intensity
11. Hue
12. OD280/OD315 of diluted wines
13. Proline

---

### Target Variable
- **Wine Class (1, 2, 3)**: Represents three cultivars of wine.

---

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
    Open pca.ipynb from the Jupyter interface.
4. **Run the Cells**