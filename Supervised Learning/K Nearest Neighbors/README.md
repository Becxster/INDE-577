# K Nearest Neighbors

In this notebook, I use the Seeds Dataset from UCI to run a K Nearest Neighbors machine learning model.

## Seeds Dataset

[UCI Machine Learning Repository - Seeds Dataset](https://archive.ics.uci.edu/dataset/236/seeds)

### Overview

The **Seeds Dataset** is from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/seeds) used primarily for classification tasks. It contains geometrical properties of wheat kernels belonging to three different varieties of wheat.

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
    Open k_nearest_nbrs.ipynb from the Jupyter interface.
4. **Run the Cells**