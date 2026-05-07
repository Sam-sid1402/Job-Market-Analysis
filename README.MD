# Job Market Analysis Project

## Overview

This project analyzes job market trends using scraped job posting data.  
The analysis focuses on:

- remote work trends
- salary estimation
- seniority distribution
- hiring activity
- geographic patterns

The project includes:
- data cleaning
- feature engineering
- exploratory data analysis (EDA)
- SQL export
- Tableau dashboards
- basic machine learning

---

# Tools & Technologies

- Python
- Pandas
- NumPy
- Regex
- Matplotlib
- Seaborn
- SQLite
- Scikit-learn
- Tableau

---

# Project Workflow

## 1. Data Cleaning

The dataset required several preprocessing steps:

- handling missing values
- removing duplicates
- standardizing text columns
- cleaning salary information
- fixing inconsistent categories

## 2. Feature Engineering

Several new analytical features were created:

| Feature | Description |
|---|---|
| `seniority_level` | extracted from job title |
| `remote_job` | detected using title, location, and remote indicators |
| `salary_estimate` | estimated yearly salary from raw salary data |
| `final_salary` | combined salary feature using fallback logic |

## 3. Exploratory Data Analysis

The analysis explored:
- remote vs onsite jobs
- salary distributions
- hiring activity
- top companies
- seniority trends

## 4. Tableau Dashboards

Two dashboards were created:

### Dashboard 1 — Job Market Overview
- total jobs
- remote work share
- top companies
- seniority distribution

### Dashboard 2 — Salary Analysis
- salary distribution
- remote vs salary
- top paying roles

## 5. Machine Learning

A simple Random Forest regression model was trained to predict salaries using structured job posting features.

The ML section was included as a demonstration of a basic machine learning workflow rather than a production-ready predictive system.

---

# Project Structure

```text
Job-Market-Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── sql/
│
├── notebooks/
│
├── README.md
│
├── requirements.txt
