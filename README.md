# Credit Risk Analysis

A comprehensive exploratory data analysis (EDA) and machine learning project for predicting loan default risk using the Lending Club loan dataset.

---

## Project Overview

Credit risk assessment plays an important role in the financial industry by helping lenders identify borrowers who are likely to repay their loans and those who may default.

In this project, we perform:

- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Loan portfolio analysis
- Visualization of borrower characteristics
- Machine learning models for loan default prediction

The objective is to classify loans into **Good Loans** and **Bad Loans** using borrower information and loan characteristics available at the time the loan is issued.

---

## Dataset

The project uses the publicly available **Lending Club Loan Dataset**.

The dataset contains information such as

- Loan amount
- Interest rate
- Employment length
- Annual income
- Debt-to-income ratio
- Home ownership
- Credit grade
- Loan purpose
- Revolving credit utilization
- Public records
- Delinquencies
- Loan status

---

## Exploratory Data Analysis

The notebook includes detailed analyses of:

### Loan Portfolio

- Distribution of loan types
- Active vs. inactive loans
- Good vs. bad loans
- Loan status distribution

### Borrower Characteristics

- Credit grades
- Employment length
- Home ownership
- Annual income
- Debt-to-income ratio
- Interest rates

### Loan Characteristics

- Loan amount
- Loan purpose
- Loan term
- Installment amount

### Geographic Analysis

- Loan distribution by state
- Default distribution by state

### Time Analysis

- Loan issuance trends
- Total loan amount by issue year
- Evolution of default loans

Numerous visualizations are created using

- Matplotlib
- Seaborn

---

## Machine Learning

The project builds binary classification models to predict whether a loan is likely to become

- **Good Loan**
- **Bad Loan**

### Workflow

1. Data cleaning
2. Feature selection
3. Missing value handling
4. Categorical variable encoding
5. Train-test split
6. Model training
7. Performance evaluation
8. Feature importance analysis

### Models

- Logistic Regression
- Decision Tree
- Random Forest
- Neural Network (MLP)

Additional models such as **XGBoost**, **LightGBM**, and **CatBoost** can also be incorporated for comparison.

---

## Evaluation Metrics

The models are evaluated using

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Repository Structure

```
Credit_Risk_Analysis/
│
├── Data/
│
├── Project_report.ipynb
│
└── README.md
```

---

## Results

The exploratory analysis demonstrates several important relationships between borrower characteristics and loan performance, including the effects of

- Credit grade
- Interest rate
- Debt-to-income ratio
- Loan purpose
- Employment length

The machine learning models provide an effective framework for predicting loan default risk using information available at loan origination.

---

## Future Work

Possible extensions include

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Feature selection
- SHAP value interpretation
- XGBoost and LightGBM comparison
- Model deployment using Streamlit or Flask

---

## Author

**Naufil Sakran**

Ph.D. in Mathematics  
Tulane University

GitHub: https://github.com/naufilsakran