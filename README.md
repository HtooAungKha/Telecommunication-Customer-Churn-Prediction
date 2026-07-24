# Telco Customer Churn Prediction Using Machine Learning

## Team Members

- Khant Lin
- Htoo Aung Kha
- Yadanar Lin

---

## About the Project

Keeping existing customers is important for any business, especially telecommunication companies. In this project, we will build machine learning models to predict whether a customer is likely to leave the company based on their account information and the services they use.

Our goal is to compare different machine learning models and see which one gives the best prediction. We also want to understand which customer features are most related to customer churn.

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

## Project Goals

- Explore and understand the dataset
- Clean and prepare the data
- Train multiple machine learning models
- Compare model performance
- Find the features that have the biggest impact on customer churn

---

## Models

We plan to compare the following models:

- Logistic Regression
- Decision Tree
- Random Forest
- Multi-Layer Perceptron (MLP)
- LSTM

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
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

```text
telco-churn-project/
│
├── README.md
├── requirements.txt
├── telco_churn.csv
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_model_evaluation.ipynb
│
├── results/
│   ├── figures/
│   └── model_results.csv
│
└── report/
    └── final_paper.docx
```

---

## Installation

Clone the repository and install the required Python packages.

```bash
git clone <repository-url>
cd telco-churn-project

pip install -r requirements.txt
```

---

## Expected Outcome

By the end of this project, we hope to find the model that predicts customer churn the best and identify the customer features that have the biggest impact on churn. This project will also help us gain more experience with data preprocessing, model training, and model evaluation.

---

## Course

**CS 171 – Introduction to Machine Learning**

San José State University

Summer 2026