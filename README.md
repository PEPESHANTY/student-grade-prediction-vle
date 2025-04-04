# student-grade-prediction-vle

# 📊 Student Performance Prediction using VLE Activity Logs

**UCD Module:** COMP47670 - Data Science in Python  
**Assignment:** Spring 2024/25 – Assignment 2  
**Author:** Shantanu Ramesh Bhute  
**Submission Date:** April 27, 2025

---

## 📁 Project Overview

This project analyzes Virtual Learning Environment (VLE) activity logs to explore student engagement patterns and predict final academic grades. The dataset consists of two CSV files:

- `vle_grades.csv`: Final grade of each student.
- `vle_log.csv`: Timestamped log of student activities on the platform.

The assignment is implemented in a single Jupyter Notebook, combining data preparation, feature engineering, visualization, classification, and model evaluation.

---

## 🧪 Tasks Performed

### ✅ Task 1: Data Characterisation
- Loaded and explored both datasets
- Visualized final grade distribution and activity type frequency
- Identified class imbalance and activity behavior patterns

### ✅ Task 2: ABT Creation (Analytics Base Table)
- Engineered features: total activities, quiz attempts, active days, etc.
- Merged logs with grades to form ABT
- Explored engagement vs. grade via boxplots and heatmaps

### ✅ Task 3: Classification & Evaluation
- Applied **Logistic Regression** and **Random Forest** classifiers
- Evaluated with accuracy, precision, recall, F1-score
- Visualized ROC Curves and Feature Importance
- Used **GridSearchCV** to tune Random Forest hyperparameters

---

## 📈 Key Insights

- Students with high engagement (especially quizzes and topic views) tend to perform better.
- Random Forest outperformed Logistic Regression in all key metrics.
- ROC AUC scores indicated excellent class separability, especially for identifying failing students.

---

## 🧠 Challenges Faced

- Aggregating engagement metrics meaningfully from log-level data
- Dealing with class imbalance (few fails and distinctions)
- Selecting meaningful features without data leakage

---

## 🔮 Future Work

- Use temporal patterns (early/late activity) as time-series features
- Try advanced models like XGBoost or Gradient Boosting
- Use SMOTE or class-weighting for better balance
- Integrate additional student data (assignments, attendance, etc.)

---

## 📁 Files in This Repository

| File Name                    | Description                                      |
|-----------------------------|--------------------------------------------------|
| `DS_Assignment2.ipynb`      | Main Jupyter Notebook containing all tasks       |
| `vle_log.csv`               | Raw activity logs per student                    |
| `vle_grades.csv`            | Final grades per student                         |
| `README.md`                 | Project documentation (this file)                |

---

## ✅ How to Run

1. Clone the repository  
2. Open `DS_Assignment2.ipynb` in Jupyter or Google Colab  
3. Ensure `vle_log.csv` and `vle_grades.csv` are in the same directory  
4. Run all cells in sequence to reproduce results

---

## 📬 Contact

**Shantanu Ramesh Bhute**  
📧 shantanubhute@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/shantanubhute)  
🔗 [GitHub](https://github.com/shantanubhute)

---


