# Week 3: Supervised Learning Models

## Dataset Name & Source
*   **Dataset:** Loan Prediction Problem Dataset (Continued from Week 2)
*   **Source:** Kaggle 
*   **Target Variable:** `Loan_Status` (Y/N)

## Project Summary
This project implements and compares three supervised classification models: K-Nearest Neighbors (KNN), Decision Tree, and Logistic Regression. 
The dataset was preprocessed using standard scaling and encoding. KNN was tuned by finding the best `K` value, and the Decision Tree was tuned by finding the best `max_depth` to prevent overfitting. 
**Best Model:** Logistic Regression (and Decision Tree). The models were evaluated using Accuracy, Confusion Matrix, and F1-Score. Since this is a banking problem, False Positives are very costly, making Recall and F1-score crucial metrics.

## How to Run the Notebook
1. Navigate to the Week 3 folder.
2. Open the `.ipynb` notebook in Jupyter or Google Colab.
3. Make sure the preprocessed dataset from Week 2 is available or run the data prep cells included in this notebook.
4. Run all cells top to bottom to see the graphs and evaluation metrics.
