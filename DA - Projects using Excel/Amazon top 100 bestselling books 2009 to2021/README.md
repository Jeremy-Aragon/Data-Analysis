# Amazon Top 100 Bestselling Books Analysis (2009-2021)

![Project Dashboard](Dashboard%20Amazon.png)

## 📊 Project Overview
This project features an interactive Excel Dashboard designed to analyze market trends, pricing strategies, and author performance within Amazon's "Top 100 Bestselling Books" over 12 years. The goal was to transform raw retail data into actionable business insights for publishing stakeholders.

## 🎯 Business Problems Solved
* **Market Share Analysis:** Identified the shifting dominance between Fiction and Non-Fiction genres to guide marketing budget allocation.
* **Pricing Optimization:** Analyzed average price trends over a decade to identify the "price ceiling" for bestsellers.
* **Risk Assessment:** Tracked author longevity and "staying power" to identify high-value talent for future acquisitions.
* **Operational Efficiency:** Evaluated book format (Hardcover vs. Paperback) popularity to inform supply chain and printing decisions.

## 🛠️ Key Features
* **Interactive Slicers:** Allows users to filter the entire dataset by **Year**, **Genre**, and **Cover Type** with a single click.
* **Dynamic KPI Cards:** Real-time calculation of Total Reviews, Average Ratings, and Average Price.
* **Trend Visualization:** A smoothed line chart showing the evolution of book pricing from 2009 to 2021.
* **Top 10 Leaderboard:** A sorted bar chart identifying the most successful authors by total appearances in the Top 100.

## 🗂️ Data Cleaning Process
The raw dataset underwent a rigorous cleaning process using Python (Pandas) and Excel to ensure professional-grade accuracy:
1. **Deduplication:** Removed redundant entries and "junk" index columns.
2. **Standardization:** Grouped inconsistent cover types into clean categories (Hardcover, Paperback, Board Book).
3. **Handling Missing Values:** Purged rows with null titles or "unknown" genres to maintain data integrity.

## 📈 Insights & Recommendations
* **Insight:** Non-Fiction titles consistently hold a higher average price point than Fiction, despite lower volumes.
* **Recommendation:** Publishers should prioritize high-quality Hardcover releases for Non-Fiction to maximize profit margins.
* **Insight:** Paperback formats have seen a 15% increase in market share in the Top 100 since 2018.
* **Recommendation:** Focus inventory efforts on Paperback editions for mass-market Fiction titles.

## 🚀 How to Use the Dashboard
1. Open the `Dashboard - Amazon top 100 bestselling books 2009 to2021.xlsx` file.
2. Use the **Slicers** on the left to filter the view by your area of interest.
3. Observe the KPI cards and charts update automatically.
