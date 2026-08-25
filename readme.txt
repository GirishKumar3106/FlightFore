# FlightFore ✈️

## Travel & Aviation Prediction System

FlightFore is a machine learning project that predicts:

1. Flight departure-delay minutes using regression.
2. Flight cancellation risk using classification.
3. Route reliability patterns using clustering.

The project combines flight schedule, airport and weather information to provide early disruption warnings.

---

## Project Objectives

- Predict departure-delay minutes.
- Predict cancellation probability.
- Identify reliable and unreliable flight routes.
- Build a deployable prediction API.
- Monitor model and data drift.

---

## Dataset

The project uses a US flight and weather dataset containing data from 30 airports over 2021–2023.

The raw dataset is not included in this repository because of its large size.

---

## Current Progress

### Week 1 — Exploratory Data Analysis
- Dataset exploration
- Target definition
- Missing-value analysis
- Delay distribution analysis
- Cancellation analysis
- Weather analysis
- Time-based analysis

### Week 2 — Data Preparation
- Combined 30 airport datasets
- Removed exact duplicate records
- Validated missing values
- Created time features
- Defined leakage-safe prediction features
- Created temporal train/validation/test split
- Built preprocessing pipeline

### Upcoming

- Week 3: OLS and Gradient Descent regression
- Week 4: Ridge, Lasso and Logistic Regression
- Week 5: Cross-validation and baseline evaluation
- Week 6: Decision Tree
- Week 7: Random Forest
- Week 8: XGBoost + SHAP
- Week 9: Route clustering
- Week 10: Rigorous evaluation
- Week 11: Model packaging and drift detection
- Week 12: FastAPI deployment