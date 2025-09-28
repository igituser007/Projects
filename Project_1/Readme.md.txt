# 📊 Customer Churn Prediction using Machine Learning

## 🧠 Objective

The objective of this project is to predict customer churn using supervised classification models.  
We aim to identify customers who are likely to leave a telecom service, allowing the business to implement retention strategies.

---

## 🔍 Steps Followed

1. **Data Cleaning & Preprocessing**
   - Removed missing/blank values
   - Converted categorical variables using One-Hot Encoding
   - Scaled numerical features using StandardScaler

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution and feature correlations
   - Analyzed categorical features (e.g., Contract type vs. Churn)
   - Identified patterns in tenure, charges, and service types

3. **Model Building**
   - Used `train_test_split` to create train/test sets
   - Trained three models:
     - Logistic Regression
     - Random Forest
     - XGBoost

4. **Model Evaluation**
   - Compared Accuracy, ROC-AUC, and Classification Reports
   - Plotted:
     - ROC curves
     - Confusion matrices
     - Feature importance (Random Forest)
     - Model comparison chart

---

## 🏆 Final Model Performance

### ✅ Best Model: **XGBoost**
- **Accuracy**: 82.4%
- **ROC-AUC**: 0.88
- **Recall (Churn Class)**: 0.78

XGBoost performed best overall — especially in minimizing **false negatives**, which is crucial for identifying customers likely to churn.

---

## 📁 Files

- `churn_prediction.ipynb`: Full notebook with code, visuals, and insights
- `README.md`: This summary file
- `telco_churn.csv`: Dataset used (from Kaggle)

---

## 💡 Future Improvements

- Hyperparameter tuning (GridSearchCV)
- SMOTE for class imbalance
- Streamlit dashboard for deployment
