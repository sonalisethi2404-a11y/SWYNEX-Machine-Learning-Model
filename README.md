# SWYNEX – Machine Learning Model

## Project Overview
This project focuses on building and evaluating machine learning classification models using the Titanic dataset.

The objective is to predict whether a passenger survived based on passenger information.

## Dataset
- Dataset: Titanic Dataset
- Target Variable: Survived
- Input Features: Passenger class, sex, age, fare, family information and embarkation details.

## Data Preparation
- Handled missing values.
- Removed unnecessary columns.
- Encoded categorical variables.
- Used the cleaned dataset from Task 1.

## Machine Learning Models
1. Logistic Regression
2. Random Forest Classifier

## Evaluation Metrics
Both models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Files
- `Titanic-Machine-Learning.ipynb` – Model training and evaluation.
- `Titanic-Cleaned.csv` – Cleaned Titanic dataset.
- `model_comparison.csv` – Model performance comparison.
- Confusion matrix images – Model evaluation visualizations.
- `requirements.txt` – Required Python libraries.

## Conclusion
The project compares Logistic Regression and Random Forest to identify which model performs better on the Titanic dataset using multiple evaluation metrics.