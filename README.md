# Amazon-store-sales-dashboard.
Amazon Sales Analysis Dashboard - Power BI Project
Executive Summary
This interactive Power BI dashboard provides a comprehensive analysis of sales performance for an Amazon store from 2019 to 2020. Designed with a stakeholder-first approach, this report translates complex sales data into clear, actionable insights. The primary goal is to empower business leaders to make data-driven decisions regarding regional strategy, product portfolio management, and operational efficiency.
The dashboard moves beyond simple reporting to answer key strategic questions:
Which products are our true "stars" versus our "workhorses"?
Which regions are not just high-selling, but also highly profitable?
Which products are causing operational drag due to high return rates?
Where should we focus our marketing and inventory efforts for maximum profitability?
Dashboard Deep Dive: Visuals and Insights
This dashboard is composed of several key components, each designed to provide a specific layer of insight into the business.
1. Key Performance Indicators (KPIs)
Located at the top, these cards provide an immediate, at-a-glance summary of the business's health. They serve as the primary measure of overall performance.
2. Interactive Slicers
To make this dashboard a dynamic tool for exploration, interactive slicers are included:
Filter by Year: Allows for analysis of a single year's performance.
Filter by Region: Enables a deep dive into a specific regional market.
All visuals on the dashboard will dynamically update based on these selections.
3. Strategic Product Analysis: Sales vs. Profit
Visual: Scatter Plot (Sales vs. Profit by Sub-Category)
Business Insight: This is the most strategic chart on the dashboard. Each dot represents a product sub-category, allowing us to visualise the relationship between its sales volume and its profitability. This helps stakeholders instantly identify four key product archetypes:
High-Value Stars (Top-Right): High sales and high profit. These are our best-performing products to be prioritised.
High-Potential (Top-Left): Low sales but high profit margins. These are niche opportunities that could benefit from targeted marketing.
Workhorses (Bottom-Right): High sales but low profit. These drive revenue but require cost optimisation or pricing strategy reviews.
Underperformers (Bottom-Left): Low sales and low profit. These may be candidates for discontinuation.
4. Geographical Performance
Visual: Filled Map (Profit and Sales by Region)
Business Insight: This map shifts the focus from just revenue to regional profitability. It answers a more critical question: "Where are we most efficient?" By visualizing profit, stakeholders can identify regions that may have lower sales but higher margins, guiding decisions on resource allocation, logistics, and market-specific strategies.
5. Product Performance & Operational Insights
Visuals: Bar Chart (Top 5 Profitable Sub-Categories) and Donut Chart (Returns by Sub-Category)
Business Insight: These charts provide a clear view of product performance and its operational impact.
Top 5 Profitable Sub-Categories: This bar chart explicitly highlights our main profit drivers. It provides clear direction on where to focus inventory and marketing spend for the greatest impact on the bottom line.
Returns by Sub-Category: This donut chart is a crucial operational metric. It helps identify products with potential quality issues, description mismatches, or shipping problems. Addressing the highest-return categories can significantly reduce costs and improve customer satisfaction.
Technical Details & Data Modeling
The insights in this dashboard are powered by DAX (Data Analysis Expressions), the formula language for Power BI. Key measures were created to ensure accurate and dynamic calculations.
