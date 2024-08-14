# Loan Default Classification Machine Learning Project

## Problem Statement

LendingClub, a leading peer-to-peer lending platform, aims to minimise financial risk by identifying high-risk loan applicants who are likely to default on their loans. Given historical loan data, this project focuses on predicting whether a loan applicant will default based on their profile. Identifying these risky applicants helps in reducing credit losses by making informed lending decisions.

## Project Objectives

1. **Data Exploration**: Perform Exploratory Data Analysis (EDA) to understand the dataset, identify feature importance, and detect any patterns.
2. **Feature Engineering**: Create and select features that significantly impact loan default predictions.
3. **Model Building**: Develop and evaluate various machine learning models to classify borrowers as either likely to default or not.
4. **Hyperparameter Tuning**: Optimise model performance through hyperparameter tuning to achieve the best possible AUC score.
5. **Model Validation**: Validate the model using appropriate metrics to ensure it generalises well to new, unseen data.

## End Goals

- Achieve a **high AUC score** to ensure the model accurately identifies potential loan defaulters.
- Support LendingClub in reducing credit loss by identifying high-risk applicants.

## Assumptions

- **Data Quality**: The historical loan data provided is accurate and representative of the real-world loan application process.
- **Feature Relevance**: Features in the dataset are relevant and sufficient for predicting loan defaults.
- **Static Risk Factors**: Risk factors associated with loan defaults remain relatively stable over time. For instance, if features like annual income or debt-to-income ratio are known to be predictors of loan default, it is assumed that their predictive power remains consistent over time and across different loan periods. In reality, risk factors can evolve due to changes in the economy, borrower behavior, or lending practices.

## Tools and Technologies

- Python, Pandas, Plotly (Express, Go), Scikit-Learn, Catboost, XGBoost
