# Airbnb-Listing

![Airbnb Listing Dashboard](https://github.com/user-attachments/assets/afdd561d-8b54-4395-934c-094517d52f8e)

Dashboard Link: https://public.tableau.com/app/profile/huzaifa.tambal/viz/AirbnbListings_17255485923850/Dashboard1
# Objective:
This project focuses on analyzing Airbnb listing data to uncover insights about nightly pricing, price trends, and bedroom availability across different regions.

# Data Sources:
The data used in this project comes from Kaggle and includes three separate files:

- Listings Data: Contains detailed information about Airbnb properties, such as cancellation policies, instant booking availability, and reviews per month.
- Reviews Data: Includes customer feedback, review dates, and reviewer names.
- Calendar Data: Provides availability and pricing information for each listing on a daily basis.

These datasets were joined in Tableau using an inner join, with the common field being the id for Airbnb listings.

# Data Cleaning and Preparation:
Before creating visualizations, the data was cleaned and prepared by:

- Removing duplicates
- Filtering irrelevant fields
- Ensuring consistent data types for key metrics such as pricing and review counts

# Key Visualizations in the Dashboard:
- Average Price for One Night Per Bedroom:

Visualization Type: Bar Chart

Description: This chart shows the average nightly price for listings grouped by the number of bedrooms. It helps identify how the price varies based on the size of the property.
- Price Per Zipcode:

Visualization Type: Map and Bar Chart

Description: A map visualization displays the price distribution geographically across different zip codes, allowing users to quickly identify the most expensive and affordable areas. Accompanying the map, a bar chart shows more detailed pricing data by zip code.
- Price Trend:

Visualization Type: Line Chart

Description: This line chart tracks the changes in average price over time, providing insights into seasonal trends or market shifts that affect Airbnb pricing.
- Distinct Count of Bedrooms Listings:

Visualization Type: Text Box

Description: A simple text box displays the total count of listings available for each number of bedrooms, giving a quick overview of the distribution of bedroom availability.
# Filters Added:
- A filter was added to the Distinct Count of Bedrooms Listings to allow users to view data based on different bedroom counts.
- Another filter was applied to the Price Per Zipcode visualization to enable users to explore pricing data for specific zip codes.

# Key Insights:
- Average Price vs. Bedroom Count: The analysis reveals that properties with more bedrooms generally command a higher average price.
- Regional Price Differences: The map highlights notable price differences across zip codes, with certain areas showing significantly higher pricing than others.
- Price Trends Over Time: The line chart shows clear seasonal trends, with pricing increasing during peak travel months.

# Conclusion:
This dashboard provides a comprehensive view of Airbnb pricing data, helping property owners and prospective hosts understand pricing dynamics across regions and over time. It also offers insights into how property characteristics, such as the number of bedrooms, influence nightly pricing.

