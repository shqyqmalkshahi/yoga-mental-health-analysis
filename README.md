# yoga-mental-health-analysis
Performed exploratory data analysis and machine learning on yoga, mental health, and stress trends using Python, including regression, hypothesis testing, classification, and clustering models.

# Yoga and Mental Health Analysis

##  Overview
This project explores the relationship between yoga, mental health, and stress using real-world datasets. The analysis combines exploratory data analysis (EDA), statistical testing, and machine learning techniques to understand trends and predictive factors related to mental wellness.

---

##  Problem Statement
With increasing mental health challenges worldwide, many individuals turn to accessible solutions like yoga. This project investigates whether interest in yoga is growing and how it relates to mental health awareness and stress levels.

---

##  Dataset Description
This project uses three datasets:

1. **Google Trends Data**
   - Weekly search interest for:
     - Yoga
     - Mental Health
     - Stress
   - Time-series data for 2023

2. **World Happiness Report**
   - Country-level life evaluation scores
   - Used for clustering analysis

3. **Mental Health in Tech Survey**
   - Demographics and workplace mental health data
   - Used for classification modeling

---

##  Tools & Technologies
- Python
- Pandas
- Matplotlib / Seaborn
- Scikit-learn
- Statsmodels

---

##  Key Analysis Performed

###  Exploratory Data Analysis (EDA)
- Time-series visualization of search trends
- Boxplots and distribution analysis
- Correlation and covariance analysis

 Example: Strong correlation between Mental Health and Stress (r ≈ 0.86) :contentReference[oaicite:0]{index=0}  

---

###  Hypothesis Testing
- One-tailed paired t-test
- Result:
  - t-statistic = 18.97
  - p-value ≈ 0

 Yoga search interest is significantly higher than mental health :contentReference[oaicite:1]{index=1}  

---

###  Regression Modeling
- Linear regression (Statsmodels + Scikit-learn)
- Key results:
  - Positive trend in yoga interest over time
  - Coefficient ≈ 0.18 per week
  - R² ≈ 0.187 :contentReference[oaicite:2]{index=2}  

---

###  Classification Model
- Logistic Regression
- Goal: Predict mental health treatment

**Performance:**
- Accuracy: 76%
- Strong recall for treatment prediction :contentReference[oaicite:3]{index=3}  

---

###  Clustering
- K-Means (k=3)
- Dataset: World Happiness Report

 Silhouette Score ≈ 0.55 (good clustering quality) :contentReference[oaicite:4]{index=4}  

---

##  Key Insights
- Yoga shows the most stable and consistently high interest over time  
- Mental Health and Stress are highly correlated  
- Yoga appears to play a proactive role rather than reactive  
- Workplace and demographic factors strongly influence mental health treatment  

---

##  Business Value
This project demonstrates how data science can:
- Identify wellness trends
- Support preventive healthcare strategies
- Inform workplace mental health initiatives
- Guide digital health and wellness platforms

---

##  Project Structure
- `.ipynb` → Full analysis notebook
- `.pdf` → Final report
- `.csv` → Datasets

---

##  How to Run
1. Open the notebook
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn statsmodels
