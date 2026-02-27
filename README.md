# 🧠 Mental Health in Tech – Exploratory Data Analysis

## 📌 Project Overview

The technology industry is known for high performance expectations and fast-paced environments. While innovation drives growth, these conditions may also contribute to stress, burnout, and mental health challenges.

This project explores mental health trends among technology professionals and identifies key personal and workplace factors associated with treatment-seeking behavior.

The goal is to understand how organizational culture, policies, and individual risk factors influence mental health outcomes.

---

## 📊 Dataset Information

- **Source:** OSMI Mental Health in Tech Survey  
- **Total Respondents:** 1,259  
- **Total Features:** 27  
- **Target Variable:** `treatment` (Yes/No)  

The dataset includes demographic information, workplace environment factors, and mental health indicators.

---

## 🧹 Data Cleaning & Preprocessing

The following steps were performed to ensure data quality:

- Handled missing values using median imputation (numerical) and categorical replacement
- Standardized gender labels for consistency
- Removed unrealistic age outliers (kept ages between 15–70)
- Removed duplicate records
- Encoded categorical variables for correlation analysis

---

## 📈 Exploratory Data Analysis (EDA)

The analysis was conducted in three stages:

### 1️⃣ Univariate Analysis
- Age distribution
- Company size distribution
- Treatment distribution

### 2️⃣ Bivariate Analysis
- Treatment vs Family History
- Treatment vs Work Interference
- Treatment vs Benefits
- Treatment vs Leave Policy

### 3️⃣ Multivariate Analysis
- Correlation heatmap
- Identification of strongest features associated with treatment

---

## 🔍 Key Insights

- Nearly **50%** of respondents reported seeking mental health treatment.
- Employees with a **family history of mental illness** are significantly more likely to seek treatment.
- Mental health interference with work strongly increases treatment likelihood.
- Companies offering **mental health benefits** and supportive leave policies see higher help-seeking behavior.
- Organizational culture appears more influential than geographic location.

---

## 🏢 Business Impact

Mental health in the tech industry is not only a personal concern but also a strategic organizational factor.

Companies that:
- Provide structured mental health benefits
- Promote psychological safety
- Offer flexible leave policies

are more likely to improve employee well-being, productivity, and retention.

---

## 🤖 Next Phase: Machine Learning

The next step in this project is to build predictive models to:

- Forecast treatment likelihood
- Identify the most influential workplace factors
- Compare Logistic Regression and Random Forest performance

This will transform exploratory insights into predictive intelligence.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📄 Presentation Version

A clean presentation-style PDF report is available in the `/reports` folder.

---

## 📬 Connect

If you found this project interesting or would like to collaborate, feel free to connect with me on LinkedIn.
