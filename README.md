# 🏥 Healthcare Patient Flow - EDA Project

## 📌 Overview
This project performs Exploratory Data Analysis (EDA) on healthcare patient flow data to understand patient behavior, hospital operations, and key factors affecting admission, wait time, and satisfaction.

## 🎯 Objectives
- Analyze patient demographics (age, gender, race)
- Study patient wait time and satisfaction score
- Explore admission patterns
- Understand department referral trends
- Identify relationships between key variables

## 📊 Dataset Features
- Patient Id
- Patient Age
- Patient Gender
- Patient Race
- Patient Waittime
- Patient Satisfaction Score
- Department Referral
- Patient Admission Flag

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🔍 Analysis Performed

### 1. Univariate Analysis
- Distribution of age, wait time, satisfaction score
- Summary statistics (mean, median, skewness)
- Category distributions

### 2. Bivariate Analysis
- Relationship between:
  - Wait time vs Satisfaction
  - Admission vs other features
  - Department referrals vs outcomes

### 3. Multivariate Analysis
- Combined feature interactions
- Encoded categorical variables for deeper insights

## ⚙️ Data Preprocessing
- Removed irrelevant columns (Patient ID, timestamps)
- Handled missing values
- Converted data types
- Applied encoding for categorical features

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook eda.ipynb
