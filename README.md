# 🧬 Colorectal Cancer Survival Analysis Framework

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Lifelines](https://img.shields.io/badge/Lifelines-Survival%20Analysis-green.svg)](https://lifelines.readthedocs.io/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange.svg)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue.svg)](https://pandas.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A comprehensive survival analysis framework for investigating prognostic factors affecting disease-free survival (DFS) in colorectal cancer patients. The project combines classical survival analysis techniques, feature selection, dimensionality reduction, and exploratory data analysis to identify factors associated with patient outcomes.

---

## 📖 Overview

This project applies statistical and machine learning techniques to analyze colorectal cancer patient data and evaluate the impact of demographic, clinical, and treatment-related variables on survival outcomes.

The framework utilizes:

* Kaplan-Meier Survival Analysis
* Cox Proportional Hazards Modeling
* Feature Selection
* Principal Component Analysis (PCA)
* Exploratory Data Analysis (EDA)
* Survival Curve Comparison

The goal is to identify meaningful predictors of patient survival and provide insights into disease progression and treatment effectiveness.

---

## 🎯 Project Objectives

* Analyze disease-free survival patterns in colorectal cancer patients.
* Evaluate the impact of clinical and demographic variables on survival outcomes.
* Identify significant prognostic factors.
* Visualize survival probabilities across patient groups.
* Apply dimensionality reduction for pattern discovery.
* Support clinical research and healthcare decision-making.

---

## ✨ Key Features

### 📊 Survival Analysis

* Kaplan-Meier survival estimation
* Survival probability visualization
* Group-based survival comparison

### 🧬 Clinical Data Exploration

* Patient demographic analysis
* Tumor location assessment
* Treatment effectiveness evaluation

### 🔍 Feature Selection

* ANOVA F-score feature ranking
* Identification of influential variables

### 📉 Dimensionality Reduction

* Principal Component Analysis (PCA)
* Visualization of latent patient characteristics

### 📈 Exploratory Data Analysis

* Distribution analysis
* Missing value assessment
* Statistical summaries

---

## 🏗️ Framework Architecture

```text
Colorectal Cancer Dataset
              │
              ▼
       Data Cleaning
              │
              ▼
    Feature Engineering
              │
              ▼
   Exploratory Analysis
              │
              ▼
      Feature Selection
              │
              ▼
   Kaplan-Meier Analysis
              │
              ▼
   Cox Survival Modeling
              │
              ▼
      PCA Analysis
              │
              ▼
     Survival Comparison
              │
              ▼
      Clinical Insights
```

---

## 📂 Dataset Variables

| Variable    | Description                    |
| ----------- | ------------------------------ |
| Age         | Patient age at diagnosis       |
| Dukes Stage | Cancer stage classification    |
| Gender      | Patient sex                    |
| Location    | Tumor location                 |
| DFS Months  | Disease-free survival duration |
| DFS Event   | Recurrence or event indicator  |
| Adj Radio   | Adjuvant radiotherapy          |
| Adj Chem    | Adjuvant chemotherapy          |

---

## 🔬 Methodology

### 1. Data Preprocessing

The framework performs:

* Missing value removal
* Feature renaming and cleaning
* Data formatting
* Categorical variable encoding

---

### 2. Kaplan-Meier Survival Analysis

Kaplan-Meier estimators are used to evaluate survival probabilities over time.

Applications include:

* Overall survival estimation
* Age-based survival analysis
* Tumor location comparison
* Patient subgroup evaluation

---

### 3. Feature Selection

ANOVA-based feature selection is applied to determine which clinical variables contribute most to survival outcomes.

Analyzed factors include:

* Age
* Cancer stage
* Gender
* Tumor location
* Treatment variables

---

### 4. Principal Component Analysis (PCA)

PCA reduces dataset dimensionality and identifies latent patterns among patients.

Benefits include:

* Noise reduction
* Feature interpretation
* Survival group discovery
* Patient clustering

---

### 5. Survival Group Comparison

Patients are grouped according to:

* Tumor location
* PCA-derived characteristics
* Clinical attributes

Kaplan-Meier curves are generated to compare survival distributions between groups.

---

## 📊 Analysis Performed

### Overall Survival Analysis

Evaluates disease-free survival trends across the entire patient population.

### Age-Based Survival Analysis

Investigates the relationship between age and survival probability.

### Tumor Location Analysis

Compares survival outcomes between:

* Rectum tumors
* Other tumor locations

### Treatment Impact Analysis

Examines the effect of:

* Radiotherapy
* Chemotherapy

on disease-free survival.

---

## 📈 Visualization Outputs

The framework generates:

* Kaplan-Meier Survival Curves
* Feature Importance Charts
* Histograms and Distribution Plots
* PCA Component Analysis
* Survival Group Comparisons
* Clinical Variable Visualizations

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Lifelines
* Scikit-Learn
* Matplotlib
* Seaborn

---

## 🔍 Research Significance

Survival analysis plays a critical role in understanding disease progression and identifying factors associated with patient outcomes.

This framework provides:

✔ Clinical outcome assessment

✔ Prognostic factor identification

✔ Treatment effectiveness evaluation

✔ Data-driven healthcare insights

✔ Research-oriented survival modeling

The methodology can support biomedical research, healthcare analytics, and evidence-based clinical decision-making.

---

## 🚀 Future Enhancements

Potential improvements include:

* Deep Survival Models
* Random Survival Forests
* Time-Dependent Cox Models
* Deep Learning for Prognosis Prediction
* Multi-Center Clinical Data Integration
* Explainable AI for Survival Analysis
* Interactive Clinical Dashboards

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed as a research-oriented framework for colorectal cancer survival analysis, prognostic factor identification, and healthcare analytics.
