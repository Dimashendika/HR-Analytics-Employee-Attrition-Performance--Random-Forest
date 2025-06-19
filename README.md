# HR Analytics: Employee Attrition & Performance

This project analyzes the **IBM HR Analytics Employee Attrition dataset** to identify key factors contributing to attrition and employee performance. The goal is to help HR departments reduce turnover and improve workforce management using data-driven insights.

##  Dataset
- Source: [IBM HR Analytics Dataset on Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Format: CSV
- Size: 1,470 employee records with 35 features

##  Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Random Forest)

##  Objective
- Understand which features most influence employee attrition
- Predict high-risk employees using classification models
- Provide actionable recommendations to HR teams

##  Methodology
1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Label Encoding & Standardization
4. Random Forest Classification
5. Model Evaluation & Feature Importance

##  Key Insights & Recommendations

1. **Younger Employees Leave More Often**  
   - Employees with 0–7 years of experience have higher attrition rates.  
    *Recommendation*: Create mentorship programs to retain young talent.

2. **Income Correlates with Retention**  
   - `MonthlyIncome` is a top predictor, tied to `JobLevel` and experience.  
    *Recommendation*: Ensure fair pay growth for junior roles.

3. **Single Employees Are More Likely to Leave**  
    *Recommendation*: Foster a stronger sense of belonging through communities and support groups.

4. **Long Commutes Increase Attrition**  
    *Recommendation*: Offer hybrid work or commute support for distant employees.

5. **Job Role & Engagement Matter**  
   - Sales Reps are high-risk; low job involvement and satisfaction fuel attrition.  
    *Recommendation*: Promote internal mobility and regular engagement checks.

6. **Managerial Relationships Influence Retention**  
   - Employees with short tenure under managers tend to leave more.  
    *Recommendation*: Improve manager training and communication.

7. **Gender Pay Equity Observed**  
   - No strong bias; continue monitoring for fairness.

##  Feature Importance (Random Forest)
Top features predicting attrition:
- `MonthlyIncome`
- `DailyRate`
- `Age`
- `DistanceFromHome`
- `OverTime`
