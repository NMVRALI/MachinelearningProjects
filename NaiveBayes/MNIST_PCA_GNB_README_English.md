# MNIST Classification with PCA and Gaussian Naive Bayes

## Overview (English)
This project explores the classification of handwritten digits from the MNIST dataset using Gaussian Naive Bayes and Principal Component Analysis (PCA) for dimensionality reduction. The workflow demonstrates key steps, including:

1. Loading and preprocessing the MNIST dataset.
2. Evaluating model performance without dimensionality reduction.
3. Applying PCA to enhance model efficiency and reduce computation.
4. Hyperparameter tuning to improve accuracy.
5. Visualizing and interpreting results to determine optimal settings.

### Key Results
- **Without PCA**: Baseline accuracy achieved with Gaussian Naive Bayes.
- **With PCA**: Improved computational efficiency and accuracy by selecting the most informative features.
- **Optimal PCA Components**: Determined to achieve approximately 90% cumulative explained variance.
- **Hyperparameter Tuning**: Further refined model performance.

### How to Run
1. Ensure Python is installed with required libraries: `scikit-learn`, `numpy`, `matplotlib`, and `seaborn`.
2. Load the MNIST dataset using `fetch_openml`.
3. Follow the cells to preprocess data, apply PCA, train models, and visualize results.
