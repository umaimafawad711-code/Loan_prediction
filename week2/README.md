# Week 2: Data Preparation & Feature Engineering

## Dataset Name & Source
*   **Dataset:** Loan Prediction Problem Dataset
*   **Source:** Kaggle (https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)

## Project Summary
This project focuses on taking a raw loan prediction dataset and making it ready for a machine learning model. The dataset contains 614 records and 13 columns. The goal is to predict the target variable `Loan_Status` (Y/N) using supervised binary classification. 
The notebook covers Exploratory Data Analysis (EDA), data cleaning (handling missing values and dropping useless columns), feature engineering (creating TotalIncome and EMI), train/test splitting (80/20 with stratification), and preprocessing using `ColumnTransformer` and `Pipeline` (scaling numerical data and encoding categorical data) without any data leakage.

## How to Run the Notebook
1. Clone this repository or download the files.
2. Ensure you have `pandas`, `scikit-learn`, `matplotlib`, and `seaborn` installed (see `requirements.txt`).
3. Open the `.ipynb` notebook in Jupyter Notebook or Google Colab.
4. Run all the cells from top to bottom. Ensure the dataset file `train_u6lujuX_CVtuZ9i.csv` is in the same directory as the notebook.
