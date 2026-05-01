# bike-share-powerbi-dashboard
Bike Share Analytics Dashboard using Power BI, DAX, and Power Query
This project presents an end-to-end data analysis of a bike-sharing system using Power BI. The goal is to analyze rider behavior, identify usage patterns, and derive business insights from multi-year datasets. The dashboard provides interactive visualizations to explore trends across time, rider types, seasons, and other influencing factors.

Dataset Description:
The analysis is based on the following datasets:
bike_share_yr_0.csv shows Bike usage data for Year 1
bike_share_yr_1.csv shows Bike usage data for Year 2
cost_table.csv shows Pricing and cost data for revenue & profit analysis
bike_riders_data_by_state.csv shows Geographic distribution of riders

Tools & Technologies:
Power BI
Power Query (Data Transformation)
DAX (Data Analysis Expressions)

Data Preparation:
The following data transformation steps were performed:
Appended multi-year datasets to create a unified dataset
Cleaned data by handling null values and standardizing data types
Renamed and removed unnecessary columns
Created new columns (Day Name, conditional columns, etc.)
Filtered and structured data for analysis
Integrated cost data for revenue and profit calculations

Dashboard Features:
The Power BI dashboard includes:
KPI Cards:
Total Riders
Trend Analysis:
Riders over time (daily/monthly trends)
Running total growth
Rider Segmentation:
Registered vs Casual riders
Seasonal Analysis:
Rider distribution across seasons
Additional Insights:
Quarterly comparisons
Rider behavior patterns

Key Insights:
Total riders exceeded 3.3M, showing strong growth over time
Registered users contribute the majority of bike usage
Rider activity is highest during warmer seasons
Demand shows consistent upward trends across years
Winter season has significantly lower rider activity
