# Telco Customer Churn Prediction Using Machine Learning

## Team Members

- Khant Lin
- Htoo Aung Kha
- Yadanar Lin

---

## About the Project

We are building several machine learning models and comparing their performance to find the one that predicts customer churn the best.

Customer churn is a major challenge for telecommunication companies because losing customers leads to lost revenue. In this project, we use machine learning to predict whether a customer is likely to leave the company based on their account information and the services they use.

We compare several machine learning models to find the one that gives the best prediction performance.
---

## Dataset

We are using the **Telco Customer Churn** dataset from Kaggle.

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The dataset contains information for more than 7,000 customers, including:

- Gender
- Senior Citizen
- Partner and Dependents
- Internet Service
- Phone Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Tenure
- Customer Churn

---

## Project Progress

### Notebook 1 – Data Exploration


Completed:

- Loaded and explored the dataset
- Checked data types and missing values
- Analyzed the distribution of customer churn
- Visualized important features using charts
- Looked for patterns and relationships in the data
- Identified data quality issues before preprocessing

---

### Notebook 2 – Data Preprocessing

Completed:

- Cleaned the `TotalCharges` column
- Removed unnecessary columns
- Encoded the target variable
- Split the dataset into training, validation, and test sets
- Encoded categorical features
- Scaled numerical features
- Saved the processed datasets
- Saved the preprocessing pipeline

---

### Notebook 3 – Model Training

Completed:

- Loaded the processed datasets
- Trained Logistic Regression
- Trained Decision Tree
- Trained Random Forest
- Trained Multi-Layer Perceptron (MLP)
- Compared the models using the validation set
- Saved the trained models
- Saved the validation results

---

### Notebook 4 – Model Evaluation

Completed:

- Loaded the trained models
- Evaluated each model using the test dataset
- Compared Accuracy, Precision, Recall, F1-Score, and ROC-AUC
- Generated classification reports
- Created confusion matrices
- Plotted ROC curves
- Compared model performance with charts
- Analyzed Random Forest feature importance
- Selected the best-performing model
- Saved the final test results

---

## Models

The following models are included:

- Logistic Regression
- Decision Tree
- Random Forest
- Multi-Layer Perceptron (MLP)

---

## Evaluation Metrics

The models are compared using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Jupyter Notebook

---

## Project Structure

```text
Telecommunication-Customer-Churn-Prediction/
│
├── DataSet/
│   ├── processed/
│   │   ├── telco_churn_train.csv
│   │   ├── telco_churn_validation.csv
│   │   └── telco_churn_test.csv
│   │
│   └── Telco-Customer-Churn.csv
│
├── models/
│   ├── preprocessor.joblib
│   ├── logistic_regression.joblib
│   ├── decision_tree.joblib
│   ├── random_forest.joblib
│   ├── mlp.joblib
│   ├── validation_results.csv
│   └── test_results.csv
│
├── Notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_model_evaluation.ipynb
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Installation

Clone the repository and install the required Python packages.

```bash
git clone (https://github.com/HtooAungKha/Telecommunication-Customer-Churn-Prediction.git)
cd telco-churn-project

pip install -r requirements.txt
```

---

## Course

**CS 171 – Introduction to Machine Learning**

San José State University

Summer 2026