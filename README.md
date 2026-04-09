# 🏦 Loan Default Prediction — Machine Learning

## Overview
A collaborative machine learning project developed for an ANZ Bank analytics challenge. The goal is to predict whether a loan will **default or be approved** based on applicant demographics, financial history, and loan details. The project follows an **Agile workflow** and covers the full data science pipeline — from exploratory analysis through to model evaluation and cloud storage of results using **Microsoft Fabric**.

## Business Context
Predicting loan defaults helps banks minimise financial risk, improve profitability, and make faster, more informed lending decisions. This project builds and compares multiple classification models to identify the most accurate predictor of loan outcomes.

## Dataset
Loaded from **Azure Blob Storage** 

Key features include:
- Applicant demographics — age, gender, education, income, employment experience, home ownership
- Loan details — amount, intent, interest rate, percentage of income
- Credit profile — credit score, credit history length, previous defaults
- Target variable — `loan_status` (1 = defaulted, 0 = approved)

## Tasks Completed

- **Agile Project Management** — set up a Jira board with To-do / In-progress / Done columns; conducted daily stand-ups and documented blockers
- **Exploratory Data Analysis (EDA)** — inspected data types, missing values, filtered outliers and visualised distributions of loan amounts, credit scores, and loan statuses; analysed feature correlations via Python Codes
- **Data Preprocessing** — handled missing values, filtered outliers, encoded categorical variables, and split data into training and testing sets
- **Model Training** — trained and compared three classification models:
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting 
- **Model Evaluation** — compared models using accuracy and confusion matrices; built an Actual vs Predicted results table for each model
- **Cloud Storage** — saved prediction results to a **Microsoft Fabric DataLakehouse** as a Delta table
- **Reporting** — produced a PowerPoint presentation summarising findings, visualisations, and model recommendations

## Results & Conclusion
Models were evaluated and compared to identify the best performer for predicting loan defaults, with insights provided on how the chosen model can support the bank's lending decision-making process.

## Tools & Skills
`Python` · `Scikit-learn` · `Pandas` · `Matplotlib / Seaborn` · `Logistic Regression` · `Random Forest` · `Gradient Boosting / XGBoost` · `Microsoft Fabric` · `Azure Blob Storage` · `Jira` · `Agile`
