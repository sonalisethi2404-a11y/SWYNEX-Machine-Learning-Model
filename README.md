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

## Model Comparison and Conclusion

Two machine learning classification models were trained and evaluated: Logistic Regression and Random Forest.

The evaluation results were:

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 80.45% | 82.12% |
| Precision | 79.31% | 81.36% |
| Recall | 66.67% | 69.57% |
| F1-score | 72.44% | 75.00% |

Random Forest performed better across all four evaluation metrics on the test dataset.

This may be because Random Forest can capture complex patterns and non-linear relationships in the data by combining multiple decision trees, whereas Logistic Regression models a linear relationship between the input features and the outcome.

Therefore, Random Forest was the better-performing model in this experiment.
