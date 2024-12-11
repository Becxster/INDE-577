# Neural Network Classification
This Jupyter Notebook demonstrates the implementation and training of a neural network for classification on the CMU Face Images dataset. First, we include data preprocessing steps like converting images to grayscale, flattening the images, and one-hot encoding the labels. Then, we defines a neural network class, train the model using stochastic gradient descent, and evaluates its performance on the test set across a couple labels.

## CMU Face Images Dataset

The CMU Face Images dataset is a collection of face images used for research in computer vision and machine learning provided by the UCI Machine Learning Repository. It contains grayscale images of faces with varying expressions, poses, and lighting conditions in pmf format.

### Dataset Details

- **Source**: Carnegie Mellon University
- **Repository**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/124/cmu+face+images)
- **Number of Images**: 640
- **Image Resolution**: 128x120 pixels
- **Format**: Grayscale images

### Features

The dataset includes images of 20 individuals, each with 32 different images. The variations in the images include:

- Userid: The individual in the photo
- Pose: (e.g., looking left, right, up, down)
- Exression: Different facial expressions (e.g., happy, sad, angry) 
- Eyes: Open or sunglasses

*Note that I only used images with a scale value of 4.*


#### Citation 

```
@misc{cmu_face_images,
    author = {Carnegie Mellon University},
    title = {CMU Face Images Dataset},
    year = {1996},
    url = {https://archive.ics.uci.edu/dataset/124/cmu+face+images}
}
```

For more information and to download the dataset, visit the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/124/cmu+face+images).

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
    Open neural_networks.ipynb from the Jupyter interface.
4. **Run the Cells**