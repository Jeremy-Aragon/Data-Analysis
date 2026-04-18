# Amazon Top 100 Bestselling Books Analysis (2009-2021)

![Amazon Bestseller Dashboard](Dashboard%20Amazon.png)

## 📊 Project Overview
This project features a professionally designed Excel Dashboard analyzing Amazon's "Top 100 Bestselling Books" over a 12-year period. The analysis transforms raw retail data into an interactive tool for tracking market performance, author popularity, and pricing trends.

## 🎯 Strategic Business Insights
* **Author Performance:** Developed a dynamic Top 10 leaderboard to identify "power authors" (like Jeff Kinney) based on review volume and market presence.
* **Pricing Strategy:** Analyzed average price points across different years to identify the optimal price ceiling for bestsellers.
* **Volume Tracking:** Monitored total title counts and review metrics to gauge overall market engagement.

## 🛠️ Technical Implementation
* **Dynamic Pivot Data Linking:** Connected Text Box UI elements directly to Pivot Table calculations to create a modern, responsive "Card" interface.
* **Interactive Slicers:** Integrated multi-select Year and Genre slicers using **Report Connections** to drive all visuals simultaneously.
* **Advanced Charting:** Implemented a Dynamic Top 10 Bar Chart using Pivot Table Value Filters, allowing for year-by-year competitive analysis.
* **Data Cleaning:** Processed the raw dataset using Python (Pandas) and Excel to handle missing values, standardize cover types, and group price ranges.

## 📈 Key Features
* **Top 10 Leaderboard:** Automatically sorts and displays the most impactful authors for any selected time period.
* **Total Titles KPI:** A dynamic counter that updates instantly as filters are applied to show the number of books in the selection.
* **Custom UI/UX Design:** Styled with Amazon's brand identity (Orange & Dark Gray) to provide a cohesive and professional user experience.

## 🗂️ Data Cleaning Process
The raw data was refined to ensure professional-grade accuracy:
1. **Deduplication:** Removed redundant entries and non-essential index columns.
2. **Standardization:** Cleaned inconsistent categorical data (Genres and Cover Types).
3. **Data Verification:** Validated pricing and rating data for consistency across all 12 years.

## 🚀 How to Use the Dashboard
1. Open the `Amazon_Bestseller_Dashboard.xlsx` file.
2. Use the **Year Slicer** on the left to filter the entire dashboard view.
3. Observe how the **Top 10 Authors** and **Total Titles** metrics update instantly to reflect your selection.
