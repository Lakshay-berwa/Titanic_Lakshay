# Titanic Survival Analysis Project

This project is based on Exploratory Data Analysis (EDA) performed on the **Titanic dataset**. It includes data cleaning, visualization, and survival pattern insights. A CSV dataset and Jupyter Notebook are used for analysis.

---

## 📌 Project Overview

The goal of this project is to analyze factors affecting passenger survival on the Titanic using Python libraries like **Pandas, NumPy, Matplotlib, and Seaborn**.

We explore:

* Data structure and summary
* Missing value handling
* Feature engineering (age groups, etc.)
* Data visualizations (countplots, heatmaps, bar charts)
* Survival rate insights

---

## 📁 Files Included

* **Titanic_Lakshay.ipynb** – Main analysis notebook
* **titanic_dataset.csv** – Converted dataset (as per user request)
* **README.md** – Project documentation

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Key Steps of Analysis

### 1. Load Dataset

```
import pandas as pd
import seaborn as sns
import numpy as np

titanic = sns.load_dataset('titanic')
```

### 2. Data Cleaning

* Handling null values
* Dropping unnecessary columns
* Converting datatypes

```
titanic.dropna(inplace=True)
```

### 3. Exploratory Data Analysis

* Countplot of survivors
* Age distribution
* Heatmap of correlations
* Bar graph by age group vs. survival

### 4. Feature Engineering

```
titanic['age_group'] = pd.cut(titanic['age'], bins=[0,12,18,35,60,80], 
                              labels=['Child','Teen','Adult','Middle Age','Senior'])
```

### 5. Visualizations

* Survival by class
* Survival by gender
* Survival by age group

---

## 📊 Major Insights

* Females had
