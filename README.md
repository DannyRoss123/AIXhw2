# AIXhw2

# Telco Customer Churn Analysis Project

## Overview
Analysis of customer churn prediction using multiple machine learning approaches. Built for telecommunications company seeking to understand and predict customer departures.

## Dataset
- Source: Kaggle Telco Customer Churn dataset
- Features: Customer demographics, service usage, billing information
- Target: Binary churn indicator (Yes/No)

## Implementation Details
### Data Preprocessing
- Categorical encoding (one-hot)
- Handling missing values
- Feature scaling
- Train-test split (80/20)

### Models
1. Linear Regression
   - Treating churn as continuous
   - R² = 0.25, MSE = 0.15
   - Key features: Internet service, streaming options

2. Logistic Regression
   - Binary classification approach
   - Accuracy: 79%
   - Strong predictors: tenure, monthly charges
   - Best performing model

3. GAM
   - Non-linear relationship capture
   - Accuracy: 79%
   - Used for complex pattern detection

## Running Instructions
1. Open `Telco_Churn_Analysis.ipynb` in Google Colab
2. Install dependencies:
```python
!pip install pygam scikit-learn seaborn
```
3. Upload dataset when prompted
4. Run cells sequentially

## Key Findings
- Customer tenure strongly influences churn
- Month-to-month contracts show higher churn risk
- Fiber optic service correlates with churn
- Price sensitivity evident in monthly charges impact

## Business Recommendations
Based on logistic regression results:
- Focus on early customer retention
- Review pricing strategies
- Consider contract incentives
- Monitor service quality, especially fiber optic


## Repository Structure
- `Telco_Churn_Analysis.ipynb`: Main analysis notebook
- `README.md`: Project documentation

