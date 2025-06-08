# Customer-Retention-Enhancement-through-Predictive-Analytics-at-SmartBank-Lloyds-Banking-Group

## Project Overview
This project was initiated to address the increasing problem of **customer churn** at **SmartBank**, a subsidiary of **Lloyds Banking Group**. The focus is on developing a predictive model that can identify at-risk customers and suggest targeted interventions for retaining them. The project involves collecting and analyzing customer data, performing exploratory data analysis (EDA), building a predictive machine learning model, and evaluating its performance to inform business strategies.

As a **Data Science Graduate** at **Lloyds Banking Group**, working within the **Data Science & Analytics Team**, my role in this project is multifaceted and crucial to understanding customer churn. My primary responsibility is to gather and analyze customer data to identify key patterns and behaviors that contribute to churn. I perform **Exploratory Data Analysis (EDA)** to uncover valuable insights about customer behavior, which serves as the foundation for developing effective strategies to mitigate churn. Additionally, I clean and preprocess the data to ensure it is accurate and ready for model building. Once the data is prepared, I develop a **predictive machine learning model** aimed at classifying customers who are at risk of churning. I also evaluate and measure the model's performance to ensure its reliability and accuracy. Throughout this process, I document and report my findings through detailed reports, enriched with visualizations, which will be used to guide business decision-making and enhance customer retention strategies.

## Organization Background
**Lloyds Banking Group** is a prominent UK-based financial services organization, offering a range of banking and insurance products. As part of the **Data Science & Analytics team**, I work closely with a highly skilled group of analysts and data scientists focused on providing actionable insights using advanced data analysis techniques. Our mission is to enhance customer retention strategies and optimize business decision-making by leveraging predictive models and in-depth data analysis.

The **Data Science & Analytics team** at Lloyds Banking Group uses a variety of techniques, including machine learning and statistical analysis, to help the business understand customer behavior and make informed decisions that positively impact customer retention.

## Problem Statement
**Customer churn** is a growing concern for SmartBank, as certain segments of their customer base are moving to competitors offering more personalized banking solutions. This project aims to develop a predictive model that can identify customers at risk of leaving and provide insights into retention strategies.

### Key challenges:
- **Declining retention rates**, especially among young professionals and small business owners.
- **Competitors offering more tailored services**, putting SmartBank's customer base at risk.
- The need for a **predictive model** to better identify at-risk customers and take proactive retention measures.

## Project Requirements

### Phase 1: Data Gathering and Exploratory Analysis
**Objective**: Gather relevant data, perform EDA, and prepare the dataset for machine learning.
- Identify key data sources related to customer demographics, transaction history, and customer service interactions.
- Clean and preprocess data by handling missing values, encoding categorical variables, and addressing any outliers.
  
**Deliverable**: A comprehensive report on EDA, visualizations of key insights, and a cleaned dataset ready for model building.

### Phase 2: Building a Machine Learning Model
**Objective**: Build a predictive model to classify customers likely to churn, and suggest ways to evaluate its performance.
- Select an algorithm (e.g., logistic regression, decision trees, random forests).
- Train and validate the model using the cleaned dataset from Phase 1.
- Propose evaluation metrics (precision, recall, F1 score, etc.) to assess the model’s effectiveness.

**Deliverable**: A trained model, performance evaluation report, and suggestions for how the model can be applied to business strategies.

## Tasks Performed

### Task 1: Data Gathering and Exploratory Analysis
- **Dataset Used**: **Customer_Churn_Data_Large.csv** (provided dataset).
  - The data contains information on customer demographics, transaction history, and customer service interactions.
  - I gathered relevant features to analyze customer behavior and churn patterns.

- **Exploratory Data Analysis (EDA)**:
  - I performed statistical analysis and used data visualization tools like histograms, box plots, and scatter plots to uncover key features influencing churn.
  - Identified important variables such as customer tenure, service usage, and customer satisfaction that correlate with higher churn rates.

- **Data Cleaning and Preprocessing**:
  - Addressed missing values through imputation and removal, depending on the context of the feature.
  - Capped extreme outliers and standardized numerical features to ensure the data was ready for modeling.
  - Encoded categorical variables using one-hot encoding to transform them into a format suitable for machine learning.

- **Deliverable**:
  - **Report** titled "Customer_Churn_Analysis_Report" detailing the exploratory analysis, insights from data visualizations, and the steps taken to clean and preprocess the data.
  - **Cleaned dataset** ready for building predictive models.

### Task 2: Building a Machine Learning Model
- **Model Selection**:
  - Based on the problem and the data at hand, I selected **Random Forest** as the algorithm due to its high interpretability and ability to handle both numerical and categorical data.
  - I used **cross-validation** and **hyperparameter tuning** to improve the model's performance.

- **Model Training and Validation**:
  - Trained the **Random Forest model** on the preprocessed dataset and used **cross-validation** to ensure the model generalizes well to unseen data.
  - Evaluated the model’s performance using metrics like accuracy, precision, recall, and ROC-AUC.

- **Performance Evaluation**:
  - After evaluating the model, I proposed the following metrics for measuring performance:
    - **Precision and Recall** to account for class imbalance (churn vs. non-churn).
    - **F1 Score** to combine precision and recall.
    - **Confusion Matrix** and **ROC-AUC** to visualize the model's performance.

- **Deliverable**:
  - **Report** titled "Customer_Churn_Analysis_Report_with_Visuals", which includes the model-building process, performance evaluation metrics, and visualizations.
  - **Trained model** ready to be deployed for business use.

## Solution

### Phase 1 Solution:
After performing **EDA** and cleaning the data, I identified the most influential factors contributing to customer churn. These insights will be valuable for developing targeted retention strategies. The cleaned data was prepared and is now ready for use in predictive modeling.

### Phase 2 Solution:
The **Random Forest model** was trained and validated successfully. The model has shown good predictive power, with high accuracy and robust performance across various evaluation metrics.

I also provided recommendations for how the model can be deployed in the business context:
- Identifying **at-risk customers** early and implementing retention strategies such as **personalized offers** or **targeted communication**.

## Files in the Repository:
- **Customer_Churn_Data_Large.csv** – The dataset provided for this project, containing customer information relevant to churn prediction.
- **Customer_Churn_Analysis_Report** – The report detailing the **EDA** process, findings, and data cleaning steps.
- **Customer_Churn_Analysis_Report_with_Visuals** – The report that includes the **machine learning model**, performance evaluation, and visualizations of the results.

## Conclusion
By leveraging predictive analytics and machine learning, this project has contributed to **SmartBank's** strategy to improve customer retention. Through thorough data analysis and model development, we can now identify at-risk customers and take **targeted actions** to retain them. This project is a vital part of **Lloyds Banking Group’s** effort to enhance customer satisfaction and ensure long-term success.

