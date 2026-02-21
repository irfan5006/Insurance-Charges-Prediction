# Insurance Machine Learning Project
Author: Muhammad Irfan
Project Type: Regression

📖 Project Overview

This project predicts medical insurance charges based on features like age, BMI, smoking habits, and region.

🎯 Objective

To build a regression model that estimates insurance cost accurately.

## Dataset Features

Age
Sex
BMI
Children
Smoker
Region
Charges (Target Variable)

# 🛠 Technologies Used

Python
Pandas
Seaborn
Scikit-learn

# Models Used
Linear Regression
## Description

The notebook walks through:

1. **Exploratory Data Analysis** — visualizing distributions, correlations, and understanding dataset structure.
2. **Data Cleaning & Preprocessing** — handling duplicates, encoding categorical variables, scaling numerical features, and creating new features (BMI categories).
3. **Feature Engineering & Extraction** — generating dummy variables and standardizing columns.
4. **Statistical Analysis** — Pearson correlation and chi-square tests to evaluate feature relevance.
5. **Modeling** — splitting data into training and test sets, fitting linear regression manually, and evaluating performance with R² and adjusted R².


## Running the Notebook

1. Clone this repository or download the files.
2. Ensure you have Python 3 installed along with required libraries: `numpy`, `pandas`, `seaborn`, `matplotlib`, `scikit-learn`, and `scipy`.
3. Open `insurance.ipynb` in JupyterLab/Notebook or VS Code and execute cells sequentially.

## Notes

- The pipeline defined in the notebook scales numeric features and fits a `LinearRegression` model, producing comparable performance metrics to the manual approach.
- Feel free to extend the notebook with additional models, hyperparameter tuning, or cross-validation.

---