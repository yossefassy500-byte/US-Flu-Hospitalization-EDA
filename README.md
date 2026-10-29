# US-Flu-Hospitalization-EDA
# 🦠 US Influenza Hospitalization Analysis (CDC FluSurv-NET)

An end-to-end Exploratory Data Analysis (EDA) investigating seasonal patterns, demographic disparities, and viral strain prevalence in US influenza hospitalizations using CDC FluSurv-NET data.

---

## 📌 Project Overview
The objective of this project is to uncover actionable insights into influenza trends across multiple flu seasons, identifying peak hospitalization windows, high-risk demographic populations, and dominant viral strains to support healthcare resource allocation.

---

## 💡 Key Insights & Findings

### 1. Time-Series & Seasonality
* **Peak Window:** Hospitalization rates consistently peak during winter between **Weeks 50 and 6** (mid-December to mid-February).
* **Record Seasons:** **2025–26** recorded the highest early peak (~13.1 per 100k at Week 52), while **2024–25** set a late-season record (>13.5 per 100k at Weeks 5–6).
* **Anomalous Early Waves:** **2022–23** spiked exceptionally early at **Week 48** due to the post-COVID immunity gap.

### 2. Demographic Disparities
* **Age Groups:** **Elderly adults ($\ge 85$)** experience the highest hospitalization rates (>12 per 100k), followed by **Infants ($0–<1$ yr)** (~3.3 per 100k).
* **Racial Groups:** **Black / African American** individuals record the highest overall rate (>2.3 per 100k), followed by **American Indian / Alaska Native** (>2.0 per 100k), highlighting structural healthcare disparities.
* **Sex Differences:** **Females** show a slightly higher rate (~1.8 per 100k) than **Males** (~1.6 per 100k), largely driven by higher healthcare-seeking behavior.

### 3. Viral Strains
* **Dominant Virus:** **Influenza A** accounts for the vast majority of hospitalizations (>1.45 per 100k) compared to Influenza B (<0.25 per 100k).
* **Primary Subtype:** **A(H3N2)** is the leading subtype (~0.85 per 100k), followed by **A(H1N1)pdm09** (~0.62 per 100k).

---

## 🛠️ Tools & Technologies Used
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebook
