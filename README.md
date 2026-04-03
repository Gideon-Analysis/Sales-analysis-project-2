📊 Sales Analysis Project 2
📌 Project Overview
This project analyses sales performance across different regions and product categories to identify key business trends and actionable insights.
🎯 Objective
To understand:
 ∙ Which region generates the most orders and revenue
 ∙ Which product category dominates sales
 ∙ Where the business should focus attention
🛠️ Tools Used
 ∙ Google Sheets (mobile)
 ∙ Formulas: UNIQUE, COUNTIF, SUMIF, SUMIFS, XLOOKUP, INDEX + MATCH, IFERROR, IF
📁 Dataset
The dataset contains:
 ∙ Order ID and Order Date
 ∙ Customer Name
 ∙ Region (North, South, East, West, Central)
 ∙ Category and Sub-Category
 ∙ Sales and Quantity
🧹 Data Cleaning
 ∙ Used =UNIQUE() to remove duplicate rows into a Clean Data sheet
 ∙ Identified and fixed duplicate Order IDs using =COUNTIF()
 ∙ Verified uniqueness using =COUNTIF($A$2:$A$75,A2) then dragged it done to the last row
 ∙ Fixed a Sales value stored as text (“thirty six” → 36)
 ∙ Fixed inconsistent category capitalisation and misspelled region name
 ∙ Deleted one row with a missing Sales value
📊 Analysis Performed
 ∙ COUNTIF and SUMIF for order count and total sales per region
 ∙ UNIQUE + COUNTIF + SUMIF for category breakdown
 ∙ SUMIFS for category sales within a specific region
 ∙ XLOOKUP and INDEX + MATCH with IFERROR for Order ID lookup
📈 Visualisations
 ∙ Column chart: Sales by Region
 ∙ Pie chart: Sales by Category
💡 Key Insights
 ∙ North has the most orders (20) AND the highest sales (10,079) — strongest performing region
 ∙ Technology has outlier sales compared to all other categories, dominating at 63.2% of total revenue
 ∙ Office Supplies and Home Appliances are underperforming — targeted ads, discounts and pattern exploration could help drive growth
📁 Files Included
[Project 002 (1).pdf](https://github.com/user-attachments/files/26462864/Project.002.1.pdf)

📝 What I Learned
 ∙ How to clean and validate real-world data
 ∙ How to summarise raw data into meaningful insights
 ∙ How to present findings clearly using charts and summary tables
📌 Notes
Built entirely on mobile phone — no laptop used 💪
