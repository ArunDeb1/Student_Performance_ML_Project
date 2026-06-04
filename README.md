# Student_Performance_ML_Project

# 🎓 Student Risk Prediction System

### AI-Powered Early Warning System for Identifying Academically At-Risk Students

---

## 🎯 Problem Statement

> Develop a Machine Learning system to identify weak students early and enable timely academic intervention before performance declines.

---

## 📖 Project Overview

Student performance is influenced by multiple factors such as attendance, study habits, motivation, academic history, family support, and access to learning resources.

This project aims to build an **Early Warning System** that identifies students at risk of poor academic performance before their next examination. By leveraging Machine Learning, the system can help educational institutions take proactive measures, provide targeted support, and improve overall student success rates.

---

## 🚀 Project Goals

✔ Identify weak students before examinations

✔ Understand the key drivers behind academic performance

✔ Build interpretable and high-performing Machine Learning models

✔ Detect students requiring academic intervention

✔ Evaluate model fairness and reduce prediction bias

✔ Deploy a production-ready prediction system

✔ Enable data-driven decision-making for educators

---

## 📊 Dataset Overview

The dataset contains information about student demographics, academic performance, study behavior, learning environment, and family background.

### Dataset Characteristics

| Category | Description |
|-----------|------------|
| Domain | Education Analytics |
| Problem Type | Classification & Regression |
| Target Variable | Weak Student / Exam Score |
| Records | 6,607 Students |
| Features | 20+ Variables |
| Goal | Identify academically weak students |

---

## 🗂️ Dataset Features

### 📚 Academic Performance

- Previous Scores
- Exam Score
- Hours Studied
- Attendance

### 🎓 Learning Support

- Tutoring Sessions
- Teacher Quality
- Access to Resources

### 🧠 Student Behavior

- Motivation Level
- Peer Influence
- Internet Access
- Extracurricular Activities

### 👨‍👩‍👧 Family & Social Factors

- Parental Involvement
- Parental Education Level
- Family Income

### 🏫 Student Demographics

- Gender
- School Type
- Learning Disabilities
- Distance from Home

### ❤️ Lifestyle Factors

- Sleep Hours
- Physical Activity

---

## 🔍 Core Business Questions

This project seeks to answer:

1. Which students are most likely to become academically weak?
2. Which factors have the strongest influence on academic performance?
3. Can weak students be identified before examination results are released?
4. Which students should be prioritized for intervention programs?
5. How can institutions improve academic outcomes using data?

---

## 💡 Core Insights from EDA

### 🎯 Academic History Matters

Students with lower previous scores show a significantly higher likelihood of becoming weak students.

### 📉 Attendance Is a Major Risk Indicator

Low attendance demonstrates a strong relationship with poor academic performance and student weakness. :contentReference[oaicite:0]{index=0}

### 📚 Study Habits Drive Success

Students with:

- Higher study hours
- Better motivation levels
- More tutoring sessions

tend to perform better academically. :contentReference[oaicite:1]{index=1}

### 👨‍👩‍👧 Support Systems Matter

Parental involvement and access to educational resources contribute positively to student outcomes. :contentReference[oaicite:2]{index=2}

### ⚠️ Potentially Weak Predictors

Some variables show limited influence on academic performance:

- Gender
- School Type
- Sleep Hours
- Physical Activity

These features will undergo further validation during model development. :contentReference[oaicite:3]{index=3}

---

## 🏗️ Machine Learning Pipeline

```text
Raw Data
    ↓
Data Cleaning
    ↓
Exploratory Data Analysis
    ↓
Feature Engineering
    ↓
Data Preprocessing
    ↓
Model Training
    ↓
Model Evaluation
    ↓
Bias & Fairness Assessment
    ↓
Deployment
```

---

## 🧪 Feature Engineering (Planned)

Custom features to improve model performance:

- Attendance Risk Score
- Academic Consistency Index
- Engagement Score
- Learning Support Index
- Historical Performance Band
- Student Risk Category
- Intervention Priority Score

---

## 🤖 Machine Learning Models

### Classification Models

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier
- LightGBM
- CatBoost

### Regression Models

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- XGBoost Regressor

---

## 📏 Evaluation Metrics

### Classification

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

### Regression

- RMSE
- MAE
- MSE
- R² Score

---

## ⚖️ Responsible AI & Fairness

To ensure ethical predictions, fairness analysis will be performed across:

- Gender
- Family Income
- Learning Disabilities
- School Type
- Parental Education Level

The objective is to identify weak students fairly without introducing demographic or socioeconomic bias. :contentReference[oaicite:4]{index=4}

---

## 🛠️ Tech Stack

| Category | Tools |
|-----------|---------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn, XGBoost, LightGBM, CatBoost |
| Model Evaluation | Scikit-Learn Metrics |
| Deployment | FastAPI, Docker |
| Cloud | AWS |
| Version Control | Git, GitHub |

---

## 📂 Project Structure

```text
Student-Risk-Prediction-System/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── EDA.ipynb
│   ├── Feature_Engineering.ipynb
│   ├── Model_Training.ipynb
│
├── src/
│   ├── preprocessing/
│   ├── features/
│   ├── training/
│   ├── evaluation/
│
├── models/
│
├── deployment/
│
├── reports/
│
└── README.md
```

---

## 📅 Project Roadmap

| Phase | Status |
|---------|---------|
| Business Understanding | ✅ Completed |
| Data Understanding | ✅ Completed |
| Data Cleaning | ✅ Completed |
| Exploratory Data Analysis | ✅ Completed |
| Feature Engineering | 🔄 In Progress |
| Data Preprocessing | ⏳ Planned |
| Model Development | ⏳ Planned |
| Model Evaluation | ⏳ Planned |
| Bias & Fairness Check | ⏳ Planned |
| API Development | ⏳ Planned |
| Cloud Deployment | ⏳ Planned |

---

## 🎯 Expected Impact

📈 Improve student success rates

📉 Reduce academic failure risk

🎯 Enable targeted intervention programs

📚 Support educators with actionable insights

🤖 Build a scalable AI-powered academic support system

---

## 👨‍💻 Author

### Arunoday Debnath

**Aspiring Machine Learning Engineer | Data Scientist | Business Analyst**

Passionate about solving real-world problems using Data Science, Machine Learning, and AI-driven decision systems.
