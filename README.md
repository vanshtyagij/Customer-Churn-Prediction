# Customer Churn Prediction

## Project Overview
This project aims to predict whether a telecom customer is likely to stop using a service. Machine learning classification models are used to identify potential customer churn based on customer information.

## Objectives
- Analyze customer data and identify churn patterns.
- Perform Exploratory Data Analysis (EDA).
- Train and evaluate machine learning models.
- Predict customer churn for new customer records.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Dataset
The project uses a synthetic telecom customer dataset containing 1,200 customer records.

Features include:
- Customer tenure
- Contract type
- Monthly and total charges
- Internet and phone services
- Payment method
- Demographic information

Target variable: Churn (Yes/No).

## Project Workflow
1. Data loading and exploration
2. Exploratory Data Analysis (EDA)
3. Data preprocessing and encoding
4. Train-test split
5. Logistic Regression
6. Random Forest
7. Model evaluation and comparison
8. Feature importance analysis
9. Customer churn prediction

## Machine Learning Models
- Logistic Regression
- Random Forest Classifier

## Model Evaluation
Models were evaluated using accuracy, precision, recall, F1-score and ROC-AUC.

Random Forest test results:
- Accuracy: 62.9%
- ROC-AUC: Approximately 0.68
- Correctly identified churn customers: 55 out of 88

## Visualizations
- Customer churn distribution
- Churn by contract type
- Confusion matrix
- ROC curve
- Feature importance chart

## Conclusion
This project demonstrates an end-to-end machine learning workflow for predicting telecom customer churn. The models can help identify customers who may be at risk of leaving a service.

Further improvements could include hyperparameter tuning, cross-validation and training with real customer data.

**Note:** This project uses synthetic data for educational purposes.

## How to Run
1. Download or clone this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open Customer_Churn_Prediction.ipynb in Jupyter Notebook.
4. Run the notebook cells in order.

## Project Type
Machine Learning Internship Project

