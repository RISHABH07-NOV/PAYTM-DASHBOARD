# PAYTM-DASHBOARD
Paytm Transaction Analytics Dashboard:Comprehensive Overview of Paytm’s Transaction Performance and User Insights

Dashboard Description
This dashboard provides a detailed analysis of Paytm’s transaction data, highlighting key performance metrics such as total transaction value, success rate, and average transaction size. It visualizes monthly trends, user demographics across generations, and service-type breakdowns. Additionally, it offers insights into transaction behavior by weekdays versus weekends, helping identify patterns in user engagement and payment success.

Purpose
This dashboard tracks and analyzes Paytm’s transaction performance to help identify trends, user behavior, and service efficiency. It exists to provide actionable insights for improving transaction success rates and understanding customer engagement patterns. 

Tech Stack 
The dashboard was built using the following tools and technologies: 

 • Power BI Desktop – Main data visualization platform used for report creation. 
 • Power Query – Data transformation and cleaning layer for reshaping and preparing the data.
 • DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional       logic.
 • Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation. 
 • File Format – .pbix for development and .png for dashboard previews. 

Data source
Phonepe-Final-Dataset.xlsx - Google Sheets 

THE DATASET CONTAIN TWO TABLE
FIRST TABLE=TRANSACTION ID,AMOUNT,USER ID,PAYMENT METHOD,AREA,SERVICE,SERVICE TYPE,REASON,PAYMENT STATUS,DATE

SECOND TABLE=AGE, JOIN DATE ,USER ID,AGE SEGMENT

Business Problem
Paytm processes millions of transactions daily, but raw logs don’t reveal why transactions fail, which services drive growth, or how different customer segments behave. Without clear visibility, it’s difficult to improve reliability, optimize marketing, and enhance customer experience.

Goal of the Dashboard
To transform raw transaction data into actionable insights by tracking performance metrics, user demographics, and service usage trends. The dashboard exists to help Paytm’s business teams make data-driven decisions that improve transaction success rates and customer engagement

Walkthrough of Key Visuals
    • Transaction Overview Cards → Show total transaction value, average transaction size, and success/failure rates.
    • Monthly Trend Line Chart → Highlights transaction growth or decline over time.
    • User Demographics Chart → Breaks down transactions by generation (Gen Z, Millennials, etc.), showing who drives usage.
    • Service-Type Breakdown → Identifies which services (recharge, bill payment, shopping) contribute most to revenue.
    • Weekday vs Weekend Analysis → Reveals behavioral patterns in transaction volume and success rates 
    • Tooltip → Showing how different generations—Gen Z, Millennial, Gen X, and Boomers—interact with Paytm’s services. It highlights demographic-specific transaction patterns, such as which age groups drive the highest volume, which services they prefer, and how their success rates vary. This generational breakdown helps the business identify target audiences for promotions, tailor product offerings, and design engagement strategies that resonate with each segment. In essence, the tooltip makes the dashboard more insightful by connecting raw transaction data to customer behavior across age groups, enabling Paytm to align its growth strategy with the needs of diverse users. 
    
Business Impact & Insights
    • Operational Efficiency: Pinpoints failure-prone services or time periods, guiding technical fixes.
    • Customer Engagement: Identifies high-value demographics to target with promotions.
    • Revenue Growth: Shows which services generate the most transactions, helping prioritize investment.
    • Strategic Planning: Provides evidence-based insights for marketing campaigns, product improvements, and customer retention strategies.

screenshots




    
