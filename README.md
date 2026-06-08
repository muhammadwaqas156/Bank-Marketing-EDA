# 📊 Bank Marketing Campaign Analysis & Predictive Modeling

A complete end-to-end Data Science project focused on Exploratory Data Analysis (EDA), feature engineering, and machine learning to predict customer subscription to bank term deposits.

---

## 📌 Project Overview

This project analyzes the Bank Marketing Dataset, which contains information about direct marketing campaigns conducted by a Portuguese banking institution.

The objective is to identify the key factors influencing whether a customer subscribes to a term deposit and develop a machine learning model capable of predicting future customer responses.

### 🎯 Project Goals

* Perform comprehensive Exploratory Data Analysis (EDA)
* Identify patterns and trends affecting customer subscriptions
* Preprocess and prepare data for machine learning
* Build and evaluate a classification model
* Interpret feature importance and business insights

---

## 📂 Dataset Description

The dataset contains over **41,000 customer records** with demographic, financial, and campaign-related information.

### Features Included

#### Demographic Information

* Age
* Job
* Marital Status
* Education

#### Financial Attributes

* Account Balance
* Housing Loan Status
* Personal Loan Status
* Credit Default Status

#### Campaign Information

* Contact Type
* Contact Month & Day
* Call Duration
* Number of Campaign Contacts

#### Historical Marketing Data

* Previous Campaign Outcome
* Number of Previous Contacts
* Days Since Last Contact

#### Target Variable

* **Yes** → Customer subscribed to a term deposit
* **No** → Customer did not subscribe

---

## 🔍 Exploratory Data Analysis (EDA)

The EDA phase was conducted to uncover customer behavior patterns and identify factors affecting subscription rates.

### 🧑‍🤝‍🧑 Demographic Insights

* Most customers are between 25–55 years old.
* Age distribution is positively skewed.
* Management, technician, and blue-collar occupations dominate the dataset.
* Customers with tertiary education show slightly higher subscription rates.
* Single customers tend to subscribe more often than married or divorced customers.

### 💰 Financial Insights

* Account balance distribution is highly skewed with significant outliers.
* Customers without housing loans are more likely to subscribe.
* Personal loan holders have lower subscription rates.
* Balance segmentation reveals clear behavioral differences among customers.

### 📞 Campaign Insights

* Call duration is the strongest indicator of subscription success.
* Increasing the number of campaign contacts generally reduces effectiveness.
* Customers with successful outcomes from previous campaigns are significantly more likely to subscribe again.

### 📊 Target Variable Analysis

* Approximately **11.7%** of customers subscribed.
* The dataset is highly imbalanced, making recall and precision important evaluation metrics.

---

## 🛠️ Data Preprocessing

The following preprocessing techniques were applied:

* Missing value handling
* Categorical variable encoding
* Numerical feature scaling
* Feature transformation and binning
* Train-test split preparation
* Class imbalance assessment

---

## 🤖 Machine Learning Model

A classification model was developed using Scikit-Learn to predict customer subscription outcomes.

### Model Performance

| Metric          | Score |
| --------------- | ----- |
| Accuracy        | 98.6% |
| Precision (Yes) | 0.67  |
| Recall (Yes)    | 0.39  |
| F1-Score (Yes)  | 0.49  |

### Key Findings

* The model achieves high overall accuracy.
* Class imbalance impacts minority-class prediction performance.
* The model predicts non-subscribers effectively.
* Improving recall for subscribers remains a key area for future enhancement.

---

## 🔥 Feature Importance

The most influential features identified by the model include:

1. Duration
2. Balance
3. Age
4. Previous Campaign Outcome (Success)
5. Days Since Last Contact (pdays)
6. Campaign Contacts
7. Education Level
8. Housing Loan Status

These findings closely align with insights discovered during exploratory analysis.

---

## 📈 Visualizations

The project includes the following visualizations:

* Age Distribution
* Job vs Subscription
* Education vs Subscription
* Marital Status vs Subscription
* Balance Distribution
* Housing Loan Impact
* Personal Loan Impact
* Campaign Analysis
* Subscription Distribution
* Call Duration Analysis
* Feature Importance Ranking
* Correlation Heatmap

---

## 🚀 Future Improvements

Potential enhancements include:

* Apply SMOTE for class balancing
* Use class-weighted models
* Hyperparameter tuning with GridSearchCV
* Compare Random Forest, XGBoost, and LightGBM
* Perform threshold optimization
* Implement SHAP for model explainability
* Deploy the model using Streamlit or Flask

---

## 📦 Project Structure

```text
Bank-Marketing-EDA-Model/
│
├── data/
│   └── bank.csv
│
├── notebooks/
│   ├── EDA.ipynb
│   └── Model_Training.ipynb
│
├── images/
│   ├── age_distribution.png
│   ├── job_vs_subscription.png
│   ├── education_vs_subscription.png
│   ├── marital_vs_subscription.png
│   ├── balance_boxplot.png
│   ├── housing_loan_vs_subscription.png
│   ├── personal_loan_vs_subscription.png
│   ├── subscription_percentage.png
│   ├── campaign_vs_subscription.png
│   ├── duration_vs_subscription.png
│   └── feature_importance.png
│
├── src/
│   ├── preprocess.py
│   ├── train_model.py
│   └── evaluate_model.py
│
├── README.md
└── requirements.txt
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📚 Key Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning & Preprocessing
* Feature Engineering
* Data Visualization
* Classification Modeling
* Model Evaluation
* Feature Importance Analysis
* Business Insight Generation

---

## 👨‍💻 Author

**Muhammad Waqas**

Aspiring Data Analyst and Machine Learning Practitioner passionate about transforming raw data into actionable insights through analytics, visualization, and predictive modeling.

### Connect With Me

* GitHub: https://github.com/muhammadwaqas156
* LinkedIn: https://www.linkedin.com/in/muhammadwaqas2798156
