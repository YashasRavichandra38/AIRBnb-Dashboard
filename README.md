# AIRBnb-Dashboard

Introduction
The objective of this analysis is to determine the best location to buy a home for rental purposes, based on an evaluation of pricing trends, revenue potential, and customer demand.

Data Overview
The project utilizes several datasets:

Listings and Calendar Data: Tracks the availability and pricing of listings over time.
Listings Information: Detailed information about each listing, including descriptions, amenities, and URLs.
Reviews Data: Customer reviews for various listings, including reviewer details and comments.
Datasets and Screenshots
Listings and Calendar Data

Columns: listing_id, date, available, price.
Description: This dataset tracks the availability and pricing of a specific listing over a period in December 2016.

Tableau Dashboard

Visualizations:
Price by Zipcode: A bar chart showing average prices per zipcode.
Price per Zipcode (Map): A map visualizing average prices in different regions.
Revenue per Month: A line chart showing revenue trends over months in 2016.
Distinct Count of Bedrooms: A bar chart showing the count of listings based on the number of bedrooms.
Average Price of Bedrooms: A bar chart depicting the average price based on the number of bedrooms.
Description: The dashboard provides insights into geographical pricing trends, revenue patterns, and bedroom configurations.

Listings Information

Columns: listing_url, scrape_id, last_scraped, name, summary, space, description.
Description: This dataset includes detailed information about each listing, including its URL, last scrape date, name, summary, space, and description.

Reviews Data

Columns: listing_id, id, date, reviewer_id, reviewer_name, comments.
Description: This dataset includes individual reviews for various listings, along with reviewer details and their comments.

Analysis and Findings
Price by Zipcode

Analysis: The bar chart shows the average prices per zipcode, revealing which areas have higher or lower average prices.
Finding: Zipcode 98146 has the highest average price, indicating it might be a premium area.
Price per Zipcode (Map)

Analysis: The map visualization displays average prices across different regions, providing a geographical perspective on pricing.
Finding: Northern and central areas tend to have higher prices compared to the outskirts.
Revenue per Month

Analysis: The line chart depicts revenue trends over the months in 2016.
Finding: Revenue peaked around mid-year (May to July) and slightly declined towards the end of the year.
Distinct Count of Bedrooms

Analysis: The bar chart shows the number of listings based on the number of bedrooms.
Finding: Most listings have 1 or 2 bedrooms, with a significant drop in listings with more bedrooms.
Average Price of Bedrooms

Analysis: The bar chart depicts the average price based on the number of bedrooms.
Finding: Listings with more bedrooms have higher average prices, with a significant jump for 5 and 6-bedroom listings.
Listings Information

Analysis: Detailed information about each listing helps in understanding the characteristics and unique selling points.
Finding: Descriptions and amenities vary significantly, influencing the pricing and attractiveness of listings.
Customer Reviews

Analysis: Reviews provide insights into guest experiences and satisfaction levels.
Finding: Common themes in positive reviews include great locations, friendly hosts, and comfortable accommodations.
Conclusion
This project provided valuable insights into the Airbnb listings data, revealing pricing trends, revenue patterns, and customer feedback. Key findings include the identification of high-priced areas, peak revenue periods, and the importance of listing characteristics such as the number of bedrooms and detailed descriptions. These insights can help Airbnb hosts optimize their listings and enhance guest experiences.

Recommendations
Optimize Pricing: Adjust pricing based on geographical trends and peak seasons to maximize revenue.
Enhance Descriptions: Provide detailed and attractive descriptions to stand out among listings.
Focus on Customer Experience: Address common feedback themes to improve guest satisfaction and attract more positive reviews.
Analyze Further: Continuously monitor and analyze data to stay updated with market trends and adjust strategies accordingly.
