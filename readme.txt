# Telco Customer Churn Prediction 📊

## Overview
This project predicts **customer churn** for a telecom company using machine learning.  
Churn prediction helps companies identify customers likely to leave and take action to retain them.

## Dataset
- Source: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- Size: ~7,000 customer records  
- Target: `Churn Value` (0 = No churn, 1 = Churn)

## Steps
1. **Exploratory Data Analysis (EDA)**  
   - Checked churn distribution  
   - Visualized key features (contract type, tenure, monthly charges)

2. **Data Preprocessing**  
   - Handled categorical variables with one-hot encoding  
   - Removed irrelevant columns (CustomerID, Churn Label, Churn Reason)  
   - Target column (`Churn Value`) used for modeling

3. **Modeling**  
   - Logistic Regression  
   - Random Forest Classifier  
   - Compared models using accuracy, precision, recall, F1-score  

4. **Results**  
   - Logistic Regression Accuracy: ~91%  
   - Random Forest Accuracy: ~94%  
   - Random Forest performed better in recall (catching more churners)

## Business Impact
By predicting churn, the telecom company can:  
- Target high-risk customers with offers or discounts  
- Improve retention strategies  
- Reduce revenue loss

## Tech Stack
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- Jupyter Notebook  

## Next Steps
- Deploy model as an API (Flask/FastAPI)  
- Try advanced models (XGBoost, Neural Networks)  
- Build a dashboard for predictions (Streamlit)
