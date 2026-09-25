# Customer-Churn-Prediction
Predicting customer churn using Logistic Regression, Decision Tree, and Random Forest.
# Customer Churn Prediction

## 📌 Project Overview

Customer churn is a common business problem where companies try to identify customers who are likely to stop using their services.

In this project, I built a machine learning classification system to predict whether a customer is likely to **stay** or **churn**.

The project uses the Telco Customer Churn dataset and compares three machine learning algorithms:

- Logistic Regression
- Decision Tree
- Random Forest

The models were evaluated using Accuracy, Precision, Recall, F1 Score, and percentage-based Confusion Matrices.

---

## 🎯 Project Objective

The main objective of this project is to develop a machine learning model that can identify customers who are likely to churn.

The project also aims to:

- Practice data cleaning and preprocessing
- Handle numerical and categorical variables
- Apply feature scaling and encoding
- Build classification models
- Compare different machine learning algorithms
- Understand confusion matrices
- Evaluate models using multiple classification metrics

---

## 📊 Dataset

The project uses the **Telco Customer Churn dataset**.

The dataset contains information about customers, including:

- Customer demographics
- Services subscribed to
- Contract information
- Payment methods
- Monthly charges
- Total charges
- Customer tenure
- Churn status

### Target Variable

The target variable is:

`Churn`

It contains two possible values:

- `No` → Customer stayed
- `Yes` → Customer churned

For machine learning, these were converted to:

- `0` → Stayed
- `1` → Churned

---

## 🛠️ Technologies and Libraries

The project was developed using Python and the following libraries:

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

### Machine Learning Techniques

The project uses:

- Train/Test Split
- One-Hot Encoding
- Standardization
- Pipeline
- ColumnTransformer
- Logistic Regression
- Decision Tree
- Random Forest

---

## 🔄 Machine Learning Workflow

The project followed this workflow:


Dataset
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
Feature & Target Separation
   ↓
Train/Test Split
   ↓
Feature Preprocessing
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Model Comparison
