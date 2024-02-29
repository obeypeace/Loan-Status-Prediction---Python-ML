# Loan-Status-Prediction---Python-ML
Welcome to the loan status prediction project! In this project, we aim to predict the status of loans using data provided by a finance company. By leveraging machine learning techniques, we strive to build models that can accurately classify whether a loan will be approved or denied based on various features provided in the dataset.

## Table of Contents
- [Project Objective](#Project-objective)
- [Data Scource](#data-source)
- [Data Processing](#data-processing)
- [Evaluation Metrices](#evaluation-metrices)
- [Key Insights](#key-insights)
- [conclusion and recommendations](#conclusion and recommendations)

## Project Objective
The main objective of this project is to develop predictive models that can effectively determine the status of loans, thereby assisting the finance company in making informed decisions regarding loan approvals. By analyzing historical data and identifying patterns, we seek to build robust models that can predict loan status with high accuracy.

## Data Source
The dataset used in this project is sourced from the finance company's internal records. It contains information about past loan applications, including applicant details, loan amounts, interest rates, employment status, credit scores, and other relevant features. The dataset is anonymized to ensure privacy and confidentiality.

## Data Processing
Before training the machine learning model, the dataset undergoes preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features. Exploratory data analysis (EDA) techniques are applied to gain insights into the distribution and relationships between different features. Additionally, the dataset is split into training and testing sets to evaluate the model's performance. Regression models were used for the monthly income machine learning building while classification models were used for the attrition machine learning building. Lastly, the model was stimulated on a new dataset and used to make relevant predictions

## Evaluation Metrices
To evaluate the performance of our models, we employ various evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. These metrics provide a comprehensive assessment of model performance and help us choose the most suitable model for deployment.

## key Insights
- 85.4% of applicants are male while 14.6% of applicants are female
- 69.2% of the applicants loan status are still active while 30.8% have inactive loan status
- 360 days have the highest loan amount term count
- Most of the applicant income falls within a range of 2877 - 5795, with a median value of 3812. There are some outliers with amount as high as 81000.
- Most of the loan amount falls within a range of 100 - 200, with a median value of 128. There are some outliers with amount as high as 700.
- The co applicant income falls within a range of 1188 - 2297. There are some outliers with amount as high as 41667.
- Applicants with a higher perentage of active loan status are married, male, have 0 dependents, are not self-employed, are graduates and they live in semi-urban areas
  
## Conclusion and Recommendations
Considering these metrics, XGB Classifier performed well across most metrics and is the model best suited for predicting the loan status of applicants
