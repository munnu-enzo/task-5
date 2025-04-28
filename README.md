
itanic Dataset EDA
Project Overview
This project, part of a Data Analyst Internship, explores the Titanic dataset to find key insights.

Tools Used
Python (Pandas, Matplotlib, Seaborn) and Jupyter Notebook.

Dataset Information
Source: Kaggle
Size: 891 rows, 12 columns

Contains passenger data: age, gender, class, fare, survival, etc.

EDA Steps
Included data loading, cleaning (handling missing values), univariate, bivariate, and multivariate analyses, visualizations, and a summary.

Summary of Findings

General Observations
Missing values in Age, Cabin, and Embarked.
Cabin had many missing values (~77%).

Key Findings:
Survival Rate: Around 38%.
Gender: Females survived more often (~74%) than males (~19%).
Passenger Class: 1st class had the highest survival (~63%); 3rd class, the lowest (~24%).
Age: Most passengers were 20-40 years old. Children (<10) had better survival chances.
Fare: Higher fares correlated with higher survival.
Embarked Port: Southampton (S) was most common; Cherbourg (C) had higher survival.
Correlations: Fare and Pclass showed moderate correlation.


Key Insights
Gender and Passenger Class strongly influenced survival.
Children had a slight survival advantage.
Socio-economic status was important for survival.

Files Included
Titanic_EDA.ipynb (Notebook)
EDA_Report.pdf (PDF report)
train.csv (dataset,)
README.md 

Conclusion
EDA revealed factors affecting Titanic survival. Visualizations helped understand variable relationships.
