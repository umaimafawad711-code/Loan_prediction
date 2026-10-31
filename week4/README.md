# Week 4: Model Comparison, Cross-Validation, and Tuning

## Dataset Name & Source
*   **Dataset:** Loan Prediction Problem Dataset (Continued from Week 2 & 3)
*   **Source:** Kaggle 
*   **Target Variable:** `Loan_Status` (Y/N)

## Project Summary
This project focuses on comparing multiple machine learning models (KNN, Decision Tree, Random Forest, Gradient Boosting, and Logistic Regression) using 5-fold cross-validation. 
We tuned KNN and Decision Tree models to find their optimal hyperparameters (Best K=9, Best Depth=2) and used GridSearchCV to tune the Random Forest (Best: n_estimators=100, max_depth=5). We also checked for overfitting by comparing Train vs. Test scores. 
**Final Decision:** Logistic Regression was chosen as the final model because it achieved the highest test accuracy (86.18%) and provides high explainability, which is crucial for banking problems where understanding why a loan was rejected is important.

## How to Run the Notebook
1. Clone this repository or download the files.
2. Ensure you have `pandas`, `scikit-learn`, `matplotlib`, and `seaborn` installed.
3. Open the `.ipynb` notebook in Jupyter Notebook or Google Colab.
4. Make sure the dataset file `train_u6lujuX_CVtuZ9i.csv` is in the same directory.
5. Run all the cells from top to bottom. The notebook is designed to run end-to-end without errors and includes the Week 2 data preparation steps.
