# LoanWise-Intelligent-Loan-Approval-Prediction-System
A machine learning project that analyzes applicant financial and demographic information to predict loan approval outcomes using Python, Pandas, NumPy, and Scikit-learn. Using different ML models like LogisticRegression, KNeighborsClassifier, GaussianNB
# LoanWise – Loan Approval Prediction System

## Overview
LoanWise is a machine learning project designed to predict loan approval outcomes using applicant information and financial indicators. The project explores how data preprocessing, exploratory data analysis, feature engineering, and classification algorithms can be used to analyze loan approval decisions.

## Objectives
- Analyze applicant and loan-related data.
- Clean missing values and prepare data for machine learning.
- Explore relationships between applicant characteristics and loan approval.
- Train and evaluate multiple classification models.
- Compare model performance using classification metrics.

## Technologies Used
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Environment:** Jupyter Notebook

## Project Workflow
1. Load and inspect the loan approval dataset.
2. Perform data cleaning and handle missing values.
3. Conduct exploratory data analysis (EDA) using charts and correlation analysis.
4. Encode categorical variables into numerical features.
5. Apply feature engineering to selected numerical variables.
6. Split the dataset into training and testing sets.
7. Scale features using StandardScaler.
8. Train and evaluate classification models.

## Machine Learning Algorithms
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

## Evaluation Metrics
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Repository Structure
```text
LoanWise-Loan-Approval-Prediction/
├── Loan_Wise.ipynb
├── loan_approval_data.csv
└── README.md
```

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Open the notebook:
   ```bash
   jupyter notebook LoanWise_Loan_Approval.ipynb
   ```
4. Run the notebook cells in sequence.

## Disclaimer
This is an educational machine learning project. Its predictions are not intended to replace professional credit assessment or real-world lending decisions.
