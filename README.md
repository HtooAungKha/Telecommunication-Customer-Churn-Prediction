# Telco Customer Churn Prediction Using Machine Learning

## Team Members

- Khant Lin
- Htoo Aung Kha
- Yadanar Lin

---

## About the Project

Customer churn is a common problem for telecommunication companies because losing customers means losing revenue. In this project, we are using machine learning to predict whether a customer is likely to leave the company based on their account information and the services they use.

We are building several machine learning models and comparing their performance to find the one that predicts customer churn the best.
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

## Project Goals

- Explore and understand the dataset
- Clean and prepare the data
- Train multiple machine learning models
- Compare model performance
- Find the features that have the biggest impact on customer churn

---

### Notebook 3 – Model Training

In Progress

Models to be trained:

- Logistic Regression
- Decision Tree
- Random Forest
- Multi-Layer Perceptron (MLP)
- LSTM (if time allows)

---

### Notebook 4 – Model Evaluation

Planned:

- Compare model performance
- Generate confusion matrices
- Plot ROC curves
- Compare evaluation metrics
- Select the best-performing model

---

## Evaluation Metrics

We will evaluate each model using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
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
│   └── preprocessor.joblib
│
├── Notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_model_evaluation.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository and install the required Python packages.

```bash
git clone <repository-url>](https://github.com/HtooAungKha/Telecommunication-Customer-Churn-Prediction.git)
cd telco-churn-project

pip install -r requirements.txt
```

---

## Course

**CS 171 – Introduction to Machine Learning**

San José State University

Summer 2026
