## 📘 README: Student Performance Analysis Project

### 👤 By: *Quntara Ashraf*
---

## 📌 Project Overview

This project focuses on analyzing a dataset of high school students’ exam scores in math, reading, and writing, along with demographic and educational background variables. The goal is to explore **what factors influence student performance**, uncover hidden patterns using **Pandas EDA**, and communicate insights via an **interactive Power BI dashboard**.

---

## 📂 Dataset Details

* **Source**: [Kaggle – Students Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
* **Rows**: 1000 students
* **Columns**:

  * `gender`
  * `race/ethnicity`
  * `parental_level_of_education`
  * `lunch`
  * `test_preparation_course`
  * `math_score`
  * `reading_score`
  * `writing_score`

---

## 🧠 Key Objectives

1. Perform **comprehensive EDA** using Python (Pandas, Seaborn).
2. Answer 8 tricky business questions (see below).
3. Create a **clean and interactive Power BI dashboard**.
4. Present the **demographic and performance patterns** visually and effectively.

---

## 📊 Exploratory Data Analysis (EDA)

Performed in Jupyter/Colab using Python:

* Data cleaning & feature engineering:

  * Added `average_score`
  * Created `performance_category` (Low, Medium, High)
* Grouped comparisons by:

  * Gender
  * Lunch type
  * Parental education
  * Test preparation course
* Created visualizations:

  * Bar Charts
  * Violin Plots
  * Heatmaps
  * Donut Charts
  * Lollipop Chart (Power BI)

---

## ❓ Business Questions Answered

1. **Which parental education level is linked with the highest average math score?**
2. **Is there a significant score difference between males and females across all subjects?**
3. **How much does completing the test preparation course improve performance?**
4. **Which combination of gender, lunch, and test prep yields top 10% scores?**
5. **Does lunch type have a uniform impact across race/ethnicity groups?**
6. **Which subjects correlate most strongly?**
7. **Who are the top 5% performers, and what are their demographic patterns?**
8. **Can we cluster students into performance bands using Pandas logic?**

---

## 📈 Power BI Dashboard

### ✅ Key Features

* **Filters (Slicers)**:

  * Gender
  * Lunch Type
  * Test Preparation Status

* **Visualizations**:

  * **KPI Cards**: Avg Math, Reading, Writing Scores
  * **Donut Chart**: Performance Category Distribution
  * **Lollipop Chart**: Parental Education vs Average Score
  * **Stacked Column Chart**: Performance Clusters by Gender


* **Design Theme**:

  * Soft modern palette (muted reds, pinks, grays)
  * Consistent typography and clean layout
  * Visuals styled to match educational/insightful tone

---

## 📦 Files Included

| Filename                                             | Description                           |
| ---------------------------------------------------- | ------------------------------------- |
| `QuntaraAshraf_StudentPerformanceAnalysis.ipynb` | Cleaned and commented Python notebook |
| `cleaned_student_data.csv`                           | Final processed dataset               |
| `QuntaraAshraf_StudentPerformanceAnalysis_BIDashboard.pbix`  | Power BI dashboard                    |
| `README.md`                                          | This documentation file               |

---

## 🧠 Key Insights

* Completing a test prep course significantly boosts scores.
* Females outperform males in reading & writing; males excel in math.
* Parental education (Master's, Bachelor's) correlates with higher student performance.
* Strong correlation found between reading and writing scores.
* Lunch type and race/ethnicity interact in affecting score patterns.
* Top performers often have standard lunch and completed test prep.

---

## 🚀 How to Run the Project

### ▶️ Jupyter Notebook:

```bash
pip install pandas matplotlib seaborn
jupyter notebook
```

### 🖥️ Power BI:

1. Open Power BI Desktop
2. Load `cleaned_student_data.csv`
3. Explore and interact with visuals

---

## 📌 Conclusion

This project demonstrates how **data storytelling, visual design, and analytical thinking** can be combined to extract meaningful educational insights. It highlights factors that significantly impact student performance and provides a visual tool for educators, policymakers, or stakeholders to explore the data effectively.

---


