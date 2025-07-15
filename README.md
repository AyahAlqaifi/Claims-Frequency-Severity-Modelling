# Claims Frequency & Severity Modelling

This project demonstrates an end-to-end workflow for modelling insurance claim frequency (classification) and claim severity (regression) on a synthetic UK car insurance dataset.

## 📄 Overview

The project covers:

- **Synthetic Data Generation**: Creating realistic policyholder, vehicle, and claim data.
- **Data Preparation & EDA**: Handling missing values, visualising distributions, exploring correlations.
- **Class Imbalance Handling**: Using SMOTE to balance claim occurrence.
- **Claim Frequency Modelling**: Predicting whether a claim will occur.
- **Claim Severity Modelling**: Predicting the claim amount.
- **Model Evaluation**: ROC curves, regression metrics, feature importances.
- **Interpretation**: Insights on variable importance and modelling limitations.

## ⚙️ Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib, Seaborn

## 🧠 Key Insights

- Vehicle characteristics, coverage type, and credit score can influence claim likelihood.
- Claim amounts are driven by vehicle value, incident type, and fault status.
- Random Forest models generally outperform linear models in this context.
- Synthetic data requires careful design to ensure meaningful predictive relationships.
