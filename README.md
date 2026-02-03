# Bank Loan Risk & Profitability Analysis 

## Project Overview

This project performs an end-to-end exploratory data analysis on Lending Club loan data to understand **loan default risk**, **customer behavior**, and **profitability drivers**. The objective is to identify high-risk segments, evaluate risk–return trade-offs, and provide data-driven recommendations to improve lending strategy.
The project focuses on **analytics and business insights**, not machine learning, reflecting real-world data analyst responsibilities.  

## Business Objectives  

Analyze factors influencing loan default  
Identify profitable vs unprofitable loan segments  
Understand risk–return trade-offs across borrower groups  
Study trends in lending volume, risk, and profitability over time  

## 📂 Dataset  

Lending Club Loan Dataset (2007–2018)  
Source: Kaggle  

## Tools & Libraries  

Python  
Pandas, NumPy  
Matplotlib, Seaborn  

## Project Workflow  

(1) Data loading & overview  
(2) Column selection & data cleaning  
(3) Feature engineering (profit, default flag, buckets)  
(4) Univariate EDA  
(5) Risk analysis  
(6) Profitability & risk–return analysis  
(7) Time trend analysis  
(8) Business conclusions & recommendations  

## Data Preparation Highlights  

Converted interest rate and loan term fields from text to numeric format for quantitative analysis.  
Standardized employment length values into numeric years.  
Created a binary default_flag column to clearly identify defaulted vs non-defaulted loans.  
Engineered a profit metric (total_pymnt - loan_amnt) to evaluate loan-level profitability.  
Bucketed annual income and interest rates into meaningful ranges for segmentation analysis.  
Extracted loan issue year from date field to enable time-based trend analysis.  

## Key Analyses Performed  

Distribution of loan amount, interest rate, grade, and term  
Default rate by grade, interest bucket, income group, and purpose  
Profitability by grade, income group, and interest bucket  
Risk vs return comparison  
Year-wise trends in lending volume, default rate, and profit  

## Final Business Conclusions  

Lending volume shows strong long-term growth, indicating continuous platform expansion.  
Default rates declined in the early years but increased slightly in recent periods, suggesting emerging risk pressure.  
Average profit per loan improved significantly after 2009 and remains positive overall.  
Higher-risk loan grades exhibit higher default rates but also higher average profits, reflecting a clear risk–return trade-off.  
Mid-grade borrowers offer the most balanced combination of risk and profitability.  

## Recommendations  

Apply tighter approval criteria and closer monitoring for high-risk grades (F–G).  
Reassess pricing strategies to ensure high-risk segments remain adequately compensated for elevated default risk.  
Prioritize growth in mid-grade and mid-income customer segments to balance portfolio risk and returns.  

## Key Skills Demonstrated   

Large dataset handling  
Data cleaning & transformation  
Feature engineering  
Exploratory Data Analysis (EDA)  
Financial & risk analysis  
Data visualization & storytelling  


## Repository Structure  
Bank-Loan-Risk-Analysis  
│  
├── data  
│   ├── raw  
│   └── processed  
│
├── notebooks  
│   ├── 01_data_preparation.ipynb  
│   ├── 02_univariate_eda.ipynb  
│   ├── 03_risk_analysis.ipynb  
│   ├── 04_profitability_analysis.ipynb  
│   └── 05_time_trend_analysis.ipynb  
│
├── visuals  
├── README.md  
└── requirements.txt  
