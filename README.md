# Credit-Card_PowerBI_Project 

<b>Project Overview</b>

This project consists of two interactive Power BI dashboards developed to analyze Credit Card Customer Data and Credit Card Transaction Data.

The objective is to provide meaningful insights into:
- Customer demographics
- Income segmentation
- Spending behavior
- Revenue trend
- Card type performance

The dashboards are fully interactive and allow filtering by Gender, Age Group, Income Group, Card Type, Week, and Spending Category.

<b>Dashboard 1 – Credit Card Customer Report</b>

<b>Objective
To analyze customer demographics and segmentation patterns to identify high-value customer groups.

<b>Key Metrics</b>
- Total Customers
- Total Income
- Average Income
- Average Age
- Average Satisfaction Score

<b>Key Visuals</b>
- Income Trend by Age Group (Line Chart)
- Customer Distribution by Card Type
- Income Group vs Card Type
- Satisfaction Score by Income Group
- Age Group vs Customer Count
- Insights Generated

<b>Identified peak income age groups</b>
- High-income customers show higher adoption of premium cards.
- Certain income segments contribute disproportionately to total income.
- Satisfaction levels vary across income categories.

<b>Dashboard 2 – Credit Card Transaction Report</b>

<b>Objective</b>
To analyze spending behavior, transaction frequency, and revenue performance.

<b>Key Metrics</b>
- Total Transaction Amount
- Total Transaction Volume
- Total Revenue
- Average Utilization Ratio
- Week-over-Week Revenue Change

<b>Key Visuals</b>
- Weekly Revenue Trend (Line Chart)
- Transaction Volume Trend
- Spending Category Analysis
- Revenue by Card Type
- Income Group vs Spending Category
- Utilization Ratio by Card Type

<b>Insights Generated</b>
- Revenue trends show weekly fluctuations.
- Premium cards contribute higher revenue.
- High-income customers spend more on specific categories.
- Certain spending categories dominate transaction volume.

<b>Tools & Technologies Used</b>
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (Data Cleaning & Transformation)
- Data Modeling (Relationships & Star Schema Approach)

<b>Key DAX Calculations</b>
- Age Group Categorization
- Income Group Classification (Low / Medium / High)
- Total Revenue
- Current Week Revenue
- Previous Week Revenue
- Week-over-Week Growth %
- Average Income
- Total Income

<b>Interactivity Features</b>
- Slicers (Gender, Age Group, Income Group, Card Type, Week, Spending Category)
- Drill-through functionality
- Synced slicers across pages
- Custom tooltips
- Dynamic KPI updates
- Sort-by-column for logical age group ordering

<b>Challenges Faced</b>
- Circular dependency issue while sorting Age Groups.
- Designing clean yet insight-rich dashboards without clutter.
- Ensuring all slicers interact consistently across visuals.
- Creating accurate Week-over-Week revenue calculations using DAX.
- Maintaining proper relationships between customer and transaction tables.

<b>Business Recommendations</b>
Based on analysis, the following recommendations can be provided:
- Target high-income age groups with premium credit card upgrades.
- Focus marketing efforts on high-spending categories.
- Monitor utilization ratios to manage credit risk.
- Improve engagement strategies for lower-income segments.
- Optimize card offerings based on revenue contribution trends.

<b>Project Deliverables</b>
- Power BI file (.pbix) with:
  - Customer Dashboard
  - Transaction Dashboard
- Documentation (README)
- Interactive filtering and professional UI design

<b>Conclusion</b>
This project demonstrates the ability to:
- Clean and model relational datasets
- Build advanced DAX measures
- Create interactive and professional dashboards
- Translate raw data into business insights
- Provide strategic recommendations

Screenshort of Dashboard:-
<br>Credit_Card_Customer_Report
![1](https://github.com/Archis-Save/Credit-Card_PowerBI_Project/blob/main/Credit_Card_Customer_Report2.PNG)  <br>
<br>Credit_Card_Transaction_Report
![2](https://github.com/Archis-Save/Credit-Card_PowerBI_Project/blob/main/Credit_Card_Transaction_Report3.PNG)
