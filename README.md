# Loan Approval Prediction Using Machine Learning

## Overview

This project focuses on predicting loan approval outcomes using Machine Learning techniques. The objective is to analyze applicant information and determine the likelihood of loan approval based on various financial and demographic factors.

Two machine learning algorithms were implemented and compared:

* Linear Regression
* K-Nearest Neighbors (KNN)

The project evaluates the performance of both models and identifies the most effective approach for loan approval prediction.

---

## Dataset

The dataset contains information about loan applicants, including:

* Applicant Income
* Co-applicant Income
* Loan Amount
* Loan Amount Term
* Credit History
* Education
* Employment Status
* Marital Status
* Property Area

These features are used to train and evaluate the machine learning models.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Performance Comparison

---

## Models Implemented

### 1. Linear Regression

Linear Regression was used as a baseline model to establish relationships between applicant attributes and loan approval outcomes.

#### Performance

| Metric   | Score |
| -------- | ----- |
| Accuracy | 9%    |

---

### 2. K-Nearest Neighbors (KNN)

K-Nearest Neighbors (KNN) was implemented to classify loan applications based on similarity to neighboring data points in the feature space.

#### Performance

| Metric   | Score |
| -------- | ----- |
| Accuracy | 98%   |

---

## Results Comparison

| Model                     | Accuracy |
| ------------------------- | -------- |
| Linear Regression         | 9%       |
| K-Nearest Neighbors (KNN) | 98%      |

### Analysis

* Linear Regression achieved an accuracy of 9%, indicating poor performance for this prediction task.
* KNN achieved an accuracy of 98%, significantly outperforming Linear Regression.
* The results suggest that KNN is better suited for capturing complex relationships within the loan approval dataset.

---

## Key Features

* Data preprocessing and cleaning
* Feature selection and transformation
* Machine learning model implementation
* Comparative performance analysis
* Loan approval prediction

---

## Future Improvements

* Hyperparameter tuning for KNN
* Cross-validation techniques
* Feature optimization
* Comparison with Decision Tree, Random Forest, and XGBoost models
* Deployment using Flask or Streamlit
* Real-time loan approval prediction interface

---

## Repository Structure

```text
Loan-Approval-Prediction/
│
├── Loan_Approval_Model.ipynb
├── README.md
├── requirements.txt
├── dataset.csv
└── model.pkl
```

---

## Conclusion

This project demonstrates the application of machine learning techniques in loan approval prediction. Through comparative analysis, K-Nearest Neighbors (KNN) achieved the highest accuracy of 98%, making it the most effective model among those evaluated for this dataset.

---

## Author

**Gourang A M**

Software Engineer | AI & Machine Learning Enthusiast

Skills:

* Python
* Machine Learning
* Pandas & NumPy
* FastAPI
* Django
* AWS Cloud Foundations
