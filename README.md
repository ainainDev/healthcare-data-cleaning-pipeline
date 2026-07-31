# 🏥 Healthcare Data Cleaning & Data Quality Pipeline

A complete end-to-end healthcare data cleaning project built using **Python** and **Pandas**. This project focuses on identifying and resolving real-world data quality issues across multiple healthcare datasets while preparing them for downstream analytics and machine learning applications.

---

## 📌 Project Overview

Healthcare datasets often contain missing values, inconsistent formats, duplicate records, invalid entries, and data spread across multiple tables.

This project demonstrates a structured data wrangling workflow to transform raw clinical datasets into clean, analysis-ready data.

---

## 🎯 Objectives

- Clean patient demographic data
- Standardize inconsistent values
- Handle missing information
- Validate data integrity
- Remove duplicates
- Correct invalid records
- Merge related healthcare datasets
- Prepare data for analysis

---

## 📂 Datasets Used

- **patients.csv**
- **treatments.csv**
- **treatments_cut.csv**
- **adverse_reactions.csv**

---

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## 📊 Data Cleaning Tasks

### Patient Dataset

- Missing value treatment
- Email validation
- Phone number extraction
- ZIP code formatting
- Data type conversion
- Duplicate removal
- Invalid value correction

### Treatment Dataset

- Merge related patient records
- Handle duplicate treatments
- Standardize treatment information

### Adverse Reaction Dataset

- Data consistency checks
- Merge with patient information
- Missing value handling

---

## 🔍 Data Quality Checks

The project addresses common data quality dimensions including:

- Completeness
- Accuracy
- Consistency
- Validity
- Uniqueness
- Integrity

---

## 📈 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Exploratory Data Preparation
- Data Validation
- Regular Expressions (Regex)
- Feature Engineering
- Data Transformation
- Dataset Merging
- Missing Value Handling

---

## 📁 Project Structure

```
healthcare-data-cleaning-pipeline/
│
├── datasets/
│   ├── patients.csv
│   ├── treatments.csv
│   ├── treatments_cut.csv
│   └── adverse_reactions.csv
│
├── notebooks/
│   └── healthcare_data_cleaning.ipynb
│
├── README.md
│
└── LICENSE
```

---

## 🚀 Key Learning Outcomes

- Cleaning messy healthcare datasets
- Building reusable data preprocessing workflows
- Applying regex for text extraction
- Performing multi-table joins
- Preparing datasets for analytics and machine learning

---

## 📌 Future Improvements

- Automate validation rules
- Create reusable cleaning functions
- Generate data quality reports
- Build an interactive dashboard
- Package the pipeline as a Python module

---

## ⭐ If you found this project useful, consider giving it a star!
