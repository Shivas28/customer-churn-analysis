# Customer Churn Prediction & Purchase Analysis

## Project Overview
End-to-end Data Science project analyzing customer behavior 
to predict churn and purchase value using Machine Learning.

## Problem Statement
- Can we predict which customers will leave? (Logistic Regression)
- Can we predict how much a customer will spend? (Linear Regression)

## Steps Performed
1. Data Cleaning → handled nulls, fixed inconsistent casing
2. Encoding → Label Encoding, One Hot Encoding
3. Standardization → StandardScaler
4. Logistic Regression → predict Churn (Accuracy: 100%)
5. Linear Regression → predict Purchase Value (R²: 0.99)
6. Visualization → Countplot, Boxplot, Heatmap, Scatterplot

## Libraries Used
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

## Results
| Model | Target | Score |
|---|---|---|
| Logistic Regression | Churned | 100% accuracy |
| Linear Regression | Purchase Value | 99.2% R² |

## Key Insights
- Low satisfaction score is strongest churn indicator
- Higher income customers spend significantly more
- New customers churn more easily
