# 🌳 Day 4: Random Forest Classifier - Heart Disease Prediction

> 🗓️ **Date**: April 9, 2025  
> 🚀 **Challenge**: 30 Days of Machine Learning Projects  
> ⏰ **Note**: I'm a bit late today — returning after a long break since **Feb 20** — but excited to continue the journey! 🙌

---

## 📌 Project Overview

This project uses the **Random Forest Classifier**, a powerful ensemble learning method, to predict the **presence of heart disease** based on various medical parameters. The dataset includes features such as age, cholesterol level, chest pain type, and more.

> 🎯 **Objective**: Build a robust model to predict whether a patient has heart disease (1) or not (0).

---

## 🧠 Problem Statement

Heart disease is one of the leading causes of death globally. Early detection using machine learning models can aid in timely treatment and save lives.

This project tackles this problem using Random Forest — leveraging its ability to handle:
- Both categorical and continuous variables
- Non-linear relationships
- Feature importance analysis

---

## 📂 Dataset Details

- **File**: `heart.csv`
- **Samples**: 1025
- **Features**: 13 (excluding the target)
- **Target Variable**: `target` → `1` (Disease), `0` (No Disease)

### 🧾 Features Description

| Feature      | Description                                                  |
|--------------|--------------------------------------------------------------|
| age          | Age of the patient                                           |
| sex          | Gender (1 = Male, 0 = Female)                                |
| cp           | Chest pain type (4 values)                                   |
| trestbps     | Resting blood pressure (mm Hg)                               |
| chol         | Serum cholesterol (mg/dl)                                    |
| fbs          | Fasting blood sugar > 120 mg/dl (1 = True, 0 = False)        |
| restecg      | Resting ECG results (0,1,2)                                  |
| thalach      | Maximum heart rate achieved                                  |
| exang        | Exercise induced angina (1 = Yes, 0 = No)                    |
| oldpeak      | ST depression induced by exercise                            |
| slope        | Slope of the peak exercise ST segment                        |
| ca           | Number of major vessels (0–3) colored by fluoroscopy         |
| thal         | Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible)   |
| target       | **Target variable** (1 = Disease, 0 = No Disease)            |

---

## 📊 Exploratory Data Analysis (EDA)

- ✅ No missing values
- 🔍 Categorical vs Numerical Feature Identification
- 📈 Target Distribution (Balanced dataset)
- 📌 Top 15 Correlated Features (e.g., `cp`, `thalach`, `oldpeak`)

## 🤖 Model: Random Forest Classifier

- ✅ **Library**: `sklearn.ensemble.RandomForestClassifier`
- 🌲 **n_estimators**: 100
- ✂️ **Train-Test Split**: 80% training / 20% testing

### 🧪 Performance Metrics

| Metric     | Value |
|------------|--------|
| Accuracy   | 100%   |
| Precision  | 1.00   |
| Recall     | 1.00   |
| F1-Score   | 1.00   |
| AUC Score  | 1.00   |

> ⚠️ Model might be **overfitting** — training and testing accuracy are both perfect.


## 🧰 Tech Stack

- Python 🐍
- Pandas & NumPy
- Seaborn & Matplotlib
- Scikit-learn (RandomForest, metrics, train_test_split)

---
