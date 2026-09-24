# Customer-Churn-Risk-Retention-Intelligence-System
An end-to-end Machine Learning and Streamlit-based system for predicting customer churn risk, identifying churn drivers, estimating revenue at risk, and generating actionable retention recommendations.

---

## 📌 Overview

Customer Churn Risk & Retention Intelligence System is an end-to-end Machine Learning and Business Intelligence application designed to help organizations identify customers who are likely to churn and understand the factors contributing to their churn risk.

The system transforms customer data into actionable insights by combining:

* Machine Learning-based churn prediction
* Customer risk segmentation
* Churn driver analysis
* Revenue-at-risk estimation
* Retention recommendations
* Interactive business dashboards

---

## 🎯 Project Objectives

The system focuses on five major objectives:

1. Predict customer churn probability
2. Segment customers according to their churn risk
3. Identify important factors associated with churn
4. Estimate potential recurring revenue exposure
5. Generate actionable retention recommendations

---

## 🏗️ System Architecture

The complete system follows a structured data-to-insight pipeline:

```text
                Customer Data
                     │
                     ▼
             Data Preparation
                     │
                     ▼
          Feature Transformation
                     │
                     ▼
          Machine Learning Model
                     │
                     ▼
            Churn Probability
                     │
          ┌──────────┴──────────┐
          ▼                     ▼
    Risk Segmentation      Driver Analysis
          │                     │
          └──────────┬──────────┘
                     ▼
          Revenue-at-Risk Analysis
                     │
                     ▼
        Retention Recommendations
                     │
                     ▼
          Interactive Dashboard
```

---

## 🔄 Machine Learning Pipeline

The machine learning pipeline processes raw customer information and converts it into churn-risk intelligence.

```text
Raw Customer Data
        ↓
Data Cleaning
        ↓
Missing Value Handling
        ↓
Categorical Encoding
        ↓
Feature Scaling
        ↓
Class-Balanced Learning
        ↓
Logistic Regression
        ↓
Churn Probability
        ↓
Risk Classification
        ↓
Driver Analysis
        ↓
Retention Intelligence
```

---

## ✨ Key Features

| Feature                       | Description                                                          |
| ----------------------------- | -------------------------------------------------------------------- |
| 🧹 Data Preparation       | Handles missing values, categorical variables and numerical features |
| 🤖 Churn Prediction       | Predicts customer churn probability using Machine Learning           |
| ⚖️ Class Balancing        | Uses balanced learning to address churn-class imbalance              |
| 🎯 Risk Segmentation      | Categorizes customers into Low, Medium and High risk                 |
| 🔎 Driver Analysis        | Identifies important customer-level churn signals                    |
| 💰 Revenue-at-Risk        | Estimates potential recurring revenue exposure                       |
| 💡 Retention Intelligence | Converts risk signals into possible retention actions                |
| 📊 Interactive Dashboard  | Provides KPIs, charts, filters and customer insights                 |
| 📁 Export Workflow        | Supports exporting analysis and prediction results                   |

---

# 🧠 Machine Learning Approach

## Model

The primary prediction model used in the system is:

Logistic Regression with balanced class weights

Logistic Regression is used to estimate the probability that a customer belongs to the churn class.

### Why Logistic Regression?

It provides:

* Probability-based predictions
* Interpretable model behavior
* Efficient training
* Good suitability for binary classification
* Useful feature-level insights for churn analysis

---

## 🔧 Data Preprocessing

### Numerical Features

```text
Missing Value Imputation
        ↓
Median Strategy
        ↓
Standard Scaling
```

### Categorical Features

```text
Missing Value Imputation
        ↓
Most-Frequent Strategy
        ↓
One-Hot Encoding
        ↓
Unknown Category Handling
```

---

## 📊 Prediction Workflow

```text
Customer Information
        ↓
Preprocessing Pipeline
        ↓
Trained ML Model
        ↓
Churn Probability
        ↓
Risk Band
        ↓
Churn Drivers
        ↓
Retention Recommendation
```

---

# 🎯 Customer Risk Segmentation

Customers are classified into three risk categories based on predicted churn probability.

| Risk Level         |     Probability | Interpretation                                  |
| ------------------ | --------------: | ----------------------------------------------- |
| 🟢 Low Risk    |        `< 0.35` | Relatively lower predicted churn risk           |
| 🟡 Medium Risk | `0.35 – < 0.60` | Customer should be monitored                    |
| 🔴 High Risk   |        `≥ 0.60` | Higher predicted churn risk requiring attention |

These thresholds are configurable and can be adjusted according to business requirements.

---


## KPI Dashboard

The dashboard can display:

* 👥 Total Customers
* 🚪 Churned Customers
* 📈 Churn Rate
* 🔴 High-Risk Customers
* 💰 Revenue at Risk

## Analytics

The analytics section provides insights such as:

* Churn distribution
* Risk-band distribution
* Contract analysis
* Service analysis
* Customer segmentation
* Revenue exposure

---

# 🛠️ Technology Stack

| Technology             | Purpose                        |
| ---------------------- | ------------------------------ |
| 🐍 Python          | Core development               |
| 🐼 Pandas          | Data manipulation and analysis |
| 🔢 NumPy          | Numerical computing            |
| 🤖 Scikit-learn    | Machine Learning               |
| 📊 Plotly          | Interactive visualizations     |
| 🎨 Streamlit       | Web dashboard                  |
| 💾 Joblib / Pickle | Model persistence              |
| 🔧 Git & GitHub    | Version control                |

---

# 📂 Project Structure

```text
Customer-Churn-Risk-Retention-Intelligence-System/
│
├── app.py
├── download_data.py
├── requirements.txt
├── run.bat
├── README.md
│
├── src/
│   └── churn_engine.py
│
├── assets/
│   ├── system_architecture.png
│   └── ml_pipeline.png
│
├── notebooks/
│
├── reports/
│
└── exports/
```

---

# 📊 Dataset

The project uses a telecom customer churn dataset containing customer demographic, service, contract, billing and churn information.

Typical features include:

* Customer tenure
* Contract type
* Internet/service type
* Monthly charges
* Total charges
* Payment method
* Paperless billing
* Customer service information
* Churn status

The dataset is used to train and evaluate the Machine Learning model and generate customer-level churn intelligence.

---


