# ⚽ Football Player Data Analytics & Cleaning Pipeline

## 📌 Overview

This project demonstrates a **complete real-world data cleaning and analytics pipeline** using a deliberately messy football dataset. It simulates industry-level data challenges and showcases how to transform raw, inconsistent data into **analysis-ready insights**.

The workflow covers everything from **data ingestion and quality auditing** to **feature engineering, visualization, and final reporting**.

---

## 🎯 Objectives

* Handle real-world messy data scenarios
* Perform systematic data quality assessment
* Clean and standardize inconsistent datasets
* Generate meaningful football performance metrics
* Deliver insights through visual analytics

---

## 📂 Dataset Description

### 📊 `football_players_UNCLEAN.xlsx`

Contains data for **40 top-tier football players** (e.g., Messi, Haaland, Mbappé) across two sheets:

#### 🔹 PlayerStats_RAW

Intentionally unclean dataset with real-world issues:

* Trailing metadata rows (e.g., *Source, Notes*)
* Blank rows within data
* Duplicate records and inconsistent naming (case variations)
* Column naming inconsistencies
* Numeric values stored as strings
* Impossible values (e.g., negative goals, extreme shots)
* ~13% randomly distributed missing values

---

#### 🔹 Data Dictionary

* Detailed column descriptions
* Expected value ranges
* Documented data issues

---

## 📓 Notebook: `football_analytics.ipynb`

A structured **7-stage data pipeline**:

---

### 🔹 1. Data Ingestion

* Automatic header detection
* Schema inspection and validation

---

### 🔹 2. Data Quality Audit

* Identification of all major issue types:

  * Missing values
  * Duplicates
  * Invalid entries
  * Formatting inconsistencies

---

### 🔹 3. Data Cleaning

* Removal of metadata rows and blanks
* Standardization of column names
* Conversion of data types
* Handling missing values
* Correction/removal of outliers

---

### 🔹 4. Feature Engineering

Creation of **12 advanced metrics**, including:

* Goals per 90 minutes
* Shot conversion rate
* Value-for-Money (VfM)
* Efficiency ratios

---

### 🔹 5. Exploratory Data Analysis (EDA)

* Distribution analysis
* Position-wise comparisons
* Box plots and statistical summaries

---

### 🔹 6. Advanced Visualizations

* Correlation heatmap
* Bubble scatter plots
* Radar charts for player comparison
* Value-for-Money rankings

---

### 🔹 7. Final Summary

* End-to-end pipeline recap
* Clean dataset export (CSV)
* Key insights consolidated

---

## 🧠 Key Highlights

* Simulates **real industry data problems**
* End-to-end **data preprocessing pipeline**
* Combines **data cleaning + analytics + visualization**
* Produces **business-relevant insights** (player efficiency, value metrics)

---

## 🏗️ Tech Stack

* **Language:** Python
* **Libraries:**

  * Pandas, NumPy
  * Matplotlib, Seaborn
  * Scikit-learn (optional analytics)
* **Environment:** Jupyter Notebook

---


## 📈 Outcomes

* Successfully cleaned a highly inconsistent dataset
* Generated meaningful performance metrics
* Identified top-performing players using advanced analytics
* Delivered structured, reproducible data pipeline

---

## 🚀 Future Enhancements

* Integrate real-time football datasets (APIs)
* Build predictive player performance models
* Deploy dashboard using Streamlit/Power BI
* Extend analysis to team-level insights

---


