# 🌾 Seasonal Agriculture Performance Analysis

## 📌 Overview

This project analyzes agricultural performance across different **seasons, crops, states, environmental conditions, farming practices, resource usage, and economic outcomes**.

The goal is to identify seasonal patterns, compare agricultural performance, understand important relationships, and provide data-driven recommendations for better agricultural planning.

## 🎯 Objectives

- Analyze agricultural performance across seasons
- Compare crop and state-level performance
- Study environmental factors and their relationship with yield
- Analyze irrigation and resource usage
- Evaluate revenue, cost, and profit
- Identify unusual patterns and outliers
- Generate data-driven insights and recommendations

## 📂 Dataset

- **Rows:** 4,000
- **Columns:** 28
- **Seasons:** Kharif, Rabi, Zaid
- **Format:** CSV

The cleaned dataset contains **no missing values or duplicate rows**.

## 📊 Analysis & Visualizations

The project includes:

- Average Yield by Season
- Average Profit by Season
- Resource Usage by Season
- Environmental Conditions vs Yield
- Crop Performance Across Seasons
- Yield by Irrigation Method
- Yield by State
- State × Season Heatmap
- Profit per Hectare
- Farm Area vs Production
- Water Efficiency vs Yield
- Correlation Analysis

## 🔎 Key Findings

- **Kharif** has the highest average yield at approximately **5.64 tonnes/ha**.
- **Kharif** has the highest average profit at approximately **₹178,915**.
- **Zaid** has the lowest average yield and negative average profit.
- Water efficiency has a strong positive association with yield (**correlation ≈ 0.915**).
- Agricultural performance varies considerably across states and seasons.
- ANOVA did not find a statistically significant difference in average yield across seasons at the 5% significance level.

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## 📁 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── seasonal_agriculture_performance_cleaned.csv
├── Seasonal_Agriculture_Performance_Analysis_Final.ipynb
└── README.md
