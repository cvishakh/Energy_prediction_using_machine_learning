# Energy Prediction Using Machine Learning

## Objective
The aim of this project is to implement a supervised learning procedure for energy prediction in a machining process. The project includes pre- and post-processing steps to ensure the accuracy and reliability of the regression models used.

## Use Case
The primary focus is on predicting the energy requirement for a milling process. To achieve this, various regression models will be trained and evaluated to determine their performance in accurately predicting the target variable.

---

## Project Workflow

1. **Data Pre-Processing**:
   - Load and explore the dataset.
   - Handle missing values, normalize features, and split the data into training and testing sets.

2. **Model Training**:
   - Train multiple regression models such as:
     - Linear Regression
     - Support Vector Regression (SVR)
     - Decision Trees
     - Random Forests
     - Gradient Boosting
   - Evaluate each model's performance using appropriate metrics like Mean Squared Error (MSE) and R-squared.

3. **Model Evaluation**:
   - Compare model performances to select the most suitable one for energy prediction.
   - Analyze residuals and perform cross-validation for reliability.

4. **Post-Processing**:
   - Optimize model parameters if necessary.
   - Interpret results and discuss implications for energy efficiency in the machining process.

---

## Dataset
The dataset used for this project contains features relevant to the milling process and the associated energy consumption. It must be configured correctly to run the analysis.

**NOTE**: Ensure to adjust the `.txt` file path in the code to point to the correct location where you have stored the dataset on your PC.

---

## Requirements
- Python (version 3.11)
- Libraries:
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn

---

## Usage
1. Clone the repository and navigate to the project directory.
2. Adjust the dataset file path in the code to match your local setup.
3. Run the main script to perform data pre-processing, train models, and evaluate performance.

---

## Future Work
- Explore additional regression models for improved prediction accuracy.
- Experiment with feature engineering and dimensionality reduction techniques.
- Investigate the integration of real-time energy prediction in a manufacturing environment.

---


