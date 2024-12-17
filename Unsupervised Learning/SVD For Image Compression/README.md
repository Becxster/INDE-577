# Image Compression Using Single Value Decomposition (SVD)

In this notebook, I use single value decomposition to compress an image of a koala. The image can be found [here](https://wwf.org.uk/learn/fascinating-facts/koala). 

Singular Value Decomposition (SVD) is a mathematical technique used to factorize a matrix into three components:
$$
A = U \Sigma V^\top
$$
Where:
- $ A $: The original matrix (e.g., pixel intensity values of an image).
- $ U $: Left singular vectors (column space).
- $ \Sigma $: Singular values (a diagonal matrix with decreasing values representing importance).
- $ V^\top $: Right singular vectors (row space).

For lower values of $k$, the image is compressed into fewer bytes. The pixels that are most 'vital' to the image's structure are retained.

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
    Open img_compression_svd.ipynb from the Jupyter interface.
4. **Run the Cells**