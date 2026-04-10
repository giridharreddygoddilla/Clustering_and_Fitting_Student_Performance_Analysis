# 🎓 Student Performance Analysis using Clustering & Regression

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikit-learn">
  <img src="https://img.shields.io/badge/Type-EDA%20%7C%20Clustering%20%7C%20Regression-green?style=for-the-badge">
</p>

---

## 📌 Project Overview

This project explores student academic performance using a combination of **exploratory data analysis, clustering, and regression modelling**.

The goal was to understand:
- how students perform across different subjects  
- how strongly reading and writing skills are connected  
- whether students can be grouped into meaningful performance categories  

Rather than treating scores as isolated numbers, this analysis focuses on identifying **patterns and relationships** that could support better educational insights.

---

## 🎯 Objectives

- Analyse score distributions across subjects  
- Understand relationships between academic skills  
- Segment students into performance groups using clustering  
- Explore predictive relationships between reading and writing  

---

## 📊 Dataset

- **Source:** Kaggle  
- **Size:** 1000 student records  
- **Features:**
  - Gender  
  - Race/Ethnicity  
  - Parental level of education  
  - Lunch type  
  - Test preparation course  
  - Math, Reading, Writing scores  

---

## ⚙️ Approach

### 🔹 Data Preparation
- Cleaned column names for consistency  
- Encoded categorical variables for analysis  
- Checked for missing values (none found)  
- Applied **StandardScaler** for clustering  

---

### 🔹 Exploratory Analysis
Created key visualisations to understand the data:
- Histogram → distribution of math scores  
- Scatter plot → reading vs writing relationship  
- Correlation heatmap → feature relationships  
- Elbow plot → optimal number of clusters  

---

### 🔹 Clustering (K-Means)
- Applied K-Means on scaled scores (math, reading, writing)  
- Used elbow method to determine optimal clusters  
- Identified **3 meaningful student groups**:
  - High-performing students  
  - Average performers  
  - Lower-performing students needing support  

---

### 🔹 Regression Analysis
- Built a **linear regression model**  
- Used reading score to predict writing score  

📈 Result:
- Strong positive relationship between reading and writing  
- Reading performance explains a large portion of writing outcomes  

---

## 📈 Key Insights

- Most students score in the mid-to-high range in mathematics  
- Reading and writing scores are highly correlated  
- Students who completed test preparation generally perform better  
- Clustering reveals clear academic performance groups  
- Regression confirms strong predictive relationship between literacy skills  

---

## 📊 Visualisations

- 📌 Score distribution (histogram)  
- 📌 Reading vs writing relationship (scatter plot)  
- 📌 Feature relationships (correlation heatmap)  
- 📌 Optimal clusters (elbow plot)  
- 📌 Student segmentation (cluster plot)  
- 📌 Regression line for prediction  

---

## 🧠 What this project shows

- How **EDA + ML** can uncover patterns in education data  
- How clustering can help identify **student performance groups**  
- How simple models can still provide **strong insights**  
- How data can support **better academic decision-making**  

---

## ⚠️ Limitations

- Categorical variables were encoded simply (may affect interpretation)  
- Regression model uses only one feature (reading score)  
- Clustering is exploratory and depends on chosen parameters  
- Results should be interpreted with real-world context  

---

## 🔮 Future Improvements

- Use one-hot encoding for categorical variables  
- Add train/test split for regression evaluation  
- Evaluate clusters using silhouette score  
- Explore multi-variable regression models  
- Compare with other clustering methods (DBSCAN, hierarchical clustering)  

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📂 Project Structure
Data/

Notebook/

Report/

README.md

## 💼 Why this matters

This project demonstrates how data analysis can go beyond numbers to uncover meaningful patterns in student performance.

In real-world applications, this type of analysis could help:
- identify students who need additional support
- understand learning patterns
- improve educational strategies

## ⭐ Final Note

This project reflects my ability to:

- clean and analyse real-world data
- apply machine learning techniques
- interpret results in a meaningful way
