# 🏥 Healthcare Data Preprocessing and Feature Engineering Project

## 📌 Project Overview

This project demonstrates practical implementation of **Data Preprocessing** and **Feature Engineering** techniques on a healthcare patient dataset.

The main purpose of this project is to clean raw healthcare data by identifying missing values, applying different imputation methods, detecting outliers using statistical techniques, treating extreme values and preparing a final cleaned dataset for machine learning applications.

This project simulates real-world healthcare data analysis where data quality directly affects prediction performance.

---

# 🎯 Project Objective

The objectives of this project are:

* Identify missing values present in dataset
* Apply multiple missing value handling techniques
* Detect outliers using statistical methods
* Handle extreme values without losing important data
* Compare dataset quality before and after cleaning
* Create final machine learning ready dataset

---

# 📂 Dataset Description

The dataset contains **50 healthcare patient records**.

Each record contains patient medical information with intentionally inserted missing values and extreme values for preprocessing practice.

Dataset columns:

| Column Name    | Description               |
| -------------- | ------------------------- |
| patient_id     | Unique patient identifier |
| age            | Age of patient            |
| gender         | Male or Female            |
| region         | Patient region            |
| bmi            | Body Mass Index           |
| blood_pressure | Blood Pressure            |
| cholesterol    | Cholesterol level         |
| glucose        | Glucose level             |
| disease_risk   | Disease prediction target |

---

# PART A : Missing Value Handling

Different missing value handling techniques were applied to clean incomplete data.

---

## Question 1 : Import Required Libraries

Libraries used in project:

* Pandas
* NumPy
* Matplotlib
* Scikit Learn
* SciPy

---

## Question 2 : Load Dataset

Dataset loaded successfully using Pandas DataFrame.

Input file:

* patient_health_records.csv

---

## Question 3 : Display Dataset Information

Basic dataset analysis performed.

Checked:

* Dataset shape
* Column names
* Data types

Dataset size:

* 50 Rows
* 9 Columns

---

## Question 4 : Identify Missing Values

Missing values intentionally inserted in following columns:

* Age
* Gender
* Region
* BMI
* Cholesterol
* Glucose

---

## Question 5 : Calculate Missing Value Percentage

Calculated percentage of missing values in each column to understand dataset quality before preprocessing.

---

## Question 6 : Mean Imputation

Applied Mean Imputation on:

* BMI Column

Missing BMI values replaced using average BMI value.

---

## Question 7 : Most Frequent Imputation

Applied Most Frequent Imputation on:

* Region Column

Missing values replaced using most common category.

---

## Question 8 : Gender Imputation

Applied Most Frequent Imputation on:

* Gender Column

Missing gender values replaced using mode value.

---

## Question 9 : Missing Indicator Method

Created binary indicator column for identifying missing values.

Applied on:

* Age Column

---

## Question 10 : Random Sample Imputation

Missing age values replaced using randomly selected existing values.

---

## Question 11 : KNN Imputer

Applied K-Nearest Neighbor Imputation for multivariate missing value estimation.

Columns used:

* Age
* BMI
* Cholesterol
* Glucose

---

## Question 12 : MICE Algorithm

Applied Multiple Imputation by Chained Equations.

This method produces statistically better missing value estimations.

---

## Question 13 : Missing Values Visualization

Bar graph created to visualize missing values before cleaning process.

<img width="567" height="595" alt="image" src="https://github.com/user-attachments/assets/b832b670-b199-495f-889f-837393bf2aec" />


# PART B : Outlier Detection and Handling

Different statistical methods used for outlier detection.

---

## Question 14 : Z Score Method

Applied Z Score statistical method for detecting extreme outliers.

Used for:

* Cholesterol Column

---

## Question 15 : IQR Method

Applied Interquartile Range method for detecting abnormal BMI values.

Used for:

* BMI Column

---

## Question 16 : Percentile Method

Applied percentile capping technique.

Used for:

* Glucose Column

---

## Question 17 : Winsorization

Applied Winsorization technique to cap extreme cholesterol values without removing records.

---

## Question 18 : Cholesterol Outlier Visualization

Created boxplot for cholesterol outlier detection.

<img width="551" height="435" alt="image" src="https://github.com/user-attachments/assets/76e3c44b-bef6-4cf2-874e-a206e1f44035" />


---

# PART C : Final Dataset Creation

Final cleaned dataset created after preprocessing.

---

## Question 19 : Create Final Dataset

Created final cleaned dataset after applying all preprocessing techniques.

---

## Question 20 : Remove Temporary Columns

Removed helper columns generated during preprocessing process.

---

## Question 21 : Final Missing Value Verification

Checked dataset after cleaning.

Final result:

* Remaining Missing Values = 0

---

## Question 22 : Original Dataset Summary

Displayed statistical summary of original raw dataset.

---

## Question 23 : Cleaned Dataset Summary

Displayed statistical summary of cleaned dataset.

---

## Question 24 : Save Final Dataset

Generated final output file.

Output:

* cleaned_patient_dataset.csv

---

## Question 25 : Final Dataset Preview

Displayed final cleaned dataset for verification.

---

## Question 26 : Project Conclusion

Project successfully completed.

Final results:

* Missing values handled successfully
* Outliers detected successfully
* Extreme values treated successfully
* Final cleaned dataset created
* Dataset prepared for machine learning

---

# 📊 Techniques Used

### Missing Value Handling

* Mean Imputation
* Most Frequent Imputation
* Missing Indicator Method
* Random Sample Imputation
* KNN Imputer
* MICE Algorithm

### Outlier Detection

* Z Score Method
* IQR Method
* Percentile Method
* Winsorization

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit Learn
* Jupyter Notebook

---

# 📁 Project Files

* healthcare_data_preprocessing_project.ipynb
* patient_health_records.csv
* cleaned_patient_dataset.csv
* Project_Report.docx
* README.md

---

# 🎓 Learning Outcome

This project helped in understanding:

* Data preprocessing workflow
* Missing value treatment techniques
* Outlier detection techniques
* Feature engineering methods
* Preparing machine learning ready dataset

---

# Final Conclusion

This project successfully demonstrates practical implementation of **Data Preprocessing and Feature Engineering** on healthcare patient dataset.

Different missing value handling techniques and outlier detection methods were applied successfully.

A final cleaned dataset was created and prepared for future machine learning applications.

This project improved understanding of real-world data cleaning process used in data analytics and machine learning.

---
