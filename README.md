# Diabetes EDA Project (BRFSS 2015 Dataset)

## 📌 Overview
This project explores the [CDC BRFSS 2015 dataset](https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system?select=diabetes_2015.csv) to analyze **patterns in diabetes prevalence** with respect to demographics, lifestyle, comorbidities, and healthcare access.  

The project is structured in **three phases**:
1. **Phase 1 – Exploratory Data Analysis (this repo):** Visualize and interpret diabetes-related trends.
2. **Phase 2 – Analytical Study:** Evaluate drug efficacy in diabetes using Pandas.
3. **Phase 3 – Predictive Modeling:** Build ML models (Scikit-learn) to predict diabetes risk.

---

## 🧩 Dataset
- **Source:** CDC BRFSS 2015 (Behavioral Risk Factor Surveillance System)
- **Size:** 250k+ respondents
- **Key Features:**
  - Demographics: Age, Income, Sex
  - Lifestyle: Smoking, Physical Activity, Diet
  - Comorbidities: Hypertension, Heart Disease, Stroke
  - Health Outcomes: BMI, Mental Health, Physical Health
  - Target: Diabetes Outcome (0 = Non-Diabetes, 1 = Prediabetes, 2 = Diabetes)

---

## 🔍 Phase 1: Exploratory Data Analysis

### 1. Diabetes Outcome Distribution
![outcome_distribution](images/outcome_distribution.png)  
📌 Most respondents are non-diabetic, with a smaller share of prediabetes and diabetes.

### 2. BMI Across Diabetes Status
![bmi_by_diabetes](images/bmi_by_diabetes.png)  
📌 Diabetics show a noticeably higher BMI distribution.

### 3. Age and Diabetes Prevalence
![age_by_diabetes](images/age_by_diabetes.png)  
📌 Diabetes prevalence increases sharply with age.

### 4. Mental and Physical Health
![mental_health](images/mental_health.png)  
![physical_health](images/physical_health.png)  
📌 Diabetics report more days of poor mental and physical health per month.

### 5. Income and General Health
![income_by_diabetes](images/income_by_diabetes.png)  
![genhlth_by_diabetes](images/genhlth_by_diabetes.png)  
📌 Diabetes is more common in lower income groups and those reporting poorer health.

### 6. Lifestyle & Comorbidities
- Smoking, alcohol consumption, physical inactivity  
- Hypertension, cholesterol, stroke, heart disease  
- Healthcare access and barriers  

Each is analyzed as **percentage distributions within diabetes groups**.

### 7. Correlation Heatmap
![heatmap](images/heatmap.png)  
📌 BMI and Age are strongly correlated with diabetes outcome.

---

## 📈 Key Insights
- **BMI and Age** are major correlates of diabetes.  
- **Mental and physical health** deteriorate in diabetics.  
- **Lower income** groups have higher diabetes prevalence.  
- **Hypertension and heart disease** are highly comorbid with diabetes.  
- Lifestyle factors (smoking, inactivity, poor diet) cluster with higher diabetes risk.  

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy)
- **Seaborn & Matplotlib** for visualization
- **Jupyter Notebook** for analysis

---

## 🚀 Next Steps
- **Phase 2:** Pandas-based analysis of drug efficacy in diabetes treatment.  
- **Phase 3:** Build predictive ML models for diabetes risk stratification.  

---

## 👨‍⚕️ About Me
I’m **Iman Taheri, M.D.**, transitioning into data science with a focus on healthcare applications.  
This project bridges **clinical expertise** and **data analysis skills**, aimed at unlocking actionable insights in medical datasets.