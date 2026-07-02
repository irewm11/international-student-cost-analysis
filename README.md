# international-student-cost-analysis
Machine learning based price-performance analysis of study abroad destinations.
# 🌍 International Student Routes and Cost Analysis

## Which Country Is Really Advantageous?

### Price-Performance Analysis for Studying Abroad

## 📌 Project Overview

Choosing a country for international education depends not only on academic opportunities but also on financial sustainability. Many students focus solely on tuition fees while overlooking hidden costs such as accommodation and living expenses.

This project analyzes the economic attractiveness of different study destinations by combining educational costs, housing expenses, and quality-of-life indicators. Using machine learning techniques, countries are grouped according to their cost-performance profiles to help students make more informed decisions.

---

## 🎯 Problem Statement

Students planning to study abroad often underestimate the impact of hidden costs such as rent and living expenses. The lack of a comprehensive financial comparison between countries makes it difficult to perform realistic return-on-investment (ROI) analyses.

This project aims to provide a data-driven approach for identifying the most advantageous study destinations worldwide.

---

## 📊 Dataset

The dataset includes information from **71 countries** and contains the following features:

* Tuition Fees
* Rent Index
* Cost of Living Index
* Number of Universities
* Country Popularity Index
* Number of International Students
* Total Annual Cost

By combining these metrics, a more realistic representation of studying abroad expenses was created.

---

## 🔍 Data Preprocessing

The following preprocessing steps were applied:

* Cleaning column names and formatting inconsistencies
* Removing missing values using `dropna()`
* Preserving natural economic differences between countries
* Standardizing numerical variables using `StandardScaler`

Feature scaling was particularly important because K-Means clustering is distance-based and highly sensitive to differences in magnitude between variables.

---

## 🤖 Machine Learning Approach

Since the dataset does not contain predefined labels, an unsupervised learning approach was selected.

### Algorithm Used

* K-Means Clustering

### Determining Optimal Number of Clusters

* Elbow Method

The optimal number of clusters was found to be **K = 3**.

Countries were grouped into:

1. Elite Routes
2. Price/Performance Routes
3. Budget-Friendly Routes

---

## 📈 Correlation Analysis Findings

* **Total Annual Cost ↔ Tuition Fees:** 0.98
* **Total Annual Cost ↔ Rent Index:** 0.83
* **Popularity Index ↔ Number of Universities:** 0.81

The analysis shows that tuition fees and housing costs are the main drivers of international education expenses.

---

## 📊 Key Insights

### High-Cost Leaders

* United States
* United Kingdom
* Australia

### Best Price/Performance Destinations

* Germany
* Japan
* France

### Main Conclusion

High quality of life does not always require high accommodation costs. Strategic country selection can significantly optimize student budgets.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Excel
* PowerPoint

---

## 📌 Machine Learning Techniques

* K-Means Clustering
* StandardScaler
* Correlation Analysis
* Exploratory Data Analysis (EDA)
* Feature Importance Analysis

---

## 📷 Dashboard

The project includes an interactive dashboard for visualizing:

* Cost comparisons
* Country clusters
* Popularity trends
* Price-performance opportunities

---

## 👩‍💻 Author

**Müesser İrem Gecici**
Manisa Celal Bayar University
Big Data Analytics Student
