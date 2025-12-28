# Swiggy-Data-Analysis-Excel.
Analyzing Swiggy's 2025 transaction data to uncover sales trends and customer insights using Microsoft Excel.
wiggy Order Data Analysis Project (2025) 🍔📊

📌 Project Overview

This project focuses on analyzing Swiggy's transactional data to identify customer ordering patterns, high-performing regions, and operational KPIs. Following a real-world business intelligence workflow, I processed a raw dataset of 197,000+ records to derive actionable insights regarding sales trends and customer preferences.

📂 Dataset Statistics

Total Revenue Analyzed: ₹53,012,505 (~₹53 Million)

Total Orders Processed: 197,430

Average Order Value (AOV): ₹268.51

Average Customer Rating: 4.34/5

🛠️ Technical Implementation & Workflow

1. Data Cleaning & Feature Engineering

Unlike standard datasets, the raw data required significant logic to be analysis-ready. I implemented Advanced Excel Formulas to create new dimensions:

Food Type Classification: Created a custom conditional column to classify dishes as 'Veg' or 'Non-Veg'.

Logic Used: Used SEARCH and ISNUMBER to identify keywords (e.g., "Chicken", "Fish", "Egg") and categorize accordingly.

Temporal Features: Extracted Week Numbers and calculated Quarters (Q1-Q4) from the Order Date using complex integer logic to enable seasonal trend analysis.

Formula Approach: ="Q" & INT((MONTH([@[Order Date]])-1)/3)+1

2. Dashboard Development

Designed an interactive dashboard containing:

Sales by Location: A Map Chart visualization highlighting state-wise revenue concentration (with Karnataka and Maharashtra as top performers).

Top 5 Cities: A horizontal bar chart ranking cities by Gross Merchandise Value (GMV), identifying Bengaluru as the leading market.

Category Analysis: A Donut Chart visualization revealing the split between Vegetarian vs. Non-Vegetarian order volume.

Trend Analysis:

Daily Trends: Vertical bar charts showing sales spikes on weekends (Saturday/Sunday).

Weekly/Quarterly Trends: Line & bar combinations to track performance stability across Q1-Q3.

3. User Experience (UX)

Slicers: Implemented interactive slicers for Month, Restaurant Name, and Category to allow users to filter the entire dashboard dynamically.

Navigation: Added "Back to Data" and "Back to Analysis" navigation buttons for seamless switching between views.

📊 Key Business Insights

Weekend Dominance: There is a significant spike in order volume on Saturdays and Sundays, suggesting a need for increased delivery fleet availability on weekends.

Regional Preferences: Bengaluru leads in total sales volume, correlating with a high concentration of tech-hubs and online-first users.

Menu Strategy: While Non-Veg items often have a higher price point, the volume of Vegetarian orders remains a critical revenue driver (approx. 64% share).

💡 Credits & References

Project Inspiration: Based on the "Real-World Swiggy Sales Analysis" tutorial by Data Tutorials.

Tools Used: Microsoft Excel 365 (Power Pivot, Pivot Tables, Advanced Formulas).
