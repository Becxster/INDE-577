
# Random Forest
In this notebook, I use the Forest Fires dataset to develop a random forest model. Random forest is an ensemble machine learning algorithm that combines multiple decision trees which improves accuracy and discourages overfitting. It works by training multiple decision trees on random subsets of the data and features, and then aggregating their predictions.


## Forest Fires Dataset Overview
The Forest Fires dataset contains 12 features and a highly skewed output variable (`area`, the burned area of the forest). 

### **Title**
Forest Fires Dataset

### **Sources**
- **Created by**: Paulo Cortez and Aníbal Morais (University of Minho)  
- **Year**: 2007  

### **Past Usage**
In the original study by Cortez and Morais (2007), the dataset was used to predict the burned area of forest fires using various data mining methods. A logarithmic transformation (`ln(x + 1)`) was applied to the output variable `area` to handle its skewness. The transformed values were then processed using several regression techniques, with experiments conducted using 10-fold cross-validation repeated 30 times. 

The best-performing model, a Gaussian Support Vector Machine (SVM), achieved:
- **Mean Absolute Deviation (MAD)**: 12.71 ± 0.01
- **Root Mean Squared Error (RMSE)**: Naive mean predictor performed best for RMSE.  

The SVM model demonstrated better performance in predicting small fires, which constitute the majority of the dataset.

Full details of the methodology and results can be found in the original paper: [http://www.dsi.uminho.pt/~pcortez/fires.pdf](http://www.dsi.uminho.pt/~pcortez/fires.pdf).

#### Citation Request
This dataset is publicly available for research. If you plan to use this database, please include the following citation:

> P. Cortez and A. Morais. A Data Mining Approach to Predict Forest Fires using Meteorological Data.  
> In J. Neves, M. F. Santos and J. Machado Eds., *New Trends in Artificial Intelligence, Proceedings of the 13th EPIA 2007 - Portuguese Conference on Artificial Intelligence*, December, Guimarães, Portugal, pp. 512-523, 2007. APPIA, ISBN-13 978-989-95618-0-9.  
> Available at: [http://www.dsi.uminho.pt/~pcortez/fires.pdf](http://www.dsi.uminho.pt/~pcortez/fires.pdf)

---
---

## Dataset Information

- **Number of Instances**: 517
- **Number of Attributes**: 12 features + 1 output attribute (`area`)

### **Relevant Information**
- This dataset represents a challenging regression problem.
- It is suitable for testing:
  - Regression methods.
  - Outlier detection techniques (due to the presence of outliers).
- Note: The number of large fires (large burned area) is very small, and attributes may be correlated. Feature selection methods may be useful.

---

## Attribute Information

1. **X**: x-axis spatial coordinate within the Montesinho park map (range: 1 to 9).
2. **Y**: y-axis spatial coordinate within the Montesinho park map (range: 2 to 9).
3. **month**: Month of the year (e.g., "jan" to "dec").
4. **day**: Day of the week (e.g., "mon" to "sun").
5. **FFMC**: Fine Fuel Moisture Code from the FWI system (range: 18.7 to 96.20).
6. **DMC**: Duff Moisture Code from the FWI system (range: 1.1 to 291.3).
7. **DC**: Drought Code from the FWI system (range: 7.9 to 860.6).
8. **ISI**: Initial Spread Index from the FWI system (range: 0.0 to 56.10).
9. **temp**: Temperature in Celsius degrees (range: 2.2 to 33.30).
10. **RH**: Relative humidity in % (range: 15.0 to 100).
11. **wind**: Wind speed in km/h (range: 0.40 to 9.40).
12. **rain**: Outside rain in mm/m² (range: 0.0 to 6.4).
13. **area**: Burned area of the forest (in hectares) (range: 0.00 to 1090.84).  
    - Note: The `area` attribute is highly skewed toward 0.0, and applying a logarithmic transformation (`ln(x + 1)`) may improve modeling.

---

No missing attribute values

---

For further details, please refer to the original paper: [http://www.dsi.uminho.pt/~pcortez/fires.pdf](http://www.dsi.uminho.pt/~pcortez/fires.pdf)


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
    Open random_forests.ipynb from the Jupyter interface.
4. **Run the Cells**