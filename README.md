# Media Campaign Data Cleanup Analysis

## Background

As the Data Manager, I am currently spearheading a project for a global organization engaged in widespread media campaigns conducted through various agencies. My key responsibilities in this project are centered around the meticulous management and analysis of two critical datasets: the Device Location and Inventory Viewability datasets, both stored within Google Cloud and BigQuery.

### Project Context:

- **My Role:** Data Manager
- **Client:** A globally operating entity conducting diverse media campaigns across multiple channels and agencies.
- **Primary Responsibilities:** These include comprehensive campaign reporting and advanced data analytics.
- **Client's Objectives:** The client has tasked me with deriving valuable insights from Key Performance Indicators (KPIs), developing compelling data visualizations, managing intricate pivot tables, creating real-time live dashboards, and formulating actionable recommendations based on thorough campaign data analysis. The overarching goal is to adeptly convert raw data into strategic insights and recommendations, thereby enhancing the effectiveness of the client's ongoing media campaign.

In this venture, my focus is on the rigorous cleaning and strategic management of the datasets. This process involves removing any duplicates, addressing missing values, maintaining consistency in the data, and integrating Conversion Revenues and Profit columns, guided by specific rates related to Inventory and Creatives.

## Summary of Activities:

### Device Location Creative Dataset:

- Eliminated null values and thoroughly examined unique values across different columns.
- Dropped the 'Device_Model' column due to a high number of unknown entries.
- Strategically reformulated the Strategy column for improved clarity.
- Added new 'Conversions_Revenue' and 'Profit' columns, based on detailed analysis.
- Successfully removed duplicate entries to enhance dataset accuracy.

### Inventory Viewability Dataset:

- Removed rows containing null values.
- Dropped the 'Brand_Company_Name' column to eliminate redundancy.
- Reformatted the Strategy column for better readability and understanding.
- Decided to retain negative values in 'Measurable_Impressions' as indicators of specific activities.
- Created new 'Conversions_Revenue' and 'Profit' columns for deeper financial analysis.
- Eliminated all duplicate entries to ensure data integrity.

## Detailed Process Overview:

- The project involved a systematic approach to data cleanup, encompassing validation, exploration, and transformation of the datasets.
- I focused on reformulating strategies across datasets, aiming for enhanced clarity and actionable insights.
- I introduced new revenue and profit calculations, tailoring them to various inventory types based on set conversion rates.
- The culminating datasets were thoroughly cleansed and refined, ensuring a foundation for accurate and meaningful analysis.

## Conclusions:

- The rigorous data cleanup and analytical processes have substantially improved the accuracy and depth of the campaign analysis.
- The integration of financial metrics like revenue and profit has provided a more nuanced understanding of the campaigns' economic impact.
- The insights derived from these datasets are now pivotal in strategic decision-making and in optimizing the direction of future campaigns.

### Our Presentation!

For a comprehensive view of the entire marketing campaign analysis, including detailed insights and strategic recommendations, access the full presentation by [clicking here](https://docs.google.com/presentation/d/1gKod_t-jIwaD47UOPTPsBRV4lsBKrEOz4_GLWBmd2Nk/edit?usp=sharing)

<sub>**Disclaimer:** This project is a capstone project for COOP Careers and does not involve a real client. The scenario described and the roles assumed are for educational purposes within the context of the COOP Careers Data Analytics program.</sup>
