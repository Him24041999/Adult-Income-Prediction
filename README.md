# Census Income Prediction

## Overview

The **Census Income Prediction** project aims to predict whether individuals earn more than $50,000 annually based on census data and to uncover patterns related to economic inequality. This project involves the use of various machine learning algorithms to analyze socio-economic factors and identify key predictors of income.

## Problem Setting

Our goal was twofold:
1. **Predict Income:** Develop a model to classify whether individuals earn more than $50,000 annually.
2. **Address Inequality:** Identify and rectify unfair financial patterns to promote a more equitable distribution of economic opportunities.

## Data

The dataset used is the **Adult Census Income** dataset from the 1994 Census Bureau. It includes the following features:
- `Age`: Age of the individual
- `Work Class`: Employment status
- `Final Weight (fnlwgt)`: Estimated number of people the census entry represents
- `Education`: Highest level of education achieved
- `Education Number`: Numerical representation of education level
- `Marital Status`: Marital status of the individual
- `Occupation`: Type of occupation
- `Relationship`: Relative status to others
- `Race`: Race of the individual
- `Sex`: Biological sex
- `Capital Gain`: Capital gains
- `Capital Loss`: Capital losses
- `Hours Per Week`: Hours worked per week
- `Native Country`: Country of origin
- `Label`: Income level (`<=50k` or `>50k`)

## Data Visualization

Key visualizations include:
- **Age Distribution:** Most individuals are between 20 and 40 years old.
- **Education vs. Income:** Higher education levels correlate with higher income.
- **Gender Distribution:** Dataset is male-dominated.
- **Marital Status Distribution:** Most individuals are married.

## Data Cleaning

- **Handling Missing Values:** Removed rows with missing values (7.38% of the data) to maintain dataset integrity.
- **Outlier Detection:** Used the Interquartile Range (IQR) method to handle outliers.

## Model Exploration

We explored the following classification algorithms:
1. **Logistic Regression**
2. **Support Vector Classifier (SVC)**
3. **Naïve Bayes Classifier**
4. **Decision Tree Classifier**
5. **Random Forest Classifier**
6. **Gradient Boosting Machines (GBM)**

## Model Results

Performance metrics for key models:
- **Logistic Regression:** Accuracy of 75.25%
- **Support Vector Classifier:** Accuracy of 81.58%
- **Naïve Bayes Classifier:** Accuracy of 64.68%
- **Decision Tree Classifier:** Accuracy of 91.42%
- **Random Forest Classifier:** Accuracy of 92.58%, improved to 92.68% with hyperparameter tuning

  ![Performace Model](https://github.com/user-attachments/assets/885e43d9-44b7-4138-85af-7646f566a0a8)


## Hyperparameter Tuning

- **Random Forest Classifier** achieved optimal performance with hyperparameters: `n_estimators: 50`, `max_depth: 80`.
- **Accuracy:** 92.68%
- **F1 Score:** 93.01%

## Performance Summary

The Decision Tree and Random Forest classifiers demonstrated exceptional performance in predicting income and addressing fairness.

## Future Work

- **Feature Engineering:** Create new features to enhance model performance.
- **Ensemble Methods:** Experiment with stacking or boosting techniques.
- **Deep Learning:** Investigate neural networks for complex data patterns.
- **Fairness and Bias Analysis:** Ensure models are equitable across different demographic groups.
- **Temporal and External Data Integration:** Enrich analysis with additional datasets.

## Conclusion

This project provided valuable insights into income prediction and the identification of financial inequalities. The methodologies employed and results achieved offer a foundation for future work aimed at promoting economic fairness.



