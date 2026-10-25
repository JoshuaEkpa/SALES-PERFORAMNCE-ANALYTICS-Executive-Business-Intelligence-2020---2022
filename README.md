# SALES-PERFORAMNCE-ANALYTICS-Executive-Business-Intelligence-2020---2022 

<img width="1011" height="576" alt="Screenshot 2026-10-25 171949" src="https://github.com/user-attachments/assets/d6ae2f93-2df9-4763-a23e-6afbc11b19b0" />
_____________________________________________________________________________________________________________
Sales Performance Analysis Dashboard | Power BI

📌 Project Overview

This project analyzes sales performance from 2020 to 2022 using Microsoft Power BI. The objective is to transform raw sales data into meaningful business insights that help organizations understand revenue trends, profitability, product performance, customer behavior, and regional sales performance.

The interactive dashboard provides a consolidated view of key performance indicators (KPIs), enabling stakeholders to monitor business performance, identify growth opportunities, and make data-driven decisions.

____________________________________________________________________________________________________________
🎯 Project Objectives

- Monitor overall sales performance from 2020 to 2022.
- Calculate total sales, gross profit, and profit margin.
- Analyze revenue trends over time.
- Identify top-performing products, categories, and markets.
- Compare regional sales revenue and profitability.
- Evaluate customer activity and order performance.
- Identify potential areas for revenue growth and profit improvement.
- Support strategic planning through interactive data visualization.

___________________________________________________________________________________________________________
🛠️ Tools & Technologies

- Microsoft Power BI: Interactive dashboards and business intelligence reporting.
- Microsoft Excel: Data storage, preparation, and preliminary analysis.
- DAX (Data Analysis Expressions): KPI calculations and analytical measures.
- Power Query: Data cleaning and transformation, where applicable.
- Data Modeling: Organizing data and establishing relationships for analysis.
- Data Visualization: Presenting trends, comparisons, and performance indicators.

___________________________________________________________________________________________________________
📈 Key Performance Indicators (KPIs)

KPI| Description
Total Sales Amount| Total revenue generated from sales transactions.
Gross Profit| Sales revenue less the cost of goods sold.
Profit Margin (%)| Gross profit expressed as a percentage of sales revenue.
Total Orders| Number of distinct orders recorded.
Units Sold| Total quantity of products sold.

These KPIs provide a foundation for evaluating sales performance, financial outcomes, and business growth opportunities.
____________________________________________________________________________________________________________
🧮 DAX Calculations

The following DAX measures illustrate how the dashboard's core KPIs can be calculated. Table and column names should match the actual dataset.

1. Total Sales Amount

Calculates total sales revenue.

Total Sales Amount =
SUM('Sales'[Sales])

2. Total Cost

Calculates the total cost associated with sales.

Total Cost =
SUM('Sales'[Cost])

Assumption: The Cost column represents the cost of goods sold.

3. Gross Profit

Gross profit measures the amount remaining after subtracting the cost of goods sold from sales revenue.

Formula:

Gross Profit = Total Sales Amount − Total Cost

Gross Profit =
[Total Sales Amount] - [Total Cost]

4. Profit Margin (%)

Profit margin measures gross profit relative to total sales revenue.

Formula:

Profit Margin = (Gross Profit ÷ Total Sales Amount) × 100

Profit Margin % =
DIVIDE(
    [Gross Profit],
    [Total Sales Amount],
    0
)

Important: Format this measure as Percentage in Power BI. Do not multiply the DAX result by 100 when percentage formatting is applied.

5. Total Orders

Counts unique order IDs.

Total Orders =
DISTINCTCOUNT('Sales'[Order ID])

6. Units Sold

Calculates the total quantity sold.

Units Sold =
SUM('Sales'[Quantity])

Note: These measures are templates. Verify the dataset's schema and ensure that the cost calculation reflects the intended business definition.

__________________________________________________________________________________________________________

📊 Dashboard Features

1. Executive Overview

Provides a high-level summary of business performance through KPI cards displaying total sales, gross profit, profit margin, total orders, and units sold.

Business purpose: Enables management to assess overall performance quickly.

2. Revenue Trend Analysis

Visualizes sales revenue over time across the 2020–2022 reporting period.

Business purpose: Helps identify growth patterns, fluctuations, seasonal trends, and periods requiring further investigation.

3. Revenue Composition

Uses a treemap to display the contribution of different products or categories to total sales revenue.

Business purpose: Helps identify important revenue contributors and assess the distribution of sales across the product portfolio.

4. Regional Profitability Matrix

Uses a scatter chart to compare sales revenue and gross profit across regions or locations.

Business purpose: Helps identify high-performing markets, compare profitability, and investigate locations with strong revenue but relatively weak profit.

5. Top Market Performance

Highlights leading markets using sales revenue, customer counts, and order volume.

Business purpose: Helps identify commercially important markets and potential opportunities for expansion.

___________________________________________________________________________________________________________
🔍 Key Insights

The dashboard supports the following areas of business analysis. Specific findings should be confirmed using the actual results displayed in Power BI.

1. Revenue Performance

Analyzing sales trends over the three-year period helps establish whether revenue is increasing, decreasing, or fluctuating over time.

