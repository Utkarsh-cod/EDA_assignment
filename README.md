# 🍽️ Zomato Dataset Exploratory Data Analysis & Feature Engineering

This repository contains an **Exploratory Data Analysis (EDA)** and **Feature Engineering** project on the **Zomato restaurant dataset**. The main goal of this analysis is to uncover insights into restaurant trends, ratings, costs, and geographic distribution, and to prepare the data for potential machine learning applications such as rating prediction or recommendation systems.

---

## 📂 Dataset

### Files Included:
- `zomato.csv` — Primary dataset containing restaurant details.
- `Country-Code.xlsx` — Reference data mapping country codes to country names.
- `EDA.ipynb` — Jupyter Notebook performing EDA and feature engineering.

### Dataset Overview:
The dataset includes information about restaurants listed on Zomato such as:
- Restaurant name, country, and city
- Cuisine types
- Average cost for two
- Online delivery and booking availability
- Aggregate rating and number of votes
- Currency and price range

---

## 🎯 Project Objectives
1. Perform detailed **data cleaning** and **preprocessing**.
2. Conduct **exploratory analysis** to identify trends and patterns.
3. Perform **feature engineering** to make the data ready for modeling.
4. Derive **insights** about restaurant performance, location-based trends, and customer preferences.

---

## 🧹 Data Cleaning
Key preprocessing steps include:
- Handling missing and null values.
- Removing duplicates and irrelevant columns.
- Merging `Country-Code.xlsx` with `zomato.csv` to map country names.
- Converting categorical features to appropriate formats.
- Standardizing textual data (like cuisines and city names).

---

## 🔍 Exploratory Data Analysis (EDA)
Insights explored in the notebook include:
- Top countries and cities with the most restaurants.
- Most common cuisine types across countries.
- Distribution of restaurant ratings.
- Relationship between **cost**, **rating**, and **online delivery**.
- Heatmaps and visualizations of rating patterns and cost variations.

---

## ⚙️ Feature Engineering
Key features created or transformed:
- Binary encoding of online delivery and table booking options.
- Extraction of **primary cuisine**.
- Mapping **price ranges** to categories.
- Aggregation of **country-wise average ratings and costs**.

---

## 📊 Visualizations
The analysis includes visual representations such as:
- Bar charts of top cuisines and countries.
- Pie charts showing online delivery and booking availability.
- Heatmaps for correlation analysis.
- Boxplots of cost vs rating.

---

## 🧠 Tools & Technologies
- **Python** 🐍  
- **Pandas**, **NumPy** — Data handling  
- **Matplotlib**, **Seaborn** — Data visualization  
- **Jupyter Notebook** — Interactive analysis  
- **Excel** — Dataset reference mapping  

---

## 💡 Key Insights
- India has the highest number of Zomato-listed restaurants.
- North Indian and Chinese cuisines are the most popular.
- Online delivery restaurants tend to have higher ratings.
- Certain countries like the UAE and UK show higher average costs for two.

---

## 📁 Repository Structure
📦 Zomato-EDA-FeatureEngineering
- 📜 EDA.ipynb
- 📜 zomato.csv
- 📜 Country-Code.xlsx
- 📜 README.md

---
