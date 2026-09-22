# Airbnb Data Analysis & Excel Dashboard

## Overview
This project analyzes Airbnb listing, calendar, and review data using Microsoft Excel. The goal is to identify patterns in listing prices, room types, neighbourhoods, availability, and review activity, and present the findings through PivotTables, PivotCharts, KPI cards, and an Excel dashboard.

## Dataset
The project uses three cleaned Airbnb datasets:

- **Listings dataset** – 3,818 listings containing listing details, room types, neighbourhoods, prices, and ratings.
- **Calendar dataset** – 1,393,570 records containing listing availability, dates, prices, and time-related fields.
- **Reviews dataset** – approximately 84,849 review records containing listing IDs, review dates, reviewer information, and comments.

The large Calendar dataset was loaded into the **Excel Data Model / Power Pivot** because it exceeds the normal Excel worksheet row limit.

## Objectives
- Analyze Airbnb listing distribution by room type and neighbourhood.
- Compare average prices across room types, months, and days of the week.
- Measure monthly availability patterns.
- Analyze review activity by month and year.
- Identify the most-reviewed listings.
- Build a dashboard to communicate important business insights.

## Analysis Performed
Nine PivotTables and PivotCharts were created:

1. Listings by Room Type
2. Average Price by Room Type
3. Top 10 Neighbourhoods by Listing Count
4. Average Price by Month
5. Availability Rate by Month
6. Average Price by Day of Week
7. Reviews by Month
8. Top 10 Listings by Review Count
9. Reviews by Year

## Dashboard
The Excel dashboard contains KPI cards and nine visualizations for quick analysis.

### KPI Metrics
- **Total Listings:** 3,818
- **Average Price:** $137.94
- **Total Reviews:** 84,849
- **Availability Rate:** 67.1%
- **Average Rating:** 4.67

The dashboard combines charts for room type, neighbourhood, pricing, availability, and review trends.

## Key Insights
- Entire home/apartment listings form a major portion of the Airbnb inventory.
- The overall average listing price is approximately $137.94.
- Availability varies across months, with December showing an availability rate of approximately 73.6%.
- Review activity shows noticeable monthly variation.
- The most-reviewed listing in the analysis has 474 reviews.
- Pricing varies across room types, months, and days of the week.

## Recommendations
- Use room-type and neighbourhood trends to support listing and marketing decisions.
- Consider monthly pricing patterns when planning seasonal pricing strategies.
- Maintain availability during periods with stronger demand indicators.
- Study highly reviewed listings to identify successful hosting practices.
- Use review trends to support seasonal promotions and planning.

## Tools & Technologies
- Microsoft Excel
- Power Query
- Excel Data Model / Power Pivot
- PivotTables
- PivotCharts
- Excel Dashboard
- Data Visualization

## Project Workflow
1. Imported the cleaned Airbnb datasets.
2. Used Power Query for data preparation and transformation.
3. Created an `Available_Flag` field for availability analysis.
4. Loaded the large Calendar dataset into the Excel Data Model.
5. Created nine PivotTables for analysis.
6. Created PivotCharts from the PivotTables.
7. Designed an Excel dashboard with KPI cards and charts.
8. Summarized the key findings and recommendations.

## Project Structure
```text
Airbnb-Excel-Analysis/
│
├── data/
│   ├── listings_clean.csv
│   ├── calendar_clean.csv
│   └── reviews_clean.csv
│
├── Airbnb_Excel_Analysis.xlsx
│
└── README.md
```

## Author
**Thanay Gannu**

This project was created as a minor data analytics project using Excel to demonstrate data cleaning, analysis, visualization, and dashboard development.
