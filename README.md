# Datathon_DA
Problem Statement:
Stroke is one of the leading causes of death and long-term disability worldwide. Early detection and prevention can save lives. The goal of this project is to analyze healthcare data to identify key factors influencing stroke occurrence and to build a predictive model that can estimate the likelihood of a stroke based on patient information.


Objective:

To explore the relationship between patient lifestyle, medical history, and stroke occurrence.

To preprocess, visualize, and analyze healthcare data effectively.

To develop and evaluate machine learning models for stroke prediction.

To create a data-driven dashboard/report summarizing findings and model results.


 Data Preprocessing:
 Removed the 'id' column.
  Filled missing 'bmi' values with the mean value (≈ 28.9).
  Encoded categorical columns using Label Encoding: gender, ever_married, work_type, Residence_type, smoking_status.
  Final dataset contained 5110 rows × 11 columns with no missing values.

Exploratory Data Analysis (EDA):
  Stroke occurrence increases significantly after age 55.
  Higher glucose levels are associated with greater stroke risk.
  BMI shows a weak but positive relationship with stroke likelihood.
  Hypertension and heart disease are key contributing factors.



Expected Outcome:

A predictive model that accurately classifies whether a person is at risk of stroke.

Insightful visualizations showing how factors like age, BMI, glucose, and lifestyle contribute to stroke risk.

A final report and dashboard summarizing results.


