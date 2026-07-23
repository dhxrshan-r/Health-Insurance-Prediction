# Health Insurance Premium Prediction using Machine Learning

## Overview

This project predicts health insurance premium charges based on an individual's demographic and health-related information using Machine Learning. The model helps estimate insurance costs by analyzing factors such as age, BMI, smoking status, gender, number of children, and region.

The project includes:

- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering and encoding
- Multiple Linear Regression models
- Model evaluation and comparison
- Premium charge prediction for new customers

---

## Problem Statement

Health insurance premiums vary based on several personal and lifestyle factors. The objective of this project is to build a predictive model that estimates medical insurance charges accurately.

The model uses customer information such as:

- Age
- Gender
- BMI (Body Mass Index)
- Number of Children
- Smoking Status
- Region

to predict the corresponding insurance charges.

---

## Dataset Information

The dataset contains the following features:

| Feature | Description |
|--------|--------|
| Age | Age of the customer |
| Sex | Male or Female |
| BMI | Body Mass Index |
| Children | Number of dependents covered by insurance |
| Smoker | Smoking status |
| Region | Residential region |
| Charges | Insurance premium charges (Target Variable) |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## Project Workflow

```
Dataset
   ↓
Data Cleaning & Exploration
   ↓
Exploratory Data Analysis
   ↓
Data Preprocessing
   ↓
Feature Encoding
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
Linear Regression Modeling
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Prediction on New Data
```

---

## Exploratory Data Analysis

The notebook performs:

- Distribution analysis of numerical features.
- Pie chart visualization for categorical features.
- Correlation analysis.
- Box plots for insurance charges.
- Scatter plots for understanding relationships between variables.

### Key Observations

- Smokers have significantly higher insurance charges.
- Age has a positive relationship with insurance premiums.
- BMI moderately affects insurance charges.
- Regional differences exist but are less significant.
- Using all available features improves prediction accuracy considerably.

---

## Data Preprocessing

The following preprocessing techniques were applied:

### Categorical Encoding

- One Hot Encoding

Features encoded:
- Sex
- Smoker
- Region

### Feature Scaling

- StandardScaler

Scaled numerical features:
- Age
- BMI
- Children

### Data Split

- Training Data: 80%
- Testing Data: 20%

---

## Machine Learning Models

Three Linear Regression models were built and compared.

| Model | Features Used |
|------|------|
| Model 1 | Age |
| Model 2 | Age + BMI |
| Model 3 | All Features |

---

## Model Evaluation Metrics

The following metrics were used:

- Mean Squared Error (MSE)
- R-Squared Score (R²)

### Why These Metrics?

- Lower MSE indicates fewer prediction errors.
- Higher R² indicates better model performance.

Special attention is given to reducing underestimation of insurance premiums, which can impact insurance pricing strategies.

---

## Model Comparison

| Model | Performance |
|------|------|
| Model 1 | Poor performance |
| Model 2 | Slight improvement |
| Model 3 | Best performance |

### Final Selected Model

**Model 3 (All Features)** was selected because it provides:

- Highest R² score
- Lowest prediction error
- Better generalization on unseen data

---

## Results

- Age alone is insufficient for accurate premium prediction.
- Adding BMI improves performance slightly.
- Including all customer attributes significantly improves prediction accuracy.
- Smoking status is one of the most influential factors affecting insurance costs.

---

## Conclusion

This project successfully builds a Health Insurance Premium Prediction model using Multiple Linear Regression.

The model demonstrates that:

- Insurance premiums are influenced by multiple factors.
- Proper data preprocessing significantly improves model performance.
- Linear Regression performs effectively when all relevant features are included.
- Machine Learning can assist insurance providers in estimating premiums more accurately.

---

## Repository Structure

```
Health-Insurance-Prediction/

│
├── Health_Insurance_Prediction_ML.ipynb
├── README.md
└── Dataset (insurance_prediction.csv)
```

---

## Future Improvements

- Implement advanced regression models:
  - Random Forest Regressor
  - XGBoost Regressor
  - Gradient Boosting
  - Support Vector Regression

- Perform hyperparameter tuning.
- Deploy the model using Streamlit or Flask.
- Build an interactive web application for premium prediction.

---

## Author

**Dharshan R**

Final Year Electronics and Communication Engineering Student
