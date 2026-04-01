# 📊 Consumer Sentiment & Demographic Analysis Dashboard

## 📌 Overview
This project analyzes consumer behavior using a survey dataset related to streaming services. The focus is on understanding user preferences, viewing habits, and price sensitivity through interactive dashboards built in Power BI.

## 🎯 Objectives
Analyze user behavior across different demographic groups
Understand platform usage, content preferences, and viewing patterns
Identify factors influencing subscription decisions
Build intuitive dashboards to communicate insights effectively

## 🧹 Data Preparation
The dataset required several cleaning and transformation steps:
Standardized column names for consistency (e.g., platform_primary, content_preference)
Created a generation column by mapping age ranges (Gen Alpha, Gen Z, Millennials)
Derived a price sensitivity flag based on responses to cancellation behavior
Converted non-numeric values (e.g., “4+”) in subscription count into numeric format
Structured demographic and behavioral fields for better segmentation

## 📈 Dashboard 1: Demographic & Sentiment Overview
This dashboard provides a high-level summary using KPI cards, donut charts, bar charts, and a treemap. It highlights key metrics such as total respondents, average subscriptions, and price sensitivity, along with distributions across generation, platform usage, device preference, and content type. It is designed to quickly communicate overall trends and user behavior.

## 🔍 Dashboard 2: Consumer Behavior & Segmentation Insights
This dashboard focuses on deeper analysis using comparative visualizations such as clustered bar charts, stacked charts, matrices, and funnels. It explores relationships between variables like platform vs price sensitivity, generation vs viewing behavior, and subscription levels across segments. The goal is to uncover patterns and explain differences in user behavior.

## 🛠 Tools Used
Power BI – Data visualization and dashboard development\
Power Query – Data cleaning and transformation\
DAX – Measure and KPI creation

## 📂 Project Structure
/data              → Raw and cleaned dataset  
/dashboard         → Power BI file (.pbix)  
/exports           → PDF of dashboards  
README.md          → Project documentation  

## 📌 Key Insights
Price sensitivity is high, indicating cost is a major factor in subscription decisions\
Many users subscribe to multiple platforms, showing diversified usage behavior\
Only a small portion of users are highly engaged with multiple subscriptions\
Platform usage is fairly evenly distributed, with no single platform dominating\
Viewing behavior varies across generations, with younger users more likely to binge-watch\
Content discovery is largely driven by recommendations and cost-related factors

## 🚀 Future Improvements
Incorporate additional datasets for broader behavioral analysis
Add time-based trends to track changes over time
Enhance sentiment scoring using more detailed survey responses

##👤 Author
Prarthana Shetty
Master’s in Information Systems | Data Analytics
