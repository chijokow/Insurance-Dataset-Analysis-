# Health Insurance Cost Analysis using Python
# Project Overview
> This project analyzes health insurance charges using Python, focusing on key factors such as age, BMI, smoking status, region, and more. The dataset is obtained from Kaggle and processed to extract meaningful insights through exploratory data analysis (EDA) and data visualization.

# Tasks Performed
Data Acquisition

> - Downloaded the dataset from Kaggle using the Kaggle API.
> - Extracted and loaded the dataset into a Pandas DataFrame.

Data Cleaning & Preparation
> - Checked for missing values and handled them using median imputation.
> - Converted categorical variables (e.g., sex, smoker, region) into numerical representations for analysis.
> - Applied one-hot encoding to categorical data for machine learning compatibility.

Exploratory Data Analysis (EDA)
> - Descriptive Statistics: Summarized key statistics of numerical columns.
> - Correlation Heatmap: Identified relationships between numerical variables, highlighting factors affecting insurance charges.
> - Distribution Analysis: Explored the spread of insurance charges using histograms.
> - Scatter Plots: Visualized relationships between charges and features like age and BMI.
> - Box Plots: Compared charges across different categories, such as smokers vs. non-smokers and regions.

Feature Engineering
> - Created BMI categories (Underweight, Normal, Overweight, Obese) to analyze its impact on charges.
> - Grouped individuals into age categories (Young, Adult, Middle-aged, Senior) for better trend analysis.

Data Export
> - Saved the processed dataset with encoded categorical variables for further modeling or predictive analysis.
