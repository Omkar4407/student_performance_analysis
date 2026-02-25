### Student Performance Analysis and Prediction ###

---

# Project Overview

This project analyzes student academic performance using demographic, behavioral, and academic features.
Exploratory Data Analysis (EDA) and Linear Regression were applied to identify key factors influencing student scores and to predict the average performance of students.

---

# Objectives

* Analyze factors affecting student performance
* Perform exploratory data analysis (EDA)
* Visualize relationships between student habits and marks
* Build a Linear Regression model to predict average score
* Evaluate model using MAE and R²

---

# Dataset

The dataset contains student information such as:

* Demographics: `sex`, `age`, `address`
* Study behavior: `studytime`, `failures`, `absences`
* Lifestyle: `goout`, `Walc`, `activities`, `internet`
* Academic scores: `Maths`, `Science`, `Physics`
**Source:** UCI Student Performance Dataset (via Kaggle)

A new feature **Average** was created as the target variable.

---

# Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

# Exploratory Data Analysis

The following analyses were performed:

* Correlation heatmap
* Study time vs average score
* Failures vs performance
* Absences vs performance
* Performance distribution

Key insight: Past failures and study time significantly influence student performance.

---

# Model Building

**Algorithm Used:** Linear Regression

**Train-Test Split:** 80:20

# Model Performance

* **MAE:** ~2.28
* **R² Score:** ~0.19

The model shows reasonable prediction error but limited explanatory power, indicating that student performance depends on multiple complex factors.

---

# How to Run

## Open in Colab

Click the **Open in Colab** badge at the top.

---

# Project Structure

```
student-performance-analysis/
│
├── data/
│   └── student_data.csv
│
├── notebooks/
│   └── student_performance_analysis.ipynb
│
├── images/
│
├── requirements.txt
└── README.md
```

---

# Future Improvements

* Apply Random Forest / advanced models
* Perform feature engineering
* Build interactive dashboard
* Deploy as web application

---

# Author

**Name:** Omkar Bommakanti
**Course:** SYBSc IT
**College:** St. Xaviers College, Mumbai

---

# -- If you found this project useful, consider giving it a star! -- #
