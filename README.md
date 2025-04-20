

# Churn Prediction Model

This project is a customer churn prediction model built using Python and Jupyter Notebook. The dataset is based on customer records from a bank, with features like age, balance, tenure, and activity status. The goal is to predict whether a customer is likely to leave the bank (churn) or stay.

## 📊 Dataset

The dataset used in this project is **Churn_Modelling.csv**, which contains the following key features:
- Customer demographics (Age, Gender, Geography)
- Financial information (Balance, Estimated Salary, Credit Score)
- Customer account details (Tenure, Number of Products, Active Membership)
- Churn status (Exited)

## 📌 Features Created

To improve model performance, the following additional features were engineered:
- `BalanceZero`: Binary feature indicating if the balance is zero.
- `AgeGroup`: Categorical age groups created from the age column.
- `BalanceToSalaryRatio`: Ratio between a customer’s balance and estimated salary.
- `ProductUsage`: Interaction feature between number of products and active membership status.
- `TenureGroup`: Grouped tenure into custom ranges.

## 🛠️ Tools and Libraries

- Python 3.x
- Pandas
- Jupyter Notebook
- Scikit-learn (for modeling)

## 📈 Objective

The main objective is to:
- Perform exploratory data analysis
- Engineer relevant features
- Build and evaluate a churn prediction model
- Provide business insights based on model findings

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/churn-prediction-model.git
