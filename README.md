# Telecom Company Churn Prediction

## Project Overview

This project aims to predict customer churn for a telecom company by developing and optimizing machine learning models. Using a dataset from an Iranian telecom company's database, the project employs seven machine learning techniques to predict customer churn status, identify key factors influencing customer churn, and provide actionable insights for improving customer retention strategies.

## Dataset Description
The dataset was randomly collected from an Iranian telecom company's [database](https://doi.org/10.24432/C5JW3Z) over a period of 12 months, containing information on 3,150 customers with 13 features representing customer behavior and characteristics. The target variable is `Churn`, indicating whether the customer left the company by the end of the 12 months.


## Project Structure
```
├── data/
│   └── customer_churn.csv            # Dataset
├── churning_project_final.ipynb      # Jupyter notebook with the analysis
├── xgbmodel.bst                      # Optimized XGBoost model
└── README.md                     
```

## Key Findings

We tested and compared seven models (Logistic Regression, Decision Trees, Random Forest, SVM, Gradient Boosting, XGBoost, and Neural Networks) to predict the binary churn labels after preprocessing and splitting the data.

- XGBoost was identified as the best-performing model. The model was further optimized using GridSearchCV, achieving an AUC-ROC score of 0.993 on the test set.
- Feature Importance: SHAP analysis was used to interpret the model, revealing key factors influencing customer churn:
    - Frequent Call Usage.
    - Proactive Issue Resolution.
    - Service Quality.

## Conclusion

This project successfully developed a robust predictive model for customer churn, and provided valuable insights for business decision-making. A combination of model performance optimization and interpretability helps ensure that our model predictions are both accurate and actionable.

## Contact
If you have any questions or feedback, feel free to reach out!
