
## Student Depression Analysis



### Project Overview

This project focuses on analysing student depression using demographic, academic, and lifestyle-related variables. Rather than attempting to make clinical diagnoses or predictions, the primary goal was to understand patterns in the data, explore factors associated with depressive symptoms, and observe how different features relate to student mental health.


### Dataset

The dataset consists of student-level records containing information such as age, gender, academic pressure, sleep duration, study hours, financial stress, social factors, and indicators related to depressive symptoms. Each row represents an individual student. The dataset reflects self-reported data and therefore includes subjectivity and potential noise, which is common in mental health–related datasets.


### Problem Context

The analysis is framed as an exploratory data problem rather than a purely predictive task. The objective is to examine relationships between academic, social, and lifestyle factors and reported depression levels, and to identify which variables appear most strongly associated with mental health outcomes among students.


### Data Preprocessing

Basic data cleaning was performed prior to analysis. This included handling missing values, encoding categorical variables, and scaling numerical features where necessary. No aggressive filtering was applied in order to preserve the real-world variability present in the data.


### Analysis and Modelling

Exploratory data analysis was used to study distributions, correlations, and trends across different student groups. Where applicable, simple machine learning models were used to observe how features contribute to outcomes, with an emphasis on interpretability rather than maximising predictive performance.


### Observations

Initial analysis suggests that factors such as academic pressure, sleep patterns, and financial stress show noticeable associations with reported depressive symptoms. No single variable fully explains student depression, highlighting its multifactorial nature. The results reinforce the idea that mental health outcomes are influenced by a combination of academic, social, and personal factors.


### Libraries

This project was implemented in Python using Pandas and NumPy for data manipulation, Scikit-learn for preprocessing and modelling, and Matplotlib and Seaborn for visualisation during exploratory analysis.


### Conclusion

This project demonstrates how data analysis techniques can be applied to sensitive real-world topics such as student mental health. The focus remains on understanding data patterns and relationships rather than drawing medical conclusions, highlighting both the potential and the limitations of data-driven approaches in this domain.



