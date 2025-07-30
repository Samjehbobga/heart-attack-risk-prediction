Heart Attack Risk Prediction Using Logistic Regression

##  Project Overview

This project explores the use of logistic regression to predict the likelihood of heart attacks based on various clinical and demographic features. The dataset, though synthetic, is modeled after real-world health records and includes common cardiovascular indicators such as age, cholesterol, blood pressure, and fasting blood sugar.

The model achieved **90% accuracy**, and the results aligned with findings from major medical studies such as **Framingham**, **INTERHEART**, and publications in the **European Heart Journal**.

---

##  Objectives

- Identify key risk factors contributing to heart attacks
- Build a predictive model using logistic regression
- Evaluate model performance using real-world metrics
- Compare results with published health research

---

##  Dataset Summary

The dataset includes the following features:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Fasting blood sugar
- Resting ECG results
- Max heart rate
- Exercise-induced angina
- ST depression & slope
- Number of major vessels
- Thalassemia result
- **Target variable**: Heart attack risk (1 = high, 0 = low)

---

## Tools & Technologies

- **Python**
- `pandas`, `seaborn`, `matplotlib`
- `scikit-learn`
- Jupyter Notebook

---

## Methodology

1. **Exploratory Data Analysis (EDA)**  
   Visualized distributions, correlations, and relationships between key features.

2. **Feature Engineering**  
   Removed redundant or weak predictors (e.g., Thalachh and ca).

3. **Model Development**  
   - Trained a logistic regression model
   - Split data into training and testing sets
   - Optimized hyperparameters

4. **Evaluation**  
   - Confusion Matrix  
   - Precision, Recall, F1-score  
   - Accuracy: **90%**

---

## Results

| Metric         | Score |
|----------------|-------|
| Accuracy       | 90%   |
| Precision      | 0.90  |
| Recall         | 0.93  |
| F1-Score       | 0.91  |

The model showed a strong ability to identify patients at high risk of heart attacks. Feature importance and correlation analysis revealed that **cholesterol**, **age**, and **chest pain type** were among the most significant predictors.

---

## References

- Framingham Heart Study  
- INTERHEART Study  
- European Heart Journal Articles on Cardiovascular Risk

---

## Author

UK-based NHS nurse turned data scientist with a passion for solving healthcare problems using data.

For collaborations contact me on samjehbobga@yahoo.com

---

## What I Learned

- How to apply logistic regression in a real-world healthcare context  
- The importance of clean, interpretable data in clinical prediction  
- That health data can tell powerful stories when handled with care

---

