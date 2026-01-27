# CardioPulse AI  
## Data-Driven Heart Disease Risk Analysis System

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Status](https://img.shields.io/badge/Project-Academic-success)
![Domain](https://img.shields.io/badge/Domain-Healthcare%20AI-red)

CardioPulse AI is an end-to-end data science and machine learning project focused on analyzing clinical data and predicting heart disease risk. The system integrates data preprocessing, exploratory data analysis, statistical validation, predictive modeling, and interactive visual analytics to deliver both accurate predictions and meaningful healthcare insights.

This project was developed as a **team academic project** to simulate a real-world healthcare data science workflow.

---

## 📌 Project Objectives

- Understand and clean real-world cardiovascular health data  
- Perform deep exploratory data analysis (EDA)  
- Statistically validate relationships between clinical features and heart disease  
- Build and compare machine learning models  
- Evaluate model performance using standard medical ML metrics  
- Identify key clinical risk factors  
- Design interactive dashboards for insights  
- Develop an integrated heart disease analysis system  

---

## 🧠 Key Features

- ✔ End-to-end data science pipeline  
- ✔ Advanced data preprocessing (missing values, outliers, encoding, scaling)  
- ✔ Exploratory Data Analysis (EDA) with visual insights  
- ✔ Chi-square tests for categorical feature validation  
- ✔ Machine learning models: Logistic Regression & Random Forest  
- ✔ Performance evaluation: Accuracy, Confusion Matrix, ROC-AUC  
- ✔ Feature importance analysis  
- ✔ Interactive Power BI dashboard  
- ✔ Integrated CardioPulse AI system interface  

---

## 📊 Dataset Information

- **Source:** Heart Failure Prediction Dataset (Kaggle)  
- **Initial Samples:** 918  
- **Final Samples (after cleaning):** 836  
- **Target Variable:** HeartDisease (0 = No, 1 = Yes)  

**Main features include:**  
Age, Sex, Chest Pain Type, Resting BP, Cholesterol, Fasting Blood Sugar, ECG Results, Max Heart Rate, Exercise-Induced Angina, Oldpeak, ST Slope.

---

## 🔎 Methodology

### 1. Data Preprocessing
- Replaced invalid zero values  
- Outlier detection and removal using IQR  
- One-hot encoding of categorical features  
- Feature scaling using StandardScaler  

### 2. Exploratory Data Analysis
- Histograms and boxplots  
- Disease vs non-disease comparisons  
- Correlation heatmaps  
- Categorical distribution analysis  

### 3. Statistical Analysis
- Chi-square tests to evaluate associations between categorical features and heart disease  

### 4. Model Development
- Logistic Regression (baseline model)  
- Random Forest Classifier (final model)  

### 5. Model Evaluation
- Accuracy  
- Confusion matrix  
- ROC–AUC curve  
- Cross-validation  
- Feature importance  

---

## 🏆 Results

| Model | Accuracy | ROC-AUC |
|------|----------|----------|
| Logistic Regression | ~89% | 0.953 |
| Random Forest | ~92% | 0.959 |

✔ Random Forest achieved the best overall performance  
✔ ST Slope, MaxHR, Cholesterol, Age, and Chest Pain Type were among the strongest predictors  

---

## 📈 Power BI Dashboard

The Power BI dashboard enables:

- KPI summaries  
- Clinical data exploration  
- Categorical risk factor analysis  
- Correlation visualizations  
- Model performance tracking  
- Feature importance interpretation  

It allows interactive filtering and intuitive analysis of cardiovascular risk patterns.

---

## 🖥 System Workflow

Data Collection → Preprocessing → EDA → Statistical Testing →  
Model Training → Evaluation → Visualization → User Interaction

This creates a complete healthcare analytics and decision-support workflow.

---

## 🛠 Tech Stack

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Machine Learning:** Logistic Regression, Random Forest  
- **Visualization:** Power BI  
- **Tools:** Jupyter Notebook, GitHub  
- **Domain:** Data Science, Healthcare Analytics, AI  

---

## 👥 Team Members

- Abdul Ahad  
- Muhammad Wafa Abbas  
- Abdul Rehman  

Academic Project — Department of Computer Science

---

## 🚀 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/AbdulAhad56/CardioPulse-AI.git

# Navigate to project folder
cd CardioPulse-AI

# Install dependencies
pip install -r requirements.txt

# Run notebooks
jupyter notebook
```
---

## 🎯 Learning Outcomes

- Healthcare data preprocessing  
- Applied statistical testing  
- Machine learning model development  
- Medical ML evaluation methods  
- Feature importance interpretation  
- Visual analytics using Power BI  
- End-to-end system integration  

---

## ⚠ Disclaimer

This project is for **educational and research purposes only**.  
It is **not intended** for medical diagnosis or real-world clinical use.

---

## 📬 Feedback & Collaboration

Suggestions, improvements, and collaboration opportunities are welcome.  
Feel free to connect and share feedback.

---


## 📄 License

This project is released for **educational and portfolio use**.

---

