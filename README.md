<img width="382" height="304" alt="image" src="https://github.com/user-attachments/assets/ce5bf3d1-73b0-428e-8ff0-f287d0ae121d" />

A complete Facebook ad campaign analysis featuring dashboard visuals, cleaned datasets, performance reports, and insights. Includes data cleaning, transformation scripts, and Power BI files to evaluate ad effectiveness and optimize future campaigns.
# INTRODUCTION
A Facebook ad campaign is a structured marketing effort run through Meta’s advertising platform to promote products, services, or content to targeted audiences.
This report presents a detailed analysis of an advertising campaign’s performance across various metrics, demographics, and time periods. It aims to evaluate the efficiency, engagement, and cost-effectiveness of the campaign to guide future strategic decisions.

# CAMPAIGN OBJECTIVES
1. Maximize brand visibility through high impressions across targeted audiences.
2. Drive user engagement, measured by interaction rates and engagement efficiency.
3. Generate traffic via ad clicks, aiming to convert viewers into active users.
4. Analyze demographic responsiveness, focusing on age and gender performance.
5. Evaluate ad spend effectiveness using cost-per-click and spend efficiency metrics.
6. Support future campaign optimization by identifying high-performing segments and refining targeting strategies.

# KEY METRICS OVERVIEW

**Spend Efficiency (6.60%)** is low, meaning that only a small portion of the budget is translating into meaningful engagement.
**Engagement Efficiency (34.09%)** is relatively high, showing that once users interact, they are actively engaging with the content.
**Click-Through Rate (CTR) at 0.02%** is extremely low, confirming that very few users are clicking on the ads despite high visibility.
**Total Spend of $39K** is substantial, and the low CTR raises concerns about return on investment.
These metrics collectively show that while the campaign is visible and engaging, it is not converting well, and the budget is n

# ABOUT THE DATASET
The dataset is from Kaggle.
The dataset contains 3 unique campaigns.
Sometimes the clicks are zero, but total_conversion still has a >0 value.
There can be a delay in time which causes this. Click happened on Monday but the install and signup took place a few days later for instance.
Link to the dataset: https://www.kaggle.com/datasets/madislemsalu/facebook-ad-campaign.

# KEY TABLES IN THE DATASET
The dataset has only table but other measures were created to facilitate great relationship in the modelling of the data. The main table of the dataset is;
**facebook ad table** and  **Report measures** , **Date** were created alongside the main table to facilitate efficient data modelling.

## CONCEPTS APPLIED 
1. Data Transformation: Power Query was used to clean and structure the data.
2. Data Modeling: Relationships between tables were established to ensure data integrity.
3. DAX Calculations: Custom measures were created for aggregations like total sales, order count, and percentage growth.
4. Visualization: Various Power BI visuals such as bar charts, line graphs, matrices, and KPI indicators were used to present insights.

## VISUALIZATION
<img width="602" height="341" alt="image" src="https://github.com/user-attachments/assets/3b081580-13eb-477d-9884-327edbf9619b" />

The dashboard uses charts such as cards to track KPIs, pie charts to show comparisons between fields, bar chart,line charts to show trends, tables for full overview and as well waterfall chart. There are slicers to show data filtering.

## VIEW DASHBOARD
https://app.powerbi.com/links/taf8W32yDU?ctid=f66fae02-5d36-495b-bfe0-78a6ff9f8e6e&pbi_source=linkShare
<img width="1870" height="81" alt="image" src="https://github.com/user-attachments/assets/9725a031-1e05-40cf-9d41-847db0fb4494" />

**Detailed insights into the dashboard is in the ppt file named Detailed Explanation of Dashboard in the main files**.
