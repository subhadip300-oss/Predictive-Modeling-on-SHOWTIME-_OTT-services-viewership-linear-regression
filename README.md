# 📊 Predictive Modeling – OTT Viewership Analysis (ShowTime)

## 📌 Project Overview
Over-the-top (OTT) media services deliver entertainment content directly to viewers through the internet. These platforms provide on-demand access to movies, web series, and original content via websites, smartphones, tablets, and smart TVs.

OTT platforms are rapidly growing due to changing consumer behavior, shifting from traditional broadcasting subscriptions to on-demand digital streaming services. The global OTT market was valued at **$121.61 billion in 2019** and is projected to reach **$1,039.03 billion by 2027**, growing at a **CAGR of 29.4%**.

The growth accelerated further during **COVID-19**, when many OTT platforms experienced up to a **46% increase in content consumption and subscriber growth** as viewers sought more digital entertainment.

As competition increases, OTT platforms must understand what drives content viewership to optimize marketing strategies and release schedules.

---

## 🎯 Business Objective
**ShowTime**, an OTT streaming platform, wants to identify the **key factors influencing first-day content viewership**.

Understanding these drivers will help the platform:

- Improve **content release strategies**
- Optimize **marketing investments**
- Avoid **content timing clashes**
- Increase **viewer engagement and platform traffic**

To solve this problem, a **Linear Regression model** was developed to determine the variables that significantly impact **first-day content views**.

---

## 📂 Dataset Description
The dataset contains information about various factors that may influence the performance of content on the platform.

### Data Dictionary

| Variable | Description |
|---------|-------------|
| visitors | Average number of visitors (in millions) to the platform in the past week |
| ad_impressions | Number of ad impressions (in millions) across all ad campaigns |
| major_sports_event | Indicates whether a major sports event occurred on the same day |
| genre | Genre of the content |
| dayofweek | Day of the content release |
| season | Season of the content release |
| views_trailer | Number of trailer views (in millions) |
| views_content | Number of first-day content views (in millions) |

---

## 🧠 Methodology

The project followed a structured data science workflow:

1. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Correlation analysis
   - Visualization of key patterns

2. **Feature Engineering**
   - Encoding categorical variables
   - Data transformation

3. **Regression Modeling**
   - Ordinary Least Squares (OLS) Linear Regression

4. **Model Diagnostics**
   - Multicollinearity check using **Variance Inflation Factor (VIF)**
   - Assumption testing (normality and homoscedasticity)

5. **Model Evaluation**
   - Adjusted R²
   - Mean Absolute Percentage Error (MAPE)

---

## 🔍 Key Insights

- **Trailer views** and **platform visitors** strongly increase first-day viewership.
- **Saturday and Wednesday releases** drive higher engagement.
- **Summer season** positively impacts viewership.
- **Major sporting events** negatively affect audience engagement.

---

## 📈 Model Performance

- **Adjusted R²:** 0.786  
- **MAPE:** 9%

The final optimized model explains **~79% of the variance in first-day content views**, indicating strong predictive performance.

---

## 💡 Business Recommendations

- Increase **trailer marketing** to boost pre-release engagement.
- Schedule important content releases on **high-performing days (Saturday or Wednesday)**.
- Focus **content marketing campaigns during summer seasons**.
- Avoid releasing major content during **large sporting events**.

---

## 🛠 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Statsmodels (OLS Regression)  
- Matplotlib  
- Seaborn
