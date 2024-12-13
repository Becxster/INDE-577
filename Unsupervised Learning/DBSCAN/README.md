# DBSCAN
DBSCAN (a.k.a. Density-Based Spatial Clustering of Applications with Noise) is an unsupervised clustering algorithm that groups data points based on their density. It clusters by density, and can identify clusters of arbitrary shape and detect outliers in low-density regions.

In this jupyter notebook, I create some noisy blobs using the sklearn library, and implement DBSCAN to identify the clusters. The clusters with higher density have less outliers filtered out. Sklearn's built-in DBSCAN function is explored, and I also imlement the algorithm in 5 steps using my own code.


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
    Open dbscan.ipynb from the Jupyter interface.
4. **Run the Cells**