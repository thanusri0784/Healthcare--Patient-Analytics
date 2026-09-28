# 🏥 Healthcare Patient Analytics

## 📌 Project Overview

Healthcare Patient Analytics is a data analytics and business intelligence project developed to analyze patient visits, treatment costs, length of stay, recovery scores, and readmission risk.

The project uses Python for data cleaning and exploratory data analysis and Power BI to create an interactive dashboard for understanding healthcare patient patterns and supporting data-driven decision-making.

## 🎯 Objectives

* Analyze patient visit patterns.
* Compare patient visits across departments and regions.
* Analyze average treatment costs.
* Study average length of hospital stay.
* Analyze patient recovery scores.
* Examine readmission risk across departments and age groups.
* Develop an interactive Power BI dashboard.
* Provide data-driven recommendations based on the analysis.

## 📊 Dataset

The project uses a healthcare patient analytics dataset containing **5,000 patient records**.

### Main Features

* Patient ID
* Visit Date
* Age Group
* Gender
* Region
* Department
* Treatment Type
* Visit Type
* Length of Stay
* Treatment Cost
* Recovery Score
* Readmission Risk

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* Microsoft Power BI
* GitHub

## 🔄 Project Workflow

Raw Data
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
KPI Analysis
   ↓
Risk & Opportunity Analysis
   ↓
Power BI Dashboard
   ↓
Insights & Recommended Actions


## 🧹 Data Cleaning & Analysis

Python was used to load, inspect, clean, and analyze the healthcare dataset.

The analysis included:

* Data quality checking
* Data type handling
* Missing-value checking
* Duplicate checking
* Descriptive statistics
* Group-by analysis
* Department-wise analysis
* Age-group analysis
* Risk analysis
* KPI calculation

The cleaned dataset was then used for further analysis and dashboard development.

## 📈 Key KPIs

| KPI                         |     Value |
| --------------------------- | --------: |
| 👥 Total Patient Visits     |     5,000 |
| 💰 Average Treatment Cost   |    54.92K |
| 🛏️ Average Length of Stay  | 4.06 days |
| ❤️ Average Recovery Score   |     74.72 |
| ⚠️ Average Readmission Risk |      0.28 |

## 📊 Power BI Dashboard

The Power BI dashboard contains three main pages:

### 1. 📌 Executive Overview

Provides an overall view of:

* Total patient visits
* Average treatment cost
* Average length of stay
* Average recovery score
* Average readmission risk
* Monthly patient visits
* Department-wise patient visits
* Region-wise patient visits

### 2. 📊 Department & Patient Analysis

Provides detailed analysis of:

* Patient visits by department
* Average treatment cost by department
* Average length of stay by department
* Average recovery score by department
* Patient visits by age group

Interactive slicers are provided for:

* Age Group
* Gender
* Region
* Department

### 3. ⚠️ Risk & Action Analysis

Focuses on:

* Average readmission risk by department
* Average readmission risk by age group
* Department-level summary
* Recommended actions based on the analysis

## 🎯 Recommended Actions

* Monitor readmission risk across departments and age groups.
* Review departments with higher average treatment costs for resource planning.
* Track length of stay alongside recovery scores to identify improvement opportunities.
* Use patient and risk trends to support targeted follow-up and care planning.

## 📁 Project Files

Healthcare-Patient-Analytics/
│
├── Healthcare_Patient_Analytics.ipynb
├── requirements.txt
├── Healthcare_Patient_Analytics_ProjectReport.docx
├── README.md
└── healthcare_patient_analytics_cleaned.csv


## 📌 Project Outcome

The project transforms raw healthcare patient data into meaningful analytical insights through Python and an interactive Power BI dashboard.

The dashboard provides a clear view of patient activity, department performance, treatment costs, recovery patterns, and readmission risk.


