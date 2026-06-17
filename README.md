# 🏥 Healthcare Data Preprocessing and Feature Engineering Project

## 📌 Project Overview

This project focuses on applying **Data Preprocessing** and **Feature Engineering** techniques on a healthcare patient dataset.

The purpose of this project is to clean raw healthcare data by identifying missing values, applying multiple imputation techniques, detecting outliers, treating extreme values, and preparing a final clean dataset suitable for machine learning applications.

This project demonstrates practical implementation of data cleaning techniques used in real-world data analytics.

---

# 🎯 Project Objective

The main objectives of this project are:

* To analyze healthcare dataset and identify missing values
* To apply different missing value imputation techniques
* To detect outliers using statistical methods
* To treat extreme values using outlier handling techniques
* To compare dataset before and after preprocessing
* To prepare a final cleaned dataset for machine learning

---

# 📂 Dataset Description

The dataset contains healthcare patient records.

| Column Name    | Description                        |
| -------------- | ---------------------------------- |
| patient_id     | Unique identifier for each patient |
| age            | Age of patient                     |
| gender         | Gender of patient                  |
| region         | Region of residence                |
| bmi            | Body Mass Index                    |
| blood_pressure | Blood pressure level               |
| cholesterol    | Cholesterol level                  |
| glucose        | Glucose level                      |
| disease_risk   | Disease prediction target          |

The dataset intentionally contains missing values and outliers for preprocessing practice.

---

# PART A : Handling Missing Values

Different missing value handling techniques were applied.

## Question 1 : Import Required Libraries

Libraries used:

* Pandas
* NumPy
* Matplotlib
* Scikit Learn
* SciPy

---

## Question 2 : Load Dataset

Dataset loaded using Pandas DataFrame.

File used:

* patient_health_records.csv

---

## Question 3 : Display Basic Dataset Information

Basic analysis performed:

* Dataset shape
* Column names
* Data types

---

## Question 4 : Identify Missing Values

Missing values detected in following columns:

* Age
* Gender
* Region
* BMI
* Cholesterol
* Glucose

---

## Question 5 : Missing Value Percentage Analysis

Calculated percentage of missing values in each column for better understanding of data quality.

---

## Question 6 : Mean Imputation

Applied Mean Imputation on:

* BMI Column

Missing BMI values replaced using average BMI value.

---

## Question 7 : Most Frequent Imputation

Applied Most Frequent Imputation on:

* Region Column

Missing categorical values replaced using most common category.

---

## Question 8 : Gender Imputation

Applied Most Frequent Imputation on:

* Gender Column

Missing gender values replaced using mode.

---

## Question 9 : Missing Indicator Method

Created binary indicator column to identify missing values in:

* Age Column

---

## Question 10 : Random Sample Imputation

Applied Random Sample Imputation on:

* Age Column

Missing age values replaced using randomly selected existing values.

---

## Question 11 : KNN Imputer

Applied **K-Nearest Neighbor Algorithm** for multivariate missing value handling.

Columns used:

* Age
* BMI
* Cholesterol
* Glucose

---

## Question 12 : MICE Algorithm

Applied **Multiple Imputation by Chained Equations (MICE)** for advanced missing value treatment.

This method generates more statistically accurate estimations.

---

## Question 13 : Missing Values Visualization

Created bar graph to visualize missing values before cleaning process.

<img width="576" height="595" alt="image" src="https://github.com/user-attachments/assets/4d8080de-f408-4c4c-9b22-3be144bfd97c" />



---

# PART B : Outlier Detection and Handling

Different statistical techniques were used for outlier detection.

---

## Question 14 : Z Score Method

Applied Z Score statistical method to detect extreme outliers.

Used for:

* Cholesterol Column

---

## Question 15 : IQR Method

Applied **Interquartile Range (IQR)** method to detect unusual BMI values.

Used for:

* BMI Column

---

## Question 16 : Percentile Method

Applied percentile capping to handle extreme values.

Used for:

* Glucose Column

---

## Question 17 : Winsorization

Applied Winsorization technique to cap extreme values.

Used for:

* Cholesterol Column

---

## Question 18 : Outlier Visualization

Created boxplot to visualize cholesterol outliers.

<img width="551" height="435" alt="image" src="https://github.com/user-attachments/assets/372c591a-4f5f-4bde-8489-72318addda96" />


---

# PART C : Final Clean Dataset

Final dataset created after applying preprocessing techniques.

---

## Question 19 : Create Final Dataset

Created final cleaned dataset after applying all preprocessing methods.

---

## Question 20 : Remove Temporary Columns

Removed helper columns created during preprocessing process.

---

## Question 21 : Final Missing Value Check

Verified final dataset.

Final Result:

* All missing values successfully removed
* Missing values count = 0

---

## Question 22 : Original Dataset Summary

Displayed statistical summary of original raw dataset.

---

## Question 23 : Cleaned Dataset Summary

Displayed statistical summary of cleaned dataset.

---

## Question 24 : Save Final Dataset

Generated final dataset file.

Output file:

* cleaned_patient_dataset.csv

---

## Question 25 : Final Dataset Preview

Displayed final processed dataset for verification.

---

## Question 26 : Project Conclusion

Project completed successfully.

Final results:

* Missing values handled successfully
* Outliers detected successfully
* Extreme values treated successfully
* Final clean dataset created
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

### Outlier Detection and Handling

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
* Project_Report_Final.docx
* README.md

---

# 🎓 Learning Outcome

Through this project, I learned:

* Practical Data Preprocessing
* Missing Value Treatment Techniques
* Outlier Detection Methods
* Feature Engineering Process
* Preparing Machine Learning Ready Datasets

---

# Final Conclusion

This project successfully demonstrates practical implementation of **Data Preprocessing and Feature Engineering** on healthcare patient dataset.

Different missing value handling techniques and outlier detection methods were applied successfully.

A final cleaned dataset was created and prepared for future machine learning applications.

This project helped in understanding real-world data cleaning workflow used in professional data analytics.

---
