# DavidWangJoryaYi_FinalProject
In this project, we built a machine learning model to predict whether an individual has cardiovascular disease using clinical and lifestyle data. Cardiovascular disease is one of the leading causes of death worldwide, so being able to identify risk factors early is an important real-world application of predictive modeling.

We chose this project because it combines healthcare relevance with a dataset that is well-suited for practicing data cleaning, exploratory analysis, and classification models. It also allowed us to compare simpler models with more complex ones and evaluate whether added complexity actually improves performance.

The dataset contains approximately 70,000 anonymized patient records with a mix of objective health measurements and self-reported lifestyle information. Features include age, height, weight, blood pressure, cholesterol levels, glucose levels, smoking habits, alcohol consumption, and physical activity. The target variable indicates the presence or absence of cardiovascular disease.

Before modeling, we performed data cleaning to remove duplicates and unrealistic outliers, converted age from days to years, created derived features such as BMI, and categorized blood pressure levels based on standard clinical guidelines.

In the EDA notebook, we explored the distribution of key variables and examined relationships between risk factors and cardiovascular disease. We visualized differences in age, BMI, blood pressure, cholesterol, glucose, and lifestyle behaviors between individuals with and without cardiovascular disease. We also performed an age-based trend analysis to understand how disease prevalence varies across different age groups.

This step helped guide our modeling choices and confirmed that age, blood pressure, and BMI are strongly associated with cardiovascular risk.

We framed this task as a binary classification problem. To evaluate different modeling strategies, we implemented several machine learning models:

Logistic Regression as a baseline linear model

Decision Tree to explore non-linear decision rules

Random Forest to improve stability and performance through ensembling

XGBoost as a gradient boosting model for comparison

We split the data into training and testing sets and evaluated models using accuracy, F1 score, ROC curves, and confusion matrices. We also used cross-validation to assess model stability across different subsets of the data.
