[README_Health_Insurance_Analysis-2.md](https://github.com/user-attachments/files/28399855/README_Health_Insurance_Analysis-2.md)
# 🏥 Health Insurance Cost Analysis using Python

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)
![Type](https://img.shields.io/badge/Type-EDA%20%7C%20Feature%20Engineering-purple?style=flat-square)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=flat-square&logo=kaggle)

---

## Project Overview

This project analyses health insurance charges using Python, focusing on key factors such as age, BMI, smoking status, and region. The dataset is sourced from Kaggle and explored through EDA and data visualisation to extract meaningful insights.

---

## Dataset

**Source:** [Kaggle — Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance) · 1,338 records · 7 features: age, sex, BMI, children, smoker, region, charges

---

## Tasks Performed

**Data Acquisition** — Downloaded via Kaggle API and loaded into a pandas DataFrame

**Data Cleaning & Preparation** — Checked for missing values (median imputation); converted categorical variables to numerical; applied one-hot encoding

**Exploratory Data Analysis** — Descriptive statistics; correlation heatmap; charge distribution histogram; scatter plots (age, BMI vs charges); box plots across smoking status, region, gender, and number of children; pairplot

**Feature Engineering** — Created BMI categories (Underweight / Normal / Overweight / Obese) and age groups (Young / Adult / Middle-aged / Senior)

**Data Export** — Processed dataset saved as CSV for further modelling

---

## Key Findings

- **Smoking** is the strongest cost driver — smokers pay 3–4x more than non-smokers
- **Age** shows a clear positive relationship with charges across three distinct cost bands
- **High BMI + smoking** consistently places patients in the highest charge bracket
- **Region** has a modest effect — Southeast shows slightly elevated charges

---

## Tools

Python · pandas · NumPy · Matplotlib · Seaborn · Kaggle API · Google Colab

---

## How to Run

1. Open `Data Analysis/Insurance_Dataset_Analysis.ipynb` in Google Colab or Jupyter
2. Set up Kaggle API credentials or upload `insurance.csv` directly
3. Run all cells sequentially

---

## Author

**William C** | [@chijokow](https://github.com/chijokow)  
Data Analyst | Python · SQL · Power BI

---
