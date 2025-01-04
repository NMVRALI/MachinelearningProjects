
# PCA on Olivetti Faces Dataset

## Overview
This project explores **Principal Component Analysis (PCA)**, a fundamental technique in machine learning for dimensionality reduction and feature extraction. We apply PCA to the **Olivetti faces dataset** to demonstrate how it can be used to compress and reconstruct images, and to evaluate its effect on machine learning model performance.

## Objectives
1. **Load and visualize** the Olivetti faces dataset.
2. **Apply PCA** to reduce the dimensionality of the dataset.
3. **Determine the optimal number of PCA components** using the elbow method.
4. **Visualize the effect** of PCA on image reconstruction.
5. **Compare the performance** of models trained on both the original dataset and the PCA-reduced dataset.

## Prerequisites
To run this project, you need the following libraries installed:
- **Python 3.x** or higher
- **NumPy**
- **matplotlib**
- **scikit-learn**

You can install the necessary libraries using pip:

```bash
pip install numpy matplotlib scikit-learn
```

## Dataset
The project uses the **Olivetti faces dataset**, which consists of grayscale images of faces. Each image is of size 64x64 pixels, and the dataset contains 400 images of 40 individuals, with 10 different images for each person.

## Steps Involved
1. **Load the dataset**: We load the Olivetti faces dataset from scikit-learn's built-in dataset repository.
2. **Apply PCA**: PCA is applied to reduce the dimensionality of the images, while maintaining most of the variance.
3. **Determine optimal components**: Using the elbow method, we determine the optimal number of components that explain 95% of the variance.
4. **Image Reconstruction**: The images are reconstructed from the reduced components to observe how much information is retained.
5. **Model Performance**: Logistic Regression models are trained on both the original and PCA-reduced datasets, and their performances are compared.

## Usage
1. **Clone the repository**:
```bash
git clone https://github.com/NMVRALI/MachinelearningProjects.git
```

2. **Navigate to the PCA folder**:
```bash
cd MachinelearningProjects/PCA
```

3. **Run the Jupyter Notebook**:
   Open the `PCA_Olivetti_Faces.ipynb` notebook in Jupyter or any other compatible environment to start exploring the project.

## Conclusion
In this project, you've learned how to apply PCA on image data, how to choose the number of components, and the effects of PCA on image reconstruction and model performance. This exercise is a great way to understand the trade-offs between data reduction and information retention in machine learning.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
