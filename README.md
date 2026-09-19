# Maternal & Fetal Health Data Analysis

## 📌 Overview

This project performs Exploratory Data Analysis (EDA) on a Cardiotocographic dataset using Python.

The analysis focuses on understanding the structure and quality of the dataset, identifying missing values and outliers, exploring feature distributions, and analyzing relationships between cardiotocographic measurements.

The project was developed using Python, Pandas, NumPy, Matplotlib, Seaborn, and Jupyter Notebook.

---

## 🎯 Objectives

- Load and understand the Cardiotocographic dataset
- Explore the structure and characteristics of the data
- Perform data cleaning and preparation
- Identify missing values
- Analyze descriptive statistics
- Detect and handle outliers using the IQR method
- Study feature distributions
- Analyze relationships between numerical variables
- Examine correlations between features
- Generate meaningful visualizations from the dataset

---

## 📊 Dataset

The dataset contains **2,126 observations and 14 numerical variables**.

The variables represent cardiotocographic measurements, while `NSP` represents the fetal state classification.

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
| ASTV | Percentage of abnormal short-term variability |
| MSTV | Mean value of short-term variability |
| ALTV | Percentage of abnormal long-term variability |
| MLTV | Mean value of long-term variability |
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

### 1. Data Loading and Exploration

The dataset was loaded into a Pandas DataFrame and examined using:

- `head()`
- `shape`
- `columns`
- `info()`
- `describe()`

### 2. Data Cleaning

The dataset was examined for:

- Missing values
- Data types
- Duplicate records
- Potential outliers

### 3. Outlier Analysis

The Interquartile Range (IQR) method was used to identify potential outliers in numerical variables.

Boxplots were created to visualize the distribution and potential outliers before and after the outlier-handling process.

### 4. Distribution Analysis

Histograms and other visualizations were used to understand the distribution of numerical features.

### 5. Correlation Analysis

A correlation heatmap was created to examine relationships between numerical variables.

### 6. Feature Relationship Analysis

Scatter plots and pair plots were used to explore relationships between selected variables.

---

## 📈 Visualizations

The notebook contains several visualizations, including:

- Numerical feature boxplots
- Feature distribution histograms
- Scatter plots
- Correlation heatmap
- Pair plot
- Violin plot

All visualizations are available directly inside the Jupyter Notebook.

---

## 💡 Key Insights

- The dataset contains 2,126 observations across 14 numerical variables.
- Several variables contain missing values that require data-quality consideration.
- Numerical variables show different ranges and distributions.
- Boxplot analysis highlights potential outliers across several features.
- Correlation analysis helps identify relationships between cardiotocographic measurements.
- Feature-level visualizations provide a better understanding of the variation within the dataset.

---

## 📂 Project Structure

```text
maternal-fetal-health-analysis/
│
├── data/
│   └── Cardiotocographic.csv
│
├── notebook/
│   └── 5_EDA_assignment.ipynb
│
└── README.md
