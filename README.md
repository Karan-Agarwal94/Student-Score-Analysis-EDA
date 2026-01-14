# Student Score Analysis – Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-blueviolet)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-lightblue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## Project Overview

This project performs a **comprehensive Exploratory Data Analysis (EDA)** on a student performance dataset to understand how **behavioral factors, demographics, and study habits** influence academic outcomes.

The analysis focuses on identifying:

* Performance trends across subjects
* Impact of attendance, study hours, part-time work
* Subject-wise and domain-wise score clustering
* High-level academic performance drivers

---

##  Objectives

* Understand distribution and variability of student scores across subjects
* Analyze the relationship between behavioral factors and academic performance
* Engineer meaningful features to enhance interpretability
* Derive actionable insights using univariate, bivariate, and multivariate analysis

---

## Project Structure

```text
Student-Score-Analysis-EDA/
│
├── Data/
│   └── Student Scores.csv
│
├── Notebooks/
│   └── Student Score Analysis.ipynb
│
├── Reports/
│   └── Student Score Analysis (Kaggle).pdf
│
├── .gitignore
├── LICENSE
└── README.md
```

---

## Dataset Summary

* **Rows:** 2000 students
* **Columns:** 17 original features (+ engineered features)
* **Data Types:**

  * Numerical: Scores, study hours, absence days
  * Categorical: Gender, career aspiration
  * Boolean: Part-time job, extracurricular activities

The dataset is **clean (no missing values)** and suitable for direct analysis.

---

## Tools & Technologies Used

* **Python** – Core programming language
* **Pandas & NumPy** – Data manipulation and numerical analysis
* **Matplotlib & Seaborn** – Data visualization
* **Jupyter Notebook** – Interactive analysis environment

---

## Feature Engineering Highlights

To deepen analytical insights, several derived features were created:

* **Total Score** – Sum of scores across all subjects
* **Average Score** – Mean academic performance
* **Science Average** – Physics, Chemistry, Biology
* **Humanities Average** – History, Geography, English
* **Quant Average** – Mathematics & Physics
* **Performance Category** – High / Medium / Low
* **Study Efficiency Metric** – Score per study hour

These features significantly improved interpretability and multivariate analysis quality.

---

## Key Insights

### 1️⃣ Demographics

* Gender distribution is balanced and no significant performance difference between male and female students

### 2️⃣ Study Behavior

* **Weekly self-study hours** show a clear positive correlation with performance
* High performers study more consistently

### 3️⃣ Attendance

* Absence days show a **negative correlation** with scores
* Consistent attendance strongly supports academic success

### 4️⃣ Part-Time Work

* Students with part-time jobs tend to have slightly lower average scores
* Likely due to time constraints

### 5️⃣ Subject Clusters

* Science subjects are strongly correlated
* Humanities subjects form a separate performance cluster
* Math acts as a bridge subject between domains

---

## Analysis Types Covered

* Univariate Analysis
* Bivariate Analysis
* Multivariate Correlation Analysis
* Feature Validation using Correlation Heatmaps

Each analysis step is thoroughly documented with visualizations and interpretations.

---

## Conclusion

Academic performance is influenced far more by **behavioral factors** (study habits, attendance, workload balance) than demographic characteristics.

Consistent study routines and strong attendance emerge as the **most influential drivers** of success, while extracurricular activities show minimal impact.

This project demonstrates how **structured EDA and thoughtful feature engineering** can uncover meaningful patterns from educational data.

---

## Author

**Karan Agarwal**
Data Analyst / Aspiring Data Scientist

* GitHub: https://github.com/Karan-Agarwal94
* LinkedIn: www.linkedin.com/in/karan-agarwal-jain94

---

## License

This project is licensed under the **MIT License** – free to use, modify, and distribute with attribution.

---

⭐ *If you found this project insightful, feel free to star the repository!*