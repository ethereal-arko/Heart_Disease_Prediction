# Heart Disease Prediction using Logistic Regression

## Project Overview

This project uses Machine Learning to predict heart disease labels based on patient-related clinical features. A Logistic Regression classifier is trained and evaluated using a structured dataset.

The project demonstrates a basic end-to-end Machine Learning workflow, including data exploration, preprocessing, model training, evaluation, and prediction.

## Objectives

- Explore and understand the dataset.
- Identify missing values and duplicate records.
- Analyze target distribution and feature correlations.
- Train a Logistic Regression classification model.
- Evaluate performance using multiple classification metrics.
- Build a simple prediction system for new input data.

## Dataset

- **Original records:** 303
- **Records after duplicate removal:** 302
- **Input features:** 13
- **Target variable:** `target`

The target variable represents the class labels provided by the dataset. The model's predictions are intended for educational purposes, not clinical diagnosis.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Machine Learning Workflow

1. Import libraries and load the dataset.
2. Perform exploratory data analysis (EDA).
3. Check missing values and remove duplicate records.
4. Separate features and target labels.
5. Split the dataset into training and testing sets using stratified sampling.
6. Scale features using `StandardScaler`.
7. Train a Logistic Regression model using a Scikit-learn Pipeline.
8. Evaluate the model using accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC.
9. Build a prediction system for a new input sample.

## Model Performance

| Metric | Result |
|---|---:|
| Training Accuracy | 85.48% |
| Testing Accuracy | 78.69% |
| ROC-AUC Score | 0.8647 |
| Recall for target = 1 | 87.88% |
| F1-score for target = 1 | 0.82 |

These results are based on a single train-test split. Further validation is necessary to assess performance stability and generalization.

## Repository Contents

- `Heart_Disease_Prediction.ipynb` — Notebook containing the complete workflow.
- `heart_disease_data.csv` — Dataset used for model development.
- `README.md` — Project documentation.

## Limitations and Future Improvements

- The dataset is relatively small.
- Evaluation uses a single train-test split.
- Performance should be validated using stratified cross-validation.
- Future work may compare Logistic Regression with SVM, Decision Tree, and Random Forest.
- Probability calibration and independent dataset validation could be explored.




