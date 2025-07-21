# customer-churn-prediction
This project analyzes telecom customer data to predict churn using machine learning. The goal is to help businesses understand the factors that lead to customer churn and take preventive actions.

The Objectives were to;
- Predict whether a customer will leave the company.
- Identify key drivers of churn (e.g., contract type, tenure, service usage).
- Build an accurate classification model using Random Forest.

Dataset
- Source: Telco Customer Churn Dataset (from IBM Sample Data)
- Rows: 7,043 customers
- Features: 21 (e.g., tenure, service type, payment method)

Tools Used
- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

Key Steps I took
1. Data cleaning and handling missing values
2. Exploratory data analysis (EDA)
3. Categorical encoding and feature engineering
4. Model training (Random Forest Classifier)
5. Evaluation using confusion matrix, classification report, and feature importance

Results
- Accuracy: 79%
- Precision (Churn): 62%
- Key Predictors: Contract type, tenure, MonthlyCharges

Insights
- Month-to-month contracts are strongly linked to higher churn.
- Short-tenure customers are more likely to leave.
- Higher charges without bundled services correlate with churn.

Project Structure
- `Customer_Churn_Analysis.ipynb`: Main notebook
- `WA_Fn-UseC_-Telco-Customer-Churn.csv`: Dataset


