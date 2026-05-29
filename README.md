# ❤️ CardioPulse-AI

### AI-Powered Heart Disease Risk Prediction & Healthcare Analytics Platform

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python\&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-F7931E?logo=tensorflow\&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikitlearn\&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi\&logoColor=black)
![Healthcare AI](https://img.shields.io/badge/Healthcare-AI-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

</p>

---

## Overview

CardioPulse-AI is an end-to-end healthcare analytics and machine learning platform designed to analyze cardiovascular health data and predict heart disease risk.

The project combines data preprocessing, exploratory data analysis, statistical validation, machine learning, and interactive business intelligence dashboards to transform raw clinical data into meaningful healthcare insights.

Developed as an academic team project, CardioPulse-AI simulates a real-world healthcare data science workflow used in predictive analytics and clinical decision-support systems.

---

## Highlights

* End-to-end healthcare analytics pipeline
* Heart disease risk prediction using Machine Learning
* Advanced data preprocessing and feature engineering
* Exploratory Data Analysis (EDA)
* Statistical validation using Chi-Square Testing
* Logistic Regression and Random Forest models
* Feature importance analysis
* ROC-AUC and Confusion Matrix evaluation
* Interactive Power BI Dashboard
* Healthcare-focused visual analytics

---

## Project Objectives

* Analyze real-world cardiovascular healthcare data
* Perform comprehensive Exploratory Data Analysis (EDA)
* Discover clinical risk factors associated with heart disease
* Validate statistical relationships between variables
* Train and compare machine learning models
* Evaluate predictive performance using healthcare ML metrics
* Generate actionable healthcare insights
* Build an integrated cardiovascular analytics system

---

## Dataset Information

### Dataset

Heart Failure Prediction Dataset (Kaggle)

### Dataset Statistics

| Metric                 | Value                 |
| ---------------------- | --------------------- |
| Initial Records        | 918                   |
| Records After Cleaning | 836                   |
| Target Variable        | HeartDisease          |
| Positive Class         | Heart Disease Present |
| Negative Class         | No Heart Disease      |

### Key Features

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* Oldpeak
* ST Slope

---

## Methodology

### 1. Data Preprocessing

* Missing value handling
* Invalid value correction
* Outlier detection using IQR
* Feature scaling using StandardScaler
* One-hot encoding of categorical variables

### 2. Exploratory Data Analysis

* Histograms
* Boxplots
* Correlation Heatmaps
* Distribution Analysis
* Target Variable Analysis

### 3. Statistical Validation

Chi-Square testing was applied to determine statistically significant relationships between categorical clinical features and heart disease occurrence.

### 4. Machine Learning Models

#### Logistic Regression

Used as the baseline classification model.

#### Random Forest Classifier

Used as the primary predictive model for heart disease classification.

### 5. Model Evaluation

Evaluation metrics included:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix
* Cross Validation

---

## Model Performance

| Model               | Accuracy | ROC-AUC |
| ------------------- | -------- | ------- |
| Logistic Regression | 89%      | 0.953   |
| Random Forest       | 92%      | 0.959   |

### Best Performing Model

Random Forest achieved the highest predictive performance and demonstrated superior generalization capability on unseen data.

### Key Predictive Features

The most influential features included:

* ST Slope
* Maximum Heart Rate
* Cholesterol
* Age
* Chest Pain Type

---

## Power BI Dashboard

The interactive Power BI dashboard enables:

* KPI summaries
* Risk factor exploration
* Clinical trend analysis
* Correlation visualization
* Model performance monitoring
* Feature importance interpretation

The dashboard allows healthcare data exploration through dynamic filtering and visual analytics.

---

## System Workflow

```text
Data Collection
        ↓
Data Preprocessing
        ↓
Exploratory Data Analysis
        ↓
Statistical Testing
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Power BI Dashboard
        ↓
Healthcare Insights
```

---

## Technology Stack

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Machine Learning

* Scikit-learn
* Logistic Regression
* Random Forest

### Data Visualization

* Matplotlib
* Seaborn
* Power BI

### Development Tools

* Jupyter Notebook
* Git
* GitHub

---

## Project Structure

```text
CardioPulse-AI
│
├── data
│   ├── processed
│   └── raw
│
├── diagrams
│   ├── DFD_Level_1.png
│   └── System_Workflow_Diagram.png
│
├── frontend
│   ├── models
│   │   ├── random_forest_model.pkl
│   │   └── scaler.pkl
│   │
│   ├── static
│   │   ├── css
│   │   └── js
│   │
│   └── templates
│       └── index.html
│
├── notebooks
│   └── HeartDisease_DS.ipynb
│
├── powerbi
│   └── CardioPulse_AI_Analytics_Dashboard.pbix
│
├── report
│   └── CardioPulse_AI_Data_Science_Project_Report.pdf
│
├── app.py
├── README.md
├── LICENSE
└── .gitignore
```

---

## Learning Outcomes

* Healthcare Data Analytics
* Data Cleaning & Preprocessing
* Exploratory Data Analysis
* Statistical Testing
* Feature Engineering
* Machine Learning Model Development
* Model Evaluation & Validation
* Power BI Dashboard Development
* End-to-End Data Science Workflow

---

## Repository Assets

### Research Report
A complete project report documenting methodology, analysis, model development, evaluation, and conclusions.

Location:
report/CardioPulse_AI_Data_Science_Project_Report.pdf

### Power BI Dashboard
Interactive analytics dashboard for exploring cardiovascular health patterns and model insights.

Location:
powerbi/CardioPulse_AI_Analytics_Dashboard.pbix

### System Design
Contains workflow and DFD diagrams describing the architecture and analytical pipeline.

Location:
diagrams/

---

## Team Members

* Abdul Ahad
* Muhammad Wafa Abbas
* Abdul Rehman

Department of Computer Science

---

## Installation

### Clone Repository

```bash
git clone https://github.com/ahadbuilds/CardioPulse-AI.git
```

### Navigate to Project

```bash
cd CardioPulse-AI
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Future Enhancements

* Deep Learning Models
* Explainable AI (XAI)
* Real-Time Prediction Dashboard
* Cloud Deployment
* Model Monitoring
* Healthcare Recommendation System

---

## Disclaimer

This project is intended solely for educational, research, and portfolio purposes.

It is not designed for medical diagnosis, treatment planning, or real-world clinical decision making.

---

## Feedback & Collaboration

Suggestions, improvements, and collaboration opportunities are always welcome.

Feel free to connect, contribute, or provide feedback.

---

## License

This project is intended for educational, research, and portfolio purposes.
