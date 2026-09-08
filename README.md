# 🛒 E-Commerce Customer Churn Prediction & Retention Engine

## 📊 Business Executive Summary
Customer churn is one of the biggest profit killers in e-commerce. This project delivers an end-to-end Machine Learning pipeline designed to predict whether a customer is likely to leave the platform. Beyond just identifying churners, this model optimizes marketing spend by ensuring retention discounts are targeted exclusively at high-risk customers, protecting profit margins.

## 🚀 Key Results & Business Impact
- **Model Used:** Optimized Random Forest Classifier (with Balanced Class Weights).
- **Prediction Accuracy:** 97.60%
- **Churn Precision (99%):** Virtually eliminates wasted marketing budget by ensuring zero false coupons sent to loyal customers.
- **Churn Recall (86%):** Successfully catches and saves the vast majority of escaping customers before they leave.

## 🔍 Key Churn Drivers (Feature Importance)
Through advanced feature analysis, the model revealed that churn is primarily driven by:
1. **Tenure:** Brand-new customers are the highest risk group and require targeted onboarding campaigns.
2. **Cashback Amount:** Customers with lower cashback tiers exhibit higher drop-off rates.
3. **Complaints:** Unresolved customer support issues heavily trigger customer defection.

## 🛠️ Tech Stack & Methodology
- **Languages & Libraries:** Python, Pandas, Scikit-Learn, Matplotlib
- **Preprocessing:** Median Imputation, One-Hot Encoding, StandardScaler (rigorously applied to prevent data leakage).
- **Inference Pipeline:** Built-in production-ready scoring script for incoming batch data (`client_churn_predictions_report.csv`).
