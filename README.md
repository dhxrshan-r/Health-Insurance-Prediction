# Health Insurance Prediction using Machine Learning

This project uses Machine Learning techniques to predict health insurance charges based on an individual's personal and health-related information. The model is trained using a health insurance dataset and demonstrates the complete Machine Learning workflow, from data preprocessing to prediction.

---

## Project Overview

Health insurance companies determine premium charges using several factors such as age, BMI, smoking habits, and other demographic information. This project aims to build a predictive model that estimates insurance charges accurately using Linear Regression.

---

## Dataset

The dataset used in this project is:

- `insurance_prediction.csv`

### Features

| Column Name | Description |
|------------|-------------|
| age | Age of the customer |
| sex | Gender of the customer |
| bmi | Body Mass Index |
| children | Number of dependent children |
| smoker | Smoking status (Yes/No) |
| region | Residential region |
| charges | Insurance charges (Target Variable) |

---

## Technologies Used

- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Workflow

The project follows the following steps:

1. Data Collection
2. Data Loading
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Data Preprocessing
6. Feature Encoding
7. Feature Scaling
8. Train-Test Split
9. Model Training
10. Model Evaluation
11. Prediction of Insurance Charges

---

## Exploratory Data Analysis

The notebook includes:

- Statistical summary of the dataset.
- Distribution plots for numerical features.
- Correlation analysis.
- Visualization of categorical features.
- Relationship between features and insurance charges.

Key insights include:

- Smoking significantly increases insurance charges.
- Insurance charges tend to increase with age.
- BMI has an impact on insurance costs.
- Combining multiple features improves prediction accuracy.

---

## Data Preprocessing

The following preprocessing techniques are applied:

### Encoding

Categorical variables are converted into numerical values using:

- One-Hot Encoding

### Feature Scaling

Numerical features are standardized using:

- StandardScaler

### Dataset Split

- Training Data – 80%
- Testing Data – 20%

---

## Model Used

The project uses:

- Multiple Linear Regression

Several models are trained using different combinations of features to compare their performance.

---

## Evaluation Metrics

The model is evaluated using:

- Mean Squared Error (MSE)
- R² Score (Coefficient of Determination)

These metrics help determine the accuracy and reliability of the predictions.

---

## Project Structure

```
Health Insurance Prediction/
│
├── Health_Insurance_Prediction_ML.ipynb
├── insurance_prediction.csv
└── README.md
```

---

## How to Run the Project

1. Clone the repository:

```bash
git clone <your-repository-link>
```

2. Navigate to the project folder:

```bash
cd Health-Insurance-Prediction
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open the notebook:

```bash
jupyter notebook
```

5. Run all the cells in:

```text
Health_Insurance_Prediction_ML.ipynb
```

---

## Results

- Successfully predicts health insurance charges.
- Demonstrates the complete Machine Learning pipeline.
- Shows how different features influence insurance premiums.
- Highlights the importance of proper data preprocessing and feature selection.

---

## Future Enhancements

Some possible improvements include:

- Random Forest Regressor
- XGBoost Regressor
- Gradient Boosting
- Hyperparameter Tuning
- Streamlit Web Application Deployment

---

## Author

**Dharshan R**
---

## Repository Contents

| File Name | Description |
|----------|------------|
| Health_Insurance_Prediction_ML.ipynb | Complete Machine Learning notebook |
| insurance_prediction.csv | Dataset used for training and testing |
| README.md | Project documentation |
