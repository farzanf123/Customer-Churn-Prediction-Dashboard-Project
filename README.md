# Customer Churn Prediction – Telco Dataset

This project analyzes customer behavior in the telecommunications industry to identify key factors contributing to churn. Using Python and machine learning, the goal was to predict customer churn and generate actionable insights to inform retention strategies.

---

## Project Objectives

- Analyze customer data to uncover trends and churn risk factors
- Build a machine learning model to classify churn likelihood
- Visualize important relationships to support business decisions

---

## Dataset Overview

- **Source**: [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Records**: 7,043 customer entries  
- **Features**: Demographics, contract details, billing information, and churn status

---

## Key Analysis Steps

### 1. Exploratory Data Analysis (EDA)
- Examined churn distribution and class imbalance
- Visualized churn by contract type, payment method, and tenure
- Found key associations between churn and:
  - Month-to-month contracts
  - Low customer tenure
  - Electronic check payments

### 2. Data Preprocessing
- Converted `TotalCharges` to numeric and handled missing values
- Applied one-hot encoding to categorical variables
- Removed non-predictive identifiers (e.g., `customerID`)

### 3. Model Development
- Split data into training and testing sets (80/20)
- Trained a Random Forest Classifier using scikit-learn
- Evaluated performance using accuracy score, classification report, and confusion matrix
- Plotted top 10 most important features driving churn

---

## Results Summary

- **Model Used**: Random Forest Classifier  
- **Evaluation Metric**: Accuracy and F1-score  
- **Achieved Accuracy**: ~78.8%

Top predictive features:
- Contract type  
- Tenure  
- Monthly charges  
- Payment method  
- Internet service type

---

## Technologies Used

- **Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Development Environment**: Jupyter Notebook (VS Code)

---

## Visual Examples

Include visual outputs such as:

- `images/tenure_churn.png`: Tenure distribution by churn
- `images/feature_importance.png`: Feature importance chart

---

## How to Run This Project

1. Clone this repository  
2. Open `churn_analysis.ipynb` using Jupyter Notebook or Google Colab  
3. Run all cells in order

---

## Author

**Farzan Feeha**  
Information Science Student – August 2025  
