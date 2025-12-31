# 🎮 Video Games Sales Analysis (Python)

<p align="center">
  <img src="https://github.com/Mazen-Alattar/global-video-games-sales-analysis-python/blob/main/video-games-sales-analysis-python/images/video_games.jpg?raw=true" width="1100">
</p>

## 📌 Project Overview
This project performs an **exploratory data analysis (EDA)** on global video game sales data to uncover trends, market behavior, and performance drivers across regions, genres, platforms, and publishers.

The analysis emphasizes **data cleaning, manual data enrichment, and feature engineering**, making it a strong portfolio project for **Data Analyst Internship** roles.

---

## 🗂 Dataset Information
- **Source:** Kaggle
- **Domain:** Video Game Sales
- **Scope:** Global sales performance

### Original Columns
- Rank  
- Name  
- Platform  
- Year  
- Genre  
- Publisher  
- NA_Sales  
- EU_Sales  
- JP_Sales  
- Other_Sales  
- Global_Sales  

---

## 🔄 Data Cleaning & Enrichment

### Missing Values Handling
Initial missing values:
  Year 271
  Publisher 58

- Missing **Year** values were manually retrieved by researching each game title.
- Missing **Publisher** values were also filled through individual game research.
- This ensured data completeness and improved analytical accuracy.

---

## 🧱 Feature Engineering

### Platform Enhancement
- Platform abbreviations were not clear for analysis.
- A new column **platform_fullname** was created to map platform abbreviations to full names.

### Platform Classification
Additional columns were created:
- **Platform Company** (e.g., Sony, Microsoft, Nintendo)
- **Platform Type** (Console / Handheld)

These features enabled deeper platform-level analysis.

---

## 📊 Exploratory Data Analysis & Insights

### Key Analyses Performed
- **Year Distribution of Game Releases**
- **Number of Games per Year (Top 5 Years)**
- **Top 10 Best-Selling Games**
- **Genre Distribution**
- **Global Sales by Genre**
- **Top Platforms by Global Sales**
- **Top 10 Publishers**
- **Top 10 Publishers by Global Sales**
- **Regional Sales Distribution (NA, EU, JP, Other)**
- **Global Sales Trend Over the Years**
- **Top 10 Platform Companies by Global Sales**
- **Regional Sales by Genre**

---

## 📈 Insight Highlights
- Game releases peak during specific years, reflecting industry growth cycles.
- A small number of games dominate global sales figures.
- Action and Sports genres generate the highest global revenue.
- Certain platforms significantly outperform others in total sales.
- North America and Europe represent the largest gaming markets.
- Platform companies such as Nintendo and Sony lead in global sales.

---

## 📊 Analysis Preview

<table>
  <tr>
    <td><img src="https://github.com/Mazen-Alattar/global-video-games-sales-analysis-python/blob/main/video-games-sales-analysis-python/images/global_sales_over_the_years.png?raw=true" width="400"></td>
    <td><img src="https://github.com/Mazen-Alattar/global-video-games-sales-analysis-python/blob/main/video-games-sales-analysis-python/images/regional_sales_distribution.png?raw=true" width="400"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Mazen-Alattar/global-video-games-sales-analysis-python/blob/main/video-games-sales-analysis-python/images/top_5_years_number_of_games_per_year.png?raw=true" width="400"></td>
    <td><img src="https://github.com/Mazen-Alattar/global-video-games-sales-analysis-python/blob/main/video-games-sales-analysis-python/images/top_platforms_by_global_sales.png?raw=true" width="400"></td>
  </tr>
</table>

---

## 🛠 Tools & Libraries Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

---

## 🎯 Project Goal
This project was developed as part of a **data analytics portfolio** to demonstrate:
- Strong data cleaning and enrichment skills
- Feature engineering for better business insights
- Exploratory data analysis using Python
- Clear storytelling through data visualizations  

Targeted toward **Data Analyst Internship** opportunities.
