# Classic Models Sales Dashboard

## Overview
A comprehensive Power BI dashboard providing actionable insights into Classic Models' sales performance, profitability, and market trends. This interactive analytical tool enables executives and sales managers to make data-driven decisions by exploring key metrics across products, regions, and customer segments.

## Tech Stack
- **Data Processing**: MySQL (using advanced queries including JOINs, CTEs, and window functions)
- **Visualization**: Power BI
- **ETL**: Direct connection between MySQL and Power BI with query optimization

## Data Source
The dataset was generated from a SQL script ([available here](https://drive.google.com/file/d/1JCCVHkm3lpjj-JCdCIapFnoPNwpZl5Mi/view?usp=sharing)) containing:
- Product catalog data
- Customer records
- Order transactions
- Regional office information
- Payment records

## Key Features

### Interactive Analytics
- Dynamic toggles between Sales and Net Profit views
- Product category filters (Vintage Cars, Ships, Planes, etc.)
- Time period selectors

### Core Visualizations
- Profitability by product line analysis
- Cost efficiency scatter plots
- Regional performance comparisons
- Market potential by country
- Sales distribution (USA vs. Rest of World)
- Temporal order trends (volume and value)

### Advanced Features
- Interactive decomposition tree for profit driver analysis
- Comprehensive sales table with:
  - Monthly performance metrics
  - Month-over-Month % change (MoM%)
  - Year-to-Date (YTD) cumulative figures
- Customer segmentation capabilities

## Business Insights Delivered

### Product Performance
- Identification of high-margin product lines
- Cost structure comparisons across categories
- Profitability drivers by product type

### Market Analysis
- Geographic markets with highest growth potential
- Regional office performance benchmarking
- USA vs. international market comparisons

### Temporal Trends
- Order volume patterns over time
- Average order value fluctuations
- Seasonal performance variations

### Customer Insights
- Key customer contribution analysis
- Customer segmentation by spend and product preference
- High-value customer identification

## Implementation Notes
- Utilized complex SQL joins to connect transactional, product, and customer data
- Implemented CTEs for modular query design
- Created calculated measures in Power BI for dynamic metric switching
- Designed user-friendly navigation with intuitive filtering

## How to Use
1. Clone this repository
2. Import the SQL script into MySQL
3. Connect Power BI to your MySQL instance
4. Open the provided Power BI file to explore the dashboard
