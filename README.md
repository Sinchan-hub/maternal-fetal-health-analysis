# Maternal & Fetal Health Data Analysis

## 📌 Overview

This project performs exploratory data analysis on a
Cardiotocographic dataset using Python.

The analysis focuses on understanding the structure and quality
of the dataset, examining feature distributions, identifying
missing values and potential outliers, and studying relationships
between numerical variables and the NSP target variable.

---

## 🎯 Objectives

- Explore the structure of the dataset
- Analyze descriptive statistics
- Identify missing values
- Check duplicate records
- Examine feature distributions
- Detect potential outliers
- Analyze correlations between variables
- Study feature distributions across NSP classes
- Extract meaningful observations from the data

---

## 📊 Dataset

The dataset contains:

- 2,126 observations
- 14 numerical variables

### Features

| Feature | Description |
|---|---|
| LB | Baseline fetal heart rate |
| AC | Accelerations |
| FM | Fetal movements |
| UC | Uterine contractions |
| DL | Light decelerations |
| DS | Severe decelerations |
| DP | Prolonged decelerations |
| ASTV | Short-term variability measure |
| MSTV | Mean short-term variability |
| ALTV | Long-term variability measure |
| MLTV | Mean long-term variability |
| Width | Histogram width |
| Tendency | Histogram tendency |
| NSP | Fetal state classification |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Analysis Performed

### 1. Data Understanding
- Dataset shape
- Column names
- Data types
- Descriptive statistics

### 2. Data Quality
- Missing-value analysis
- Duplicate detection
- Data-type inspection

### 3. Exploratory Data Analysis
- Feature distributions
- Histograms
- Boxplots
- Target distribution
- Correlation heatmap

### 4. Outlier Analysis
- IQR-based outlier detection
- Feature-level outlier summary

### 5. Target Analysis
- NSP class distribution
- Feature distributions across NSP classes

---

## 📈 Key Findings

The analysis identified differences in feature distributions,
missing values across selected variables, potential outliers,
and relationships between numerical features.

The NSP target variable contains multiple classes, providing
a basis for further classification-oriented analysis.

---

## 📂 Project Structure

```text
maternal-fetal-health-analysis/
│
├── data/
│   └── Cardiotocographic.csv
│
├── notebook/
│   └── maternal_fetal_health_eda.ipynb
│
├── images/
│   └── analysis_visualizations
│
├── README.md
├── requirements.txt
└── .gitignore# maternal-fetal-health-analysis
