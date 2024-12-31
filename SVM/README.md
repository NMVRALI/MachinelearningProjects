
# Support Vector Machines on the Fashion MNIST Dataset

This project applies the Support Vector Classifier (SVC) to the Fashion MNIST dataset, a collection of 28x28 grayscale images representing various fashion products. The primary objective is to classify these images using SVMs with techniques like feature scaling, dimensionality reduction, and hyperparameter tuning.

## Project Overview

1. **Dataset Loading**:
   - The Fashion MNIST dataset is fetched from OpenML using `sklearn.datasets`.
   - It contains 60,000 training images and 10,000 test images.

2. **Data Visualization**:
   - Sample images from the dataset are visualized to understand the data distribution.

3. **Preprocessing**:
   - The dataset is split into training and test sets.
   - Feature scaling is performed using `StandardScaler` for optimal SVM performance.
   - PCA is applied for dimensionality reduction to speed up computations.

4. **Model Training**:
   - A `LinearSVC` model is trained on a subset of the dataset.
   - Performance is evaluated using accuracy scores and a confusion matrix.

5. **Hyperparameter Tuning**:
   - `GridSearchCV` is employed to tune parameters like `C`, `kernel`, and `gamma` for the `SVC` model.
   - Best parameters and cross-validation scores are reported.

6. **Results**:
   - Achieved an accuracy of approximately 86% with the RBF kernel.
   - Results are visualized in a confusion matrix and a formatted results table.

## Requirements

To run this project, install the following Python libraries:
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `pandas`
- `numpy`

## How to Run

1. Clone this repository.
2. Ensure the required libraries are installed.
3. Run the script in your Python environment.

## Key Takeaways

- Proper preprocessing (e.g., scaling, PCA) significantly impacts SVM performance.
- Hyperparameter tuning is essential for achieving optimal results.
- SVMs are powerful for high-dimensional datasets but can be computationally intensive.

## Future Improvements

- Experiment with additional kernels (e.g., sigmoid, polynomial).
- Use advanced feature engineering techniques.
- Apply ensemble methods or other classifiers for comparison.
