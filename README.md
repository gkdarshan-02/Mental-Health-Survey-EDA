# 🧠 Mental Health in Tech Workplace – Exploratory Data Analysis (EDA)

## 📌 Project Overview
Mental health is a critical yet often underrepresented aspect of workplace well-being, especially in the technology sector.  
This project performs a **comprehensive Exploratory Data Analysis (EDA)** on the *Mental Health in Tech Workplace Survey (2014)* to uncover patterns, trends, and workplace factors influencing mental health awareness and treatment-seeking behavior.

The analysis focuses on understanding how **demographics, company culture, organizational support, and workplace policies** impact mental health outcomes in the tech industry.

---

## 🎯 Business Objective
To identify key factors affecting mental health in the tech workplace and provide **data-driven insights** that help organizations:
- Improve employee well-being
- Reduce stigma
- Increase productivity and retention
- Design effective mental health policies

---

## ❓ Problem Statement
Mental health challenges are increasingly common in the tech industry, yet many organizations lack clarity on how workplace environment, benefits, and culture influence employee mental health. This project aims to analyze survey data to uncover actionable insights that enable organizations to build supportive, inclusive, and mentally healthy work environments.

---

## 📂 Dataset Information
- **Source:** Open Sourcing Mental Illness (OSMI)
- **Year:** 2014
- **Total Records:** 1,259
- **Total Features:** 27
- **Data Type:** Categorical & Numerical

### Key Features:
- Demographics: `Age`, `Gender`, `Country`
- Mental Health Indicators: `family_history`, `treatment`, `work_interfere`
- Workplace Factors: `remote_work`, `no_employees`, `tech_company`
- Organizational Support: `benefits`, `care_options`, `wellness_program`, `seek_help`
- Attitudes & Stigma: `supervisor`, `coworkers`, `mental_health_consequence`

---

## 🛠️ Data Cleaning & Preprocessing
The following preprocessing steps were applied to improve data quality:
- Removed unrealistic age values (kept ages between 10 and 100)
- Standardized gender entries (merged variations like *m, man, woman, f*)
- Handled missing values by replacing them with `"Unknown"`
- Encoded categorical variables for correlation and pair-plot analysis

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Univariate Analysis
- Majority of respondents are aged **25–40**
- Nearly **50%** of respondents have sought mental health treatment
- Many employees are unaware of mental health benefits provided by employers

### 🔹 Bivariate Analysis
- Strong relationship between **family history** and **treatment-seeking behavior**
- Females tend to seek treatment more than males
- Employees in **larger organizations** are more likely to seek treatment
- Remote work does not eliminate mental health challenges

### 🔹 Multivariate Analysis
- Pair plots and correlation heatmaps show that:
  - Mental health outcomes are **multifactorial**
  - Organizational support plays a stronger role than age or work mode
  - Fear of negative consequences suppresses openness

---

## 📈 Visualizations Used
- Count Plots (Categorical Analysis)
- Pair Plots (Feature Relationships)
- Correlation Heatmap
- Distribution Plots

Each visualization was chosen to clearly communicate insights to both technical and non-technical stakeholders.

---

## 💡 Key Insights
- Mental health issues are widespread in the tech industry
- Family history is a strong predictor of treatment-seeking
- Workplace stigma and fear still exist
- Mental health benefits are underutilized due to lack of awareness
- Remote work alone is not a complete mental health solution

---

## ✅ Business Impact
**Positive Impact**
- Enables data-driven HR and wellness strategies
- Improves employee engagement and retention
- Builds a healthier and more inclusive workplace culture

**Risks if Ignored**
- Burnout, absenteeism, and attrition
- Reduced productivity
- Negative employer branding

---

## 🧩 Conclusion
Mental health is not a peripheral issue—it is a core business concern in the tech industry. Organizations that proactively address mental health through awareness, support systems, and stigma reduction can achieve sustainable growth, higher productivity, and improved employee satisfaction.

---

## 🔧 Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Repository Structure
├── survey.csv

├── Mental Health in Tech Survey.pptx

├── Sample_EDA_Submission_Template.ipynb

├── Mental_Health_EDA.ipynb

└── README.md

---

## 🙌 Acknowledgements
- Dataset provided by **Open Sourcing Mental Illness (OSMI)**
- Inspired by real-world workplace mental health challenges

---

⭐ *If you found this project insightful, feel free to star the repository!*  
📬 *Open to feedback and collaboration.*
