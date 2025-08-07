# Employee Attrition Analysis

This project explores the factors contributing to employee attrition using data visualization and analysis techniques in Python. The goal is to understand employee behavior, identify trends, and uncover insights that may help reduce attrition rates.

---

## 📊 Project Overview

- **Notebook**: `EmployeeAttrition.ipynb`
- **Dataset**: Contains employee details like Age, Gender, Salary, City, LastWorkingDate, etc.
- **Objective**: Perform exploratory data analysis (EDA) to identify patterns and distributions that correlate with employee attrition.

---

## 🔍 Key Insights

- Created a binary target variable `target`: 
  - `1` if `LastWorkingDate` is not null (employee has left),
  - `0` otherwise.
- Discovered class imbalance: ~10% employees left (90:10 split).
- Salary is **right-skewed** (few high earners).
- Age follows a **nearly normal distribution**.
- More **males** than females in the dataset.
- Distribution by **City** shows concentration in a few key locations.

---

## 📁 Folder Structure

