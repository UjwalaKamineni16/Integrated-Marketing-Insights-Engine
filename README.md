## Integrated Marketing Insights Engine

##Overview
The Integrated Marketing Insights Engine is a comprehensive analytics solution designed to provide actionable insights for marketing strategies. This project integrates customer data, engagement metrics, product pricing, and sentiment analysis to enable data-driven decision-making, ultimately improving customer engagement and ROI.
The project leverages SQL for data processing, Power BI for visualizations, and Python for advanced analytics, making it a versatile and powerful marketing analytics tool.

##Features

#Data Cleaning and Transformation
Product Price Categorization: Classifies products into "Low," "Medium," or "High" price categories for segmentation and analysis.
Whitespace Cleanup: Removes unnecessary spaces from customer reviews to improve text processing quality.
Customer Data Enrichment: Combines customer and geography data to provide location-specific insights.
Engagement Data Normalization: Cleans and formats engagement metrics for consistent analysis.

##Advanced Analytics

Sentiment Analysis: Analyzes customer reviews to identify positive, neutral, or negative sentiments and trends.
Duplicate Detection and Data Cleaning: Uses SQL window functions to identify and clean duplicate customer journey records.

##Interactive Dashboards
Conversion Rate Analysis: Tracks the customer journey stages and calculates conversion rates across channels.
Engagement Metrics Dashboard: Visualizes views, clicks, likes, and other engagement metrics by content type and product.
Customer Feedback Insights: Displays sentiment trends from customer reviews for product improvement.

##Core Components

##SQL Queries:
Queries for data transformation, enrichment, and cleaning (see the documentation in Integrated Marketing Insights Engine.docx).

##Power BI Dashboard:
Integrated Marketing Insights Engine.pbit: A Power BI template to visualize metrics and insights.

##Data Files:
fact_customer_reviews_with_sentiment.csv: Processed customer reviews data, including sentiment analysis results.
PortfolioProject_MarketingAnalytics.bak: SQL Server database backup for restoring the project database.

##Tools and Technologies
SQL Server: For data storage, transformation, and querying.
Power BI: For creating interactive and shareable dashboards.
Python: For sentiment analysis and advanced data processing.
GitHub: For project management, version control, and collaboration.

##Installation and Setup
##Restore the Database:
Use the PortfolioProject_MarketingAnalytics.bak file to restore the database in SQL Server.
##Run the SQL Scripts:
Execute the SQL queries provided in Integrated Marketing Insights Engine.docx to clean and transform the data.
##Load the Power BI Dashboard:
Open Integrated Marketing Insights Engine.pbit in Power BI Desktop to explore the visualizations.
##Explore Sentiment Analysis:
Use the fact_customer_reviews_with_sentiment.csv file to analyze sentiment trends using Python or other tools.
