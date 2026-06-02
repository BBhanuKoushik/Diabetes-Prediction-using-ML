# Diabetes Prediction Using Machine Learning

## Overview

This project predicts the likelihood of diabetes in patients using Machine Learning techniques. By analyzing medical attributes such as glucose level, blood pressure, BMI, insulin level, age, and pregnancy count, the model helps identify individuals at risk of diabetes, supporting early diagnosis and preventive healthcare.

## Objectives

* Analyze and understand diabetes-related health data.
* Perform data preprocessing and exploratory data analysis (EDA).
* Build a predictive machine learning model for diabetes classification.
* Evaluate model performance using standard classification metrics.

## Dataset

The dataset contains medical records of patients with features including:

* Pregnancies
* Glucose Level
* Blood Pressure
* Skin Thickness
* Insulin
* BMI (Body Mass Index)
* Diabetes Pedigree Function
* Age
* Outcome (Diabetic / Non-Diabetic)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Methodology

### 1. Data Preprocessing

* Loaded and inspected the dataset.
* Checked for missing values and inconsistencies.
* Prepared data for machine learning training.

### 2. Exploratory Data Analysis (EDA)

* Generated descriptive statistics.
* Visualized feature distributions.
* Created heatmaps and boxplots.
* Analyzed correlations between variables.

### 3. Model Development

* Split the dataset into training and testing sets.
* Implemented the K-Nearest Neighbors (KNN) classification algorithm.
* Trained the model on historical patient records.

### 4. Model Evaluation

Performance was measured using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

## Results

The KNN model achieved approximately **75% accuracy** in predicting diabetes, demonstrating the effectiveness of machine learning for healthcare risk assessment.

## Key Insights

* Glucose level showed a strong correlation with diabetes occurrence.
* Data visualization helped identify important trends and outliers.
* Machine learning can assist healthcare professionals in early disease detection.

## Future Improvements

* Compare multiple machine learning algorithms such as Random Forest, SVM, and XGBoost.
* Perform hyperparameter tuning to improve accuracy.
* Develop a web application for real-time diabetes prediction.
* Integrate larger and more diverse healthcare datasets.

## Conclusion

This project demonstrates how machine learning can be applied to healthcare data to predict diabetes risk effectively. The developed model provides a foundation for intelligent healthcare systems that support early diagnosis and data-driven medical decision-making.
