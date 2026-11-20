Loan Approval Prediction

Project Overview

This project uses Machine Learning classification algorithms to predict whether a loan application will be approved or rejected based on applicant information.

Problem Statement

The objective is to predict loan approval status using applicant-related features. This can help understand the factors associated with loan approval decisions.

Dataset

- File: "loan_approval_data.csv"
- Target Variable: "Loan_Approved"
- Problem Type: Binary Classification

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

Project Workflow

1. Data loading and understanding
2. Exploratory Data Analysis (EDA)
3. Data preprocessing
4. Handling missing values
5. Encoding categorical variables
6. Feature scaling
7. Train-test split
8. Model training
9. Model evaluation
10. Model comparison

Machine Learning Models

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Results

Model| Accuracy
Logistic Regression| 88.95%
Decision Tree| 94.21%
Random Forest| 95.26%
Gradient Boosting| 96.32%

Gradient Boosting performed the best among the four models tested, achieving an accuracy of 96.32% and an F1 Score of 94.31%.

Conclusion

This project helped me understand the complete Machine Learning workflow for a classification problem, including data preprocessing, handling missing values, encoding, scaling, training multiple models, and evaluating their performance.

Project Structure

Loan-Approval-Prediction/
│
├── Loan_Approval_Prediction.ipynb
├── README.md
├── requirements.txt
│
└── data/
    └── loan_approval_data.csv

---

Created as a Machine Learning project for learning and practice.