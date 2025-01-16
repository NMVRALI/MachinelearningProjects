
# Anomaly Detection

This project aims to build an anomaly detection model to identify fraudulent credit card transactions using unsupervised learning techniques. The dataset used is publicly available on Kaggle and contains information about credit card transactions, with labels indicating fraudulent and non-fraudulent transactions.

## Dataset

The dataset used in this project is available at the following Kaggle link:
- [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download)

### Dataset Overview
The dataset contains 284,807 credit card transactions, with the following features:
- `Time`: The number of seconds elapsed between this transaction and the first transaction in the dataset.
- `Amount`: The purchase amount for this transaction.
- `Class`: The target variable, where `1` indicates a fraudulent transaction and `0` indicates a non-fraudulent transaction.

### Key Libraries Used
- `pandas`: Data manipulation and analysis.
- `scikit-learn`: Machine learning models and metrics.
- `seaborn` and `matplotlib`: Data visualization.
- `time`: For measuring model training time.

## Project Description

### 1. Data Exploration and Preprocessing

- **Load the Dataset**: The dataset is loaded and inspected to understand its structure.
- **Exploratory Data Analysis (EDA)**: 
  - Visualized the class distribution to understand the imbalance between fraudulent and non-fraudulent transactions.
  - Investigated the distribution of the `Amount` and `Time` features.
  - Analyzed correlations among the features.
  - Plotted the distribution of fraudulent vs non-fraudulent transaction amounts.

### 2. Model Preparation and Training

The following anomaly detection models were trained and evaluated on the dataset:
- **Isolation Forest**: A tree-based algorithm for anomaly detection.
- **Local Outlier Factor (LOF)**: A density-based algorithm for detecting local outliers.
- **Elliptic Envelope (Robust Covariance)**: A model based on robust statistics for detecting anomalies.
- **One-Class SVM**: A support vector machine-based model designed for outlier detection.

### 3. Model Evaluation

The performance of each model was evaluated using accuracy, precision, recall, and F1-score metrics. The time taken for each model's training was also recorded.

### Best Model: **Isolation Forest**
After evaluating all the models, **Isolation Forest** performed the best for detecting fraudulent transactions. It demonstrated the highest accuracy and was able to effectively distinguish between fraudulent and non-fraudulent transactions.

## Steps to Run the Project

### 1. Install Dependencies
You can install the required libraries using `pip`:

```bash
pip install pandas scikit-learn seaborn matplotlib
```

### 2. Download the Dataset
Download the dataset from Kaggle and save it in the project directory. You can use the following link to download the dataset:
- [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download)

### 3. Run the Code
After installing the necessary libraries and downloading the dataset, run the Python script to load the dataset, train the models, and evaluate their performance.

```bash
python anomaly_detection.py
```

## Conclusion

In this project, we demonstrated how unsupervised learning models can be applied to credit card fraud detection. Among the models evaluated, **Isolation Forest** performed the best in detecting fraudulent transactions. This model can be used in real-world applications to improve fraud detection systems in financial institutions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
