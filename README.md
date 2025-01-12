# Diabetes Prediction with Machine Learning

This repository demonstrates diabetes prediction using machine learning models on the **Pima Indians Diabetes Dataset**.

---

## Workflow
1. **Data Preparation**:
   - Cleaned and imputed missing values.
   - Balanced classes using **SMOTE**.
   - Scaled features with `StandardScaler`.
2. **Model Training**:
   - Models: Logistic Regression, Random Forest, XGBoost.
   - Performance evaluated using accuracy, ROC-AUC, and classification reports.
3. **Hyperparameter Tuning**:
   - Optimized XGBoost with Grid Search.
4. **Model Saving**:
   - Best model saved as `diabetes_prediction_model.pkl`.

---

## Requirements
Install dependencies with:
```bash
pip install -r requirements.txt
