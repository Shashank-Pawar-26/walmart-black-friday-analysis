# walmart-black-friday-analysis
Data-driven analysis of Walmart's Black Friday sales to uncover customer behavior, segment high-value shoppers, and generate actionable business insights using Python, statistics, and Power BI.
# 🛍️ Walmart Black Friday Sales Analysis

## 📌 Project Overview
This project analyzes transactional data from Walmart's Black Friday sales to uncover customer purchasing behavior, identify key sales drivers, and provide actionable business insights. The goal is to help Walmart optimize marketing strategies and improve customer segmentation.

## 📊 Business Objective
- Understand which customer segments contribute most to sales.
- Identify high-performing product categories.
- Analyze the impact of demographic features (age, gender, occupation) on purchase behavior.

## 🧮 Dataset Description
- **Source**: [Kaggle – Black Friday Dataset](https://www.kaggle.com/datasets/sdolezel/black-friday)
- **Rows**: 550,069
- **Columns**: 12
- **Key Features**:
  - `User_ID`, `Product_ID`
  - `Gender`, `Age`, `Occupation`, `City_Category`
  - `Stay_In_Current_City_Years`, `Marital_Status`
  - `Product_Category_1/2/3`
  - `Purchase` (target variable)

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Statistical Analysis (`scipy.stats`)
- Power BI (for dashboarding)
- Jupyter Notebook / Google Colab

## 🔍 Exploratory Data Analysis (EDA)
- Checked for missing values and data types
- Visualized purchase distribution by gender, age, and city
- Analyzed product category popularity
- Identified top spenders and high-value segments

## 📈 Key Insights
- **Males** tend to spend more than females on average.
- **Age group 26–35** is the most active and high-spending demographic.
- **City Category B** customers contribute the most to overall sales.
- **Product Category 1** dominates in terms of frequency and revenue.

## 📐 Statistical Analysis
- Conducted hypothesis testing to compare average purchases across gender and age groups.
- Used ANOVA and t-tests to validate differences in spending behavior.

## 📊 Dashboard
Power BI dashboard includes:
- Sales by demographic segments
- Product category performance
- Purchase trends by city and marital status

## 📁 Folder Structure
