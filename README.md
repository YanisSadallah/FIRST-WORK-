# HR Data Analysis: Performance & Absenteeism

## Project Overview
This project analyzes a Human Resources dataset to investigate potential correlations between employee demographics, performance scores, and absenteeism. The objective is to identify data-driven patterns to support workforce management decisions.

## Methodology
The analysis follows a structured data science workflow:
1.  **Data Preprocessing:** Handling missing values and formatting data types.
2.  **Exploratory Data Analysis (EDA):** Visualizing distributions of performance and absences.
3.  **Statistical Hypothesis Testing:** Implementing **Chi-Square tests** to determine if performance scores are independent of gender (p-value analysis).
4.  **Anomaly Detection:** Using the **Interquartile Range (IQR)** method to detect statistical outliers in absenteeism records.

## Key Findings
* **Performance & Gender:** Statistical tests suggest [There is/There is no] significant correlation between gender and performance ratings.
* **Absenteeism:** Outlier analysis identified specific profiles exceeding the upper bound of [X] days of absence.

## Stack & Tools
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, SciPy (Stats), Seaborn, Matplotlib.
