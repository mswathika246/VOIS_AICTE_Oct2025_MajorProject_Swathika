# 🎬 Netflix Content Analysis & Recommendation System

## 📘 Overview
This project analyzes the Netflix dataset to uncover insights about content trends, genre popularity, and global distribution.  
It also includes a simple **content-based recommender system** using TF-IDF similarity on title descriptions.

---

## 🎯 Objectives
1. Analyze the distribution of **Movies vs. TV Shows** over the years.  
2. Identify **popular genres** and how their popularity has evolved.  
3. Compare **country-wise contributions** to Netflix’s catalog.  
4. Build a **text-based recommender system** for similar shows.

---

## 📊 Expected Outcomes
- Clear understanding of Netflix’s content strategy evolution.  
- Identification of top-performing genres and categories.  
- Strategic recommendations for future content investment.

---

## 🧩 Dataset
**File:** `Netflix Dataset 1.csv`  
- Rows: 7,789  
- Columns: 11  
- Key fields: `Title`, `Category`, `Director`, `Cast`, `Country`, `Release_Date`, `Rating`, `Duration`, `Type`, `Description`.

> Source: Public Netflix dataset used for educational purposes.

---

## ⚙️ Tech Stack
- **Language:** Python 3.x  
- **Libraries:**  
  - pandas, numpy  
  - matplotlib  
  - scikit-learn  
  - IPython.display  
  - (optional) tabulate

---

## 🧠 Key Analyses
- 📈 Distribution of Movies vs. TV Shows  
- 🎭 Most common genres and their time trends  
- 🌎 Country-wise content contribution  
- 🎬 Top actors and directors  
- 🧮 Feature engineering (`duration_minutes`, `num_actors`, `is_series`)  
- 🤖 Simple TF-IDF recommender system

---

## 🧮 Recommender System Example
```python
recommend("Narcos", topn=10)
