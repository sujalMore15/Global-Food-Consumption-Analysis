# Global-Food-Consumption Power-BI Analysis
Built an interactive Power BI dashboard to analyze global food consumption trends. Cleaned and transformed data in Excel, modeled datasets with relationships, and created DAX measures including per capita consumption using population data. Delivered insights through dynamic visuals, regional comparisons, and time-based analysis.
Problem Statement

Global food consumption varies significantly depending on geographical location, economic conditions, population distribution, and time.

Analyzing such data using raw tables can make it difficult to identify:

Which areas have the highest consumption.
How consumption differs between regions.
Whether income level influences consumption patterns.
How consumption changes over time.
Which regions contain a larger number of countries.
Which income groups contribute significantly to overall consumption.

Therefore, this project was developed to create a centralized BI dashboard where users can interactively analyze these patterns instead of manually working through large amounts of raw data.

💡 Project Objective

The main objective was to build an interactive reporting solution that converts food-consumption data into meaningful visual insights.

The dashboard allows users to:

Analyze total food consumption.
Compare consumption across geographical areas.
Analyze regional consumption patterns.
Compare different income groups.
Analyze yearly consumption trends.
Identify maximum consumption values.
Filter the analysis by year.
Filter the analysis by income group.
Filter the analysis by area/country.
Compare income groups across different regions.
🔄 Data Analytics Process

The project follows a structured data analytics workflow:

Raw Data → Data Preparation → Data Transformation → Data Modeling → DAX Calculations → Visualization → Interactive Dashboard → Insights

1. Data Preparation

The raw dataset was imported into Power BI and examined to understand its structure, dimensions, and analytical fields.

The important dimensions used in the analysis included:

Year
Country
Area
Region
Income Group
Consumption

The dataset was prepared so that numerical and categorical fields could be used correctly in Power BI visualizations.

2. Data Transformation

Power Query was used to prepare the dataset for analysis.

The transformation stage focused on:

Reviewing data types.
Preparing categorical fields.
Preparing numerical consumption values.
Organizing year-based information.
Ensuring fields could be properly aggregated.
Preparing the dataset for interactive filtering and visualization.
3. Data Modeling

The prepared data was structured within Power BI to support analytical reporting.

The model allows the main consumption metric to be analyzed across different dimensions such as:

Year → Region → Area/Country → Income Group

This structure enables users to move from high-level global analysis to more detailed geographical and income-group analysis.

🧮 DAX Analysis

DAX was used to create analytical measures required for the dashboard.

The project uses calculations related to:

Total Consumption
Country Count
Maximum Consumption
Consumption by Year
Consumption by Region
Consumption by Income Group
Consumption by Area

These measures allow the dashboard visuals and KPI cards to respond dynamically when users interact with slicers.

🎛️ Interactive Dashboard

One of the major features of the project is its interactive filtering capability.

The dashboard contains slicers for:

📅 Year

Users can select individual years to analyze consumption for a specific period.

💰 Income Group

Users can analyze consumption based on:

High Income
Low Income
Lower Middle Income
Upper Middle Income
🌎 Area

Users can select individual geographical areas/countries to perform focused analysis.

Because the visuals are connected to these filters, changing a slicer dynamically updates the corresponding dashboard components.

📊 Dashboard Components
1. Maximum Consuming Country KPI

A KPI card highlights the maximum consumption value available within the selected analytical context.

This provides an immediate high-level summary before users move into detailed visual analysis.

2. Count of Country by Region

A pie chart is used to show how countries in the dataset are distributed across different regions.

The visualization provides a quick comparison between regions such as:

Europe
Latin America
East Asia
Middle East
North America
Sub-Saharan Africa

This helps establish the geographical composition of the dataset.

3. Count of Country by Income Group and Region

A stacked bar chart compares country counts across income groups and regions.

This visualization combines two dimensions:

Income Group + Region

It helps identify how different income classifications are distributed geographically.

4. Total Consumption by Area and Income Group

A horizontal stacked bar chart compares total consumption across different areas while separating the contribution of income groups.

This makes it possible to identify areas with high consumption and understand the income-group composition behind the totals.

5. Total Consumption by Year

A line chart is used to analyze the overall consumption trend across years.

The visualization makes it easier to identify:

Growth trends
Declining periods
Long-term movement
Changes in total consumption

The dashboard shows an overall upward trend in total consumption during the analyzed period.

6. Detailed Area-Level Consumption Analysis

A detailed area-level visualization provides a broader comparison of consumption across multiple geographical areas.

The chart combines:

Area + Income Group + Total Consumption

This allows users to identify major consumption contributors and compare the contribution of different income groups.

🔍 Key Analytical Insights

The dashboard provides several important insights.

🌎 Geographical Differences

Food consumption is not evenly distributed across geographical areas. Certain areas contribute considerably more to overall consumption than others.

💰 Income-Based Differences

Consumption patterns vary between income groups. The dashboard allows users to compare high-income, middle-income, and low-income groups to understand these differences.

📈 Long-Term Trend

The yearly analysis indicates an overall upward movement in total food consumption across the analyzed period.

🌍 Regional Distribution

The number of countries represented across regions varies, providing important context when interpreting regional comparisons.

📊 Concentration of Consumption

The area-level analysis demonstrates that a relatively smaller group of areas contributes a substantial portion of total consumption.

🧰 Tools & Technologies
Technology	Purpose
Microsoft Power BI	Dashboard development and visualization
Power Query	Data cleaning and transformation
DAX	Measures and analytical calculations
Data Modeling	Structuring data for analysis
Power BI Slicers	Interactive filtering
Charts & KPI Cards	Data visualization and reporting
📈 Visualizations Used

The dashboard uses multiple visualization techniques:

KPI Cards
Pie Chart
Stacked Bar Chart
Horizontal Bar Chart
Line Chart
Interactive Slicers
Category-based filtering
Time-series analysis
Geographical comparison

The combination of these visuals creates a complete data storytelling experience rather than presenting isolated charts.

💼 Business Intelligence Perspective

From a Business Intelligence perspective, this project demonstrates how organizations can move from:

Raw Data

⬇️

Processed Information

⬇️

Analytical Insights

⬇️

Decision Support

The dashboard provides a centralized environment where users can interact with the data and quickly identify important patterns.

Instead of manually analyzing large tables, users can use the dashboard filters and visualizations to investigate specific questions.

🚀 Skills Demonstrated

Through this project, the following practical skills were demonstrated:

Data Analysis
Business Intelligence
Microsoft Power BI
Power Query
DAX
Data Cleaning
Data Transformation
Data Modeling
KPI Development
Interactive Dashboard Development
Data Visualization
Time-Series Analysis
Comparative Analysis
Regional Analysis
Income-Group Analysis
Data Storytelling
Analytical Thinking
📌 Project Outcome

The final result is an interactive Global Food Consumption Intelligence Dashboard that converts raw consumption data into an easy-to-understand analytical reporting solution.

The dashboard enables users to quickly identify:

What is happening? → Where is it happening? → How does it differ? → How has it changed over time?

This project demonstrates practical application of Power BI, DAX, Power Query, data modeling, and data visualization to solve a real-world analytical problem.
