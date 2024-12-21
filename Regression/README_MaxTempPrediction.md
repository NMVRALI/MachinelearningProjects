# Max Temperature Prediction

## Project Overview
This project focuses on predicting the **Maximum Temperature (MaxTemp)** using various meteorological features, such as **Precipitation (Precip)**, **Mean Temperature (MeanTemp)**, **Snowfall**, and other related variables. By leveraging machine learning regression models, the goal is to build an accurate model for daily temperature predictions.

## Dataset
The dataset used in this project contains several weather-related variables, including:
- **Precipitation (Precip)**
- **Snowfall (Snowfall)**
- **MaxTemp** (the target variable)
- **Mean Temperature (MeanTemp)** and other relevant features.

## Project Workflow
1. **Data Exploration and Preprocessing:**
   - Load and examine the dataset.
   - Handle missing values and outliers.
   - Drop irrelevant features and preprocess categorical variables.

2. **Feature Engineering:**
   - Identify features relevant to predicting MaxTemp.
   - Visualize feature correlations with the target variable.

3. **Model Training and Evaluation:**
   - Split the data into training and testing sets.
   - Train a **Linear Regression** model.
   - Evaluate model performance using metrics like **Mean Squared Error (MSE)** and **R-squared (R²)**.

4. **Conclusions:**
   - Summarize the model's performance and suggest improvements.

## Files Included
- `MaxTemp Prediction.ipynb`: The main Jupyter Notebook containing the code and analysis.
- `data/ww-ii-data.csv`: The dataset used for training and testing (replace with link if hosted online).
- `requirements.txt`: A list of dependencies required to run the project.

## How to Run the Project
1. Ensure you have Python installed on your system.
2. Install the required dependencies by running the following command:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and execute the Jupyter Notebook:
   ```bash
   jupyter notebook MaxTemp\ Prediction.ipynb
   ```

## Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Future Work
- Experiment with advanced models like **Random Forest**, **XGBoost**, or **LightGBM**.
- Perform additional feature engineering to enhance accuracy.
- Develop a simple web-based user interface for model predictions.

## License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

## Author
GitHub: [NMVRALI](https://github.com/NMVRALI)
