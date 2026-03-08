# NETFLIX-ANALYSIS
End-to-end Data Science project on 8,804 Netflix titles —  EDA, TF-IDF NLP, KMeans Clustering &amp; Recommendation Engine  using Python, Pandas, and Scikit-learn

# 🎬 Netflix Content Intelligence Engine
### End-to-End Data Science Project

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3-green)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Project Overview

A complete end-to-end Data Science project analyzing **8,804 Netflix titles** to uncover content patterns and build a real-time recommendation engine using NLP and Machine Learning.

**Business Problem:** Netflix needs to understand its content library and recommend relevant titles to keep subscribers engaged and reduce churn.

---

## 🎯 What This Project Solves

| Problem | Solution |
|---------|----------|
| What content does Netflix have? | EDA with 8 visualizations |
| Which content is similar? | TF-IDF + Cosine Similarity |
| How to group content intelligently? | KMeans Clustering (k=8) |
| What should a user watch next? | Recommendation Engine |
| What should Netflix produce next? | Business Insights from clusters |

---

## 🛠️ Tech Stack

```
Language:     Python 3.9
Libraries:    Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
NLP:          TF-IDF Vectorization (sklearn)
ML Models:    KMeans Clustering, PCA, Cosine Similarity
Dataset:      Netflix Movies and TV Shows (Kaggle)
```

---

## 📁 Project Structure

```
netflix-content-intelligence/
│
├── Netflix_DS_Project_Vijay.ipynb  ← Main notebook (run this)
├── netflix_titles.csv              ← Dataset (8,804 titles)
├── requirements.txt                ← Required libraries
└── README.md                       ← You are here
```

---

## 🔬 Project Sections

### 1. Data Loading & First Look
- Load 8,804 Netflix titles
- Explore shape, columns, data types
- Identify missing values

### 2. Data Cleaning & Wrangling
- Fill missing values (director, cast, country, rating)
- Fix incorrect rating entries
- Parse date columns
- Extract duration as numeric

### 3. Exploratory Data Analysis (EDA)
- Movies vs TV Shows distribution
- Top countries by content volume
- Top 15 genres
- Content growth by year (2008–2021)
- Rating distribution
- Movie duration & TV show seasons analysis

### 4. Feature Engineering (NLP)
- Build content "soup" combining description + genre + type + country
- TF-IDF Vectorization → **8,804 × 5,000 feature matrix**

### 5. KMeans Clustering
- Group all 8,804 titles into **8 content clusters**
- PCA visualization (2D)
- Label each cluster by dominant genre

### 6. Recommendation Engine
- Cosine similarity matrix (**8,804 × 8,804**)
- Input any title → get top 10 similar titles with % match score
- Tested on: Stranger Things, Dark, Bird Box, Extraction

### 7. Business Insights & Dashboard
- 8 actionable insights derived from data
- Final dashboard visualization

---

## 📊 Key Findings

```
✅ Netflix is 70% Movies, 30% TV Shows
✅ United States produces most content by far
✅ 2019 was peak content year (1,606 titles)
✅ TV-MA rating dominates — Netflix targets adults
✅ Most TV shows have 1 season (limited series strategy)
✅ International content (Korean, Spanish) is surging
✅ Sci-Fi cluster is smallest — potential growth gap
✅ Comedy & Family is 2nd largest cluster
```

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/vijaydevineni/netflix-content-intelligence.git

# 2. Install requirements
pip install -r requirements.txt

# 3. Open Jupyter Notebook
jupyter notebook Netflix_DS_Project_Vijay.ipynb

# 4. Run All Cells
Kernel → Restart & Run All
```

---

## 📦 Requirements

```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=1.0.0
jupyter>=1.0.0
```

---

## 📈 Results

| Metric | Value |
|--------|-------|
| Dataset Size | 8,804 titles |
| TF-IDF Features | 5,000 |
| Clusters Found | 8 |
| Similarity Matrix | 8,804 × 8,804 |
| Recommendation Speed | < 1 second |

---

## 💡 Business Recommendations

1. **Invest in Sci-Fi** — smallest cluster, high audience demand
2. **Expand Korean & Spanish content** — International TV surging
3. **Focus on limited series** — 1-season format drives subscriptions
4. **Target adult content** — TV-MA dominates, align strategy
5. **Fill Romance content gap** — smallest cluster, underserved audience

---

## 👤 Author

**Vijay Bhaskar Devineni**
- 🎓 M.S. Information Technology Project Management — Indiana Wesleyan University (GPA: 3.57)
- 💼 Business Performance Analyst
- 🔗 [LinkedIn](https://linkedin.com/in/vijay-bhaskar-devineni-1148422ab)
- 📍 Open to Data Analyst roles across the United States

---

## 📄 Dataset Source

[Netflix Movies and TV Shows — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

*Built with Python · Pandas · Scikit-learn · Matplotlib · Seaborn*
