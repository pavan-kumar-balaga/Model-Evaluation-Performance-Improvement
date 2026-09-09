# Machine Learning Model Evaluation – Mall Customers

## Project Overview

This project evaluates and compares multiple machine learning classification models using the **Mall Customers** dataset. The objective is to understand model performance, select appropriate evaluation metrics, compare models, and identify signs of overfitting and underfitting.

## Dataset

The dataset contains customer information such as:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

For this project, a binary target variable **High_Spender** was created from the Spending Score to formulate a classification problem.

## Models Evaluated

The following classification models were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors (KNN)
4. Random Forest Classifier

## Evaluation Metrics

The models were compared using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

A confusion matrix and classification report were also used to understand model performance in more detail.

## Train-Test Split

The dataset was divided into training and testing sets. The training data was used to build the models, while the unseen test data was used for final performance evaluation.

## Results

The executed notebook contains the complete model training process, evaluation metrics, visualizations, and performance comparison table.

Based on the F1-score in the test-set comparison, **Decision Tree and KNN** achieved the strongest performance in this experiment. The report discusses the strengths and weaknesses of each model and explains the final model recommendation.

## Overfitting and Underfitting

The project compares training and test performance to identify potential overfitting or underfitting.

- **Overfitting:** The model performs very well on training data but substantially worse on unseen test data.
- **Underfitting:** The model performs poorly on both training and test data.

## Repository Contents

```text
ML_Model_Evaluation_Mall_Customers.ipynb
ML_Model_Evaluation_Mall_Customers.html
ML_Model_Evaluation_Report.docx
performance_comparison_table.csv
Mall_Customers(1).csv
README.md
```

## How to Run

1. Clone or download this repository.
2. Keep the CSV dataset in the same folder as the notebook.
3. Open `ML_Model_Evaluation_Mall_Customers.ipynb` using Jupyter Notebook, JupyterLab, Google Colab, or VS Code.
4. Run the notebook cells from top to bottom.

The notebook is already executed and includes the generated outputs.

## Project Objective

The main objective is to demonstrate how evaluation metrics can be used to compare machine learning models and make an informed model-selection decision based on data and performance.

## Author

Machine Learning Internship Project
