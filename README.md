# Heart Failure Prediction Project

## Overview
This project focuses on predicting heart failure using various machine learning algorithms. The goal is to leverage clinical and demographic features to achieve the highest prediction accuracy possible.

![hfp](https://github.com/Kalamatha-Eshwari/Heart-Failure-Prediction/assets/139895843/0af18f86-4e7d-4637-bb65-1ccbecf25455)

## Steps

### 1. Exploratory Data Analysis (EDA)
- **Duplicates and Null Values**:
  - Checked for and handled duplicates. No null values were found in the dataset.

- **Feature Classification**:
  - Features were categorized into:
    - Continuous: creatinine_phosphokinase, ejection_fraction, serum_sodium, time
    - Discrete: anaemia, diabetes, high_blood_pressure, sex, smoking

### 2. Data Visualization
- **Univariate Analysis**:
  - Continuous Features: Histogram, distribution plot, box plot.
  - Discrete Features: Count plot, pie plot.

- **Bivariate Analysis**:
  - Continuous-Continuous: Scatter plots between each pair of features.
  - Discrete-Target: Count and bar plots between features and the target variable (heart failure).

### 3. Feature Engineering and Selection
- **Collinearity Check**:
  - Evaluated the correlation matrix among continuous features. No significant collinearity (>60%) was observed.

- **Feature Importance**:
  - Utilized pivot tables and cross-tabulations for easy feature analysis.

### 4. Data Preprocessing
- **Handling Imbalance**:
  - Addressed class imbalance using Synthetic Minority Over-sampling Technique (SMOTE).

- **Scaling**:
  - Applied feature scaling to improve the performance of models sensitive to feature magnitude differences.

### 5. Model Building and Evaluation
- **Algorithms Tested**:
  - Logistic Regression (accuracy: 73%)
  - Random Forest (accuracy: 96%)
  - Decision Tree (accuracy: 93%)
  - SVM with linear kernel (accuracy: 70%)

- **Model Comparison**:
  - Visualized comparative accuracy using a bar plot.
  - Identified Random Forest as the good performing model for heart failure prediction.

### 6. Conclusion
- Based on the evaluation, Random Forest emerged as the  accurate model for predicting heart failure. This project underscores the critical role of comprehensive data analysis and robust model selection in healthcare analytics.

