# 📊 Streaming Service User Analysis - Excel Dashboard Project

This project demonstrates advanced **Microsoft Excel data analysis** and dashboard creation using a synthetic dataset of users from a streaming service platform. The goal is to extract meaningful insights, identify user behavior trends, and recommend strategic business decisions.

---

## 📁 Project Structure

📁 Streaming-Service-User-Analysis/
├── 📊 Streaming_Service_Analysis_Complete.xlsx # Excel dashboard file
├── 🧠 Streaming Service User Analysis.pptx # Project presentation slides
├── 📄 Streaming Service User Analysis.pdf # Project description and problem statement
├── 📈 streaming_service_data.csv # Raw dataset used for the analysis
└── 📘 README.md # Documentation


---

## 🧠 Project Objectives

The primary goal of the project is to:

- Analyze **user behavior**, **subscription plans**, **engagement patterns**, and **demographic factors**.
- Use Excel for **data cleaning**, **data transformation**, and **visual dashboard creation**.
- Provide **insightful visualizations** and actionable business recommendations.

---

## 🔍 Key Analysis Areas

1. **Subscription & Revenue Analysis**
   - Revenue from different subscription tiers.
   - Price tier distribution.

2. **User Engagement Metrics**
   - Average watch hours.
   - Movies vs. Series consumption.
   - Impact of personalized recommendations.

3. **Demographics & Behavior**
   - Age-wise genre preferences.
   - Peak watch time (Morning, Evening, Late Night).
   - Device usage patterns.

4. **Retention & Loyalty**
   - Membership status.
   - Loyalty point distribution.
   - Login frequency and content downloads.

5. **Payment & Regional Insights**
   - Payment methods by region.
   - Subscription trends by country.
   - Language preference and engagement correlation.

---

## 🧼 Excel Data Cleaning & Processing Steps

- Removed duplicates and corrected data entry errors.
- Handled missing values using logical replacements.
- Created new columns like:
  - **Loyalty Points Range**
  - **Engagement Score**

### ✅ Engagement Score Formula:
```excel
= (Watch Hours * 0.40) 
+ (Total Movies Watched * 0.15) 
+ (Total Series Watched * 0.15) 
+ (Has Downloaded Content * 10) 
+ (Average Rating Given * 2) 
+ (Loyalty Points * 0.05) 
+ (Active Devices * 0.025) 
+ (Profile Count * 0.025)
