# Meta-Ads-performance-dashboard

## Table of content
- [Project Overview](#Project-Overview)
- [Project Scope](#Project-Scope)
- [Data Source](#Data-Source)
- [Tool Used](#Tool-Used)
- [Data Preparation and transformation](#Data-Preparation-and-transfornation)
- [Analysis](#Analysis)
- [Key Observation](#Key-Observation)
- [Recommendations](#Recommendations)
- [Conclusion](#Conclusion)
  
## Project Overview 
The objective of this project is to analyze and track the effectiveness of advertising campaigns across Facebook and Instagram. The dashboard provides insights into key performance metrics such as impressions, clicks, engagement, purchases, likes, and shares, while also identifying behavioral patterns across diverse audience segments. These insights help stakeholders understand where to focus ad optimization efforts to improve overall campaign performance.
## Project Scope
- ‎Analyze ad performance based on engagement rate and purchase rate
- Identify engagement and purchasing behavior patterns by:
  - ‎Age group
  - ‎Gender
  - ‎Country
    
## Data Source


**Tables Data**
- Ads Events Table
- ‎Ads Table
- Calendar Table
- Campaign Table
- ‎User Table

## Tool Used
- Power BI 
## Data Preparation and Transformation
- Data Cleaning:
‎Removed errors, duplicates, and missing values to ensure data accuracy and reliability.
- ‎Data Standardization:
‎Standardized formats for dates, text values, and categorical fields to maintain consistency.
- ‎Derived Columns:
‎‎CreatedCreated additional columns from existing data to generate deeper insights and improve analysis.
- ‎Data Normalization:
‎Normalized the data to reduce redundancy and enhance data organization and performance.
- ‎DAX Creation:
‎Developed DAX formulas to support dynamic calculations and advanced data analysis.
## Analysis
  - ##### KPI
‎‎A total of 12 KPIs were created using DAX:
‎Impressions,Clicks,‎Comments,‎Likes,‎Shares,‎Engagement,‎Engagement Rate,‎Purchases,‎Purchase Rate,Conversion Rate (CR),‎Click-Through Rate (CTR),‎Total Budget.
  - #### Selected KPI:
 To filter the chart on how audience responsed to the ads. this includes;‎Engagement,‎Clicks,‎Comments,Impressions,‎Likes,‎Purchases,‎
 Shares.
  - #### Platform Performance Summary
  
       **Facebook**
- ‎Impressions: 215.97K
- ‎Engagement: 36.80k
- ‎Purchase:
- ‎CTR: 11.76%
- ‎Conversion Rate: 5.21%
  
  **Instagram**
- Impressions: 123.84K
- ‎Engagement: 21.36K
- ‎Purchase:
- ‎CTR: 11.86%
- ‎Conversion Rate: 4.82%


INSTAGRAM DASHBOARD 
  
- #### Dashboard Visualizations
- Target Gender Analysis: Identifies which gender (Male, Female,    All) responds best to ads
- ‎Age Group Analysis: Shows performance metrics across different age segments
- ‎Weekly Trend: Tracks engagement patterns based on ad types by week
- ‎Hourly Trend: Displays hourly user activity and engagement levels
- ‎Ad Type : Compares performance across different ad formats
- ‎Country Analysis: Shows performance metrics by country
- Monthly Analysis: Highlights periods of low and high sales across the month
  
- #### Slicers and Interactivity
- ‎Month Slicer: Filters campaigns by month
- ‎Selected KPI : Allows dynamic switching between engagement, clicks, likes, purchases, and shares

‎All slicers interact dynamically with the dashboard for flexible analysis
‎
## Key Observation

   **Facebook Insight** 
- ‎Female users respond more positively to ads than other genders
- Users aged 16–34 show the highest engagement.
- ‎Top sales originate from the United States, followed by the United Kingdom, Canada, and India.
- ‎Story ads outperform other ad formats.
- ‎Monthly trends indicate higher sales between the 23rd and 31st of each month.
  
 **‎Instagram Insights**
- ‎All genders and female users show strong interaction with ads.
- ‎The 16–34 age group responds best to Instagram ads.
- ‎Carousel and story ads perform best, followed by image ads, while  video ads show the lowest performance.
- ‎Top sales come from the United States, followed by the United Kingdom, Canada, and India.
- Hourly engagement patterns vary week by week, indicating changing user behavior.
## Recommendations
- ‎Review and optimize landing pages, as conversion rates are relatively low
- ‎Increase retargeting efforts toward female and all-gender audiences within the 18–34 age range
- ‎Focus ad spend on stories and carousel ads, followed by image ads, with reduced emphasis on video ads

 ## Conclusion 
The Meta Ads Performance Dashboard effectively analyzes Facebook and Instagram campaigns, highlighting top-performing audiences and ad formats. All gender and Female age 18–34 generate the highest engagement and purchases. While CTR is strong, low conversion rates suggest the need for better landing pages and retargeting.
