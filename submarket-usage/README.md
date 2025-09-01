
# Submarket Usage Dashboard

![Dashboard Screenshot](screenshot.png)

## Business Question
Which submarkets generate the most dealroom activity, and what share of property listings are being converted into dealrooms?  
Purpose: Allow market directors to see which submarkets have the most deals and make informed hiring decisions.  
This dashboard design is flexible and can be used across any market, not just Los Angeles.

## Dataset
- Source: Real estate listings and dealroom creation logs (anonymized).  
- Granularity: Submarket-level aggregation with listings, dealrooms, and % conversion.  
- Period Covered: Current quarter.  
- Key Metrics: Number of Listings Added, Number of Dealrooms Created, % Conversion.  

## Approach
- Tabular summary of listings and dealrooms by submarket.  
- Conversion rate calculated as dealrooms ÷ listings.  
- Stacked bar chart to compare submarkets across organizations.  

## Key Insights
- Concentration in central business districts and prime submarkets drives dealroom creation.  
- Certain submarkets show strong dealroom adoption (high conversion %).  
- Smaller submarkets have negligible dealroom activity.  
- Organizational activity: Certain firms dominate dealroom creation in specific submarkets.  

## What I'd Do Next
- Add filters for organization and time to analyze adoption patterns.  
- Benchmark dealroom conversion vs. pipeline progression.  
- Introduce heatmaps to quickly visualize submarket intensity.  

## Tech Stack
- Tableau (visualization)  
- SQL (data preparation)