Analytical value: Identifies periods of strong performance and periods that may require further investigation.

2. Profitability and Margins

Comparing gross profit with sales revenue provides a clearer understanding of how effectively revenue translates into profit.

Analytical value: Helps distinguish revenue growth from profitable growth.

3. Product and Category Contribution

Revenue composition reveals how sales are distributed across products and categories.

Analytical value: Helps identify key revenue drivers and products that may require pricing, marketing, or portfolio reviews.

4. Regional Performance

Comparing sales revenue and gross profit across locations provides insight into differences in regional performance.

Analytical value: Helps identify successful markets and locations where sales or profitability could be improved.

5. Market and Customer Activity

Examining order volumes and customer counts helps assess the level of commercial activity across different markets.

Analytical value: Provides a basis for investigating customer engagement, repeat purchasing, and opportunities to increase sales.
__________________________________________________________________________________________________________

💡 Business Recommendations

Based on the analytical capabilities of the dashboard, the following actions can be considered after validating the findings against the data.

1. Strengthen Revenue Growth

Investigate periods of declining sales and evaluate potential causes such as seasonal demand, pricing changes, product availability, and marketing effectiveness.

Recommended action: Develop targeted sales strategies and monitor their impact on revenue over time.

2. Improve Profitability

Assess product costs, selling prices, discount policies, and product mix to identify opportunities to improve gross profit and profit margin.

Recommended action: Prioritize actions that improve profitability without unnecessarily sacrificing sales volume.

3. Optimize Product Performance

Evaluate the sales contribution and profitability of individual products and categories.

Recommended action: Maintain appropriate stock levels for high-demand products and assess underperforming products before changing inventory or marketing priorities.

4. Improve Regional Sales Performance

Compare the performance of high-performing and underperforming markets, taking local demand and operating conditions into account.

Recommended action: Replicate successful sales practices where appropriate and develop targeted improvement plans for weaker markets.

5. Increase Customer Engagement

Use order and customer data to understand purchasing patterns and identify opportunities to encourage repeat purchases.

Recommended action: Consider customer retention initiatives, targeted promotions, and improved customer engagement strategies.

6. Establish Regular Performance Monitoring

Use the Power BI dashboard to review business performance consistently and investigate significant changes in KPIs.

Recommended action: Establish weekly or monthly performance reviews, supported by clear KPI targets and follow-up actions.

____________________________________________________________________________________________________________
📌 Key Business Value

This project demonstrates how business intelligence tools can support practical decision-making by:

- Improving visibility into sales and profitability.
- Supporting evidence-based product and market evaluation.
- Identifying potential revenue growth opportunities.
- Helping management investigate changes in business performance.
- Enabling consistent monitoring of key performance indicators.
- Communicating analytical findings through interactive visualizations.
___________________________________________________________________________________________________________

🚀 Future Improvements

Potential enhancements to the dashboard include:

- Adding year-over-year revenue and profit growth measures.
- Introducing sales targets and actual-versus-target comparisons.
- Adding a customer segmentation analysis.
- Developing a product-level profitability analysis.
- Including inventory performance and stock turnover metrics, if the required data is available.
- Implementing automated data refresh and scheduled reporting where supported.

___________________________________________________________________________________________________________

📝 Conclusion

The Sales Performance Analysis Dashboard demonstrates the application of Microsoft Power BI, Excel, and DAX to sales data analysis and business intelligence.

By consolidating sales revenue, gross profit, profit margin, order activity, product contribution, and regional performance into an interactive reporting environment, the project provides a foundation for identifying business trends and evaluating performance.

The analysis highlights the importance of looking beyond revenue alone and considering profitability, customer activity, and market performance when making business decisions.
_____________________________________________________________________________________________________________
DASHBOARD PREVIEW_1 FOR EXECUTIVE OVERVIEW 
<img width="1011" height="576" alt="Screenshot 2026-10-25 171949" src="https://github.com/user-attachments/assets/fe6e99b6-f949-4f5b-9a02-cc97d0fe0a2e" />

___________________________________________________________________________________________________________
DASHBOARD PREVIEW_2 FOR PRODUCT ANALYSIS
<img width="1011" height="570" alt="Screenshot 2026-10-25 172010" src="https://github.com/user-attachments/assets/f804289e-c20f-4e1c-acd8-5b8fa271bd27" /> 

__________________________________________________________________________________________________________
DASHBOARD PREVIEW_3 FOR REGIONAL PERFORMANCE
<img width="1011" height="578" alt="Screenshot 2026-10-25 172034" src="https://github.com/user-attachments/assets/a1881627-9984-42a6-9b69-68423fa9da47" />

_________________________________________________________________________________________


👨‍💻 Author :Joshua Ekpah

Data Analyst | Business Intelligence | Power BI | SQL | Excel

📬 Connect With Me

- LinkedIn: "Joshua Ekpah" (https://www.linkedin.com/in/joshua-ekpah-302223327/)
- Portfolio: "JOSNEX Analytics & Technology Ltd" (https://joshuaekpa5.wixsite.com/joshuaekpa)

---

Turning Data into Impactful Decision Making — Data is Life.
