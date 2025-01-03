
# Model Performance Evaluation

This project evaluates the performance of various machine learning models and visualizes their accuracy scores.

## Dataset
The dataset used in this project is sourced from Kaggle:  
[Fake News Dataset](https://www.kaggle.com/c/fake-news/data)

## Models Used
- Decision Tree
- Random Forest
- XGBoost
- ExtraTrees
- LightGBM

## How to Run
1. Make sure the required libraries are installed:
   ```bash
   pip install scikit-learn matplotlib xgboost lightgbm
   ```

2. Replace the placeholders in the code with your pre-trained models:
   ```python
   pretrained_models = {
       "Decision Tree": decision_tree_model,
       "Random Forest": random_forest_model,
       "XGBoost": xgboost_model,
       "ExtraTrees": extratrees_model,
       "LightGBM": lightgbm_model
   }
   ```

3. Run the code to evaluate models and view the chart.

## Output
The code generates a horizontal bar chart showing the accuracy of each model, with the exact values labeled on the bars.

## Requirements
- Python 3.7+
- scikit-learn
- matplotlib
- XGBoost
- LightGBM

## Credits
- Dataset: [Fake News Dataset on Kaggle](https://www.kaggle.com/c/fake-news/data)
