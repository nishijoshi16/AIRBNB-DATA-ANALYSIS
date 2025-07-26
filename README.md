# AIRBNB-DATA-ANALYSIS
📌 1. Project Title: Airbnb Listings Analysis: Comprehensive Market Insights Dashboard

🧭 2. Purpose: This project provides a concise, visual analysis of Airbnb to offer quick insights into market trends, host activities, property performance, and seasonal demand. It aims to help users understand key dynamics and make informed decisions within the NYC Airbnb ecosystem.


🛠️ 3. Tech Stack Used:

📊 Power BI – for interactive data visualization

📐 DAX (Data Analysis Expressions)

🗺️ Microsoft Bing Maps Integration

🧩 Custom Visuals

🎨 Color Coding & Icons

📂 4. Data Source: Kaggle

PAGE 1: Airbnb Listings Analysis: Unveiling Trends:

<img width="1444" height="770" alt="1" src="https://github.com/user-attachments/assets/119bbee7-7250-42b9-bebe-3f4fb115bc76" />


🌟 1. Features and Highlights: This interactive dashboard addresses several key business problems and provides valuable insights:

🎯 2. Business Problems Addressed:

📊 Pricing Strategy: What's the average listing price, and how does it vary?

🏘️ Competitive Landscape: Who are the busiest hosts, and which neighborhoods are most saturated?

🏡 Property Performance: Which property types are most popular, and how do reviews fluctuate throughout the year?

🧑‍💼 Host Performance: Identifying the host with the most properties and the property with the highest reviews.

📈 3. Dashboard Walkthrough & Visuals:

📈 Overall Summary Metrics:

💰 Avg price ($151.64): Provides a quick understanding of the average cost of an Airbnb stay in NYC.

📍 Max no properties listed (Manhattan): Indicates the neighborhood with the highest number of listings, highlighting a dense market.

👤 Busiest host (Michael): Identifies the individual host with the highest activity, suggesting a significant player in the market.

🏘️ Host of max properties listed (Michael): Reconfirms Michael as a dominant host based on property count.

⭐ Property with max reviews (Room near JFK Queen Bed): Highlights a highly-rated property, potentially indicating strong guest satisfaction.

📊 Host Performance Analysis:

📊 "Count of calculated_host_listings_count by host_name" Bar Chart: Clearly visualizes the top hosts by the number of listings, with "Michael" leading significantly (416 listings), followed by "David" (402) and "Sonder (NYC)" (327). This helps in understanding the distribution of listings among hosts.

🗺️ Geographical Distribution of Listings & Prices:

📋 "neighbourhood_group" Table with "Count of price": Shows the overwhelming concentration of listings in Manhattan (21,598) and Brooklyn (20,057), which also likely correlates with higher average prices. Other boroughs like Queens, Bronx, and Staten Island have significantly fewer listings. This is crucial for understanding market density and potential demand in different areas.

🏠 Property Type Insights:

📊 "Count of number_of_reviews by room_type" Bar Chart: "Entire home/apt" and "Private room" dominate in terms of review counts (both around 20K+), indicating their popularity. "Shared room" has significantly fewer reviews (around 1K), suggesting less usage or preference.

📊 "Count of availability_365 by room_type" Bar Chart: Shows that "Entire home/apt" and "Private room" both have high availability (366 days, suggesting year-round listings), while "Shared room" has less (232 days), perhaps due to owner occupancy or different usage patterns. This gives insight into the supply of different room types.

📆 Seasonal Trends in Reviews:

📈 "Count of reviews_per_month by Month" Line Chart: Reveals a clear seasonal pattern in reviews, with a peak in July (801 reviews) and August (831 reviews), followed by a decline in the latter half of the year. This suggests highest visitor activity during the summer months in NYC, which is valuable for pricing and marketing strategies.


💡 4. Impacts and Analysis:

🎯 Strategic Pricing: The average price provides a benchmark, and neighborhood-specific data can inform dynamic pricing strategies for hosts.

🚀 Market Entry & Competition: New hosts can identify less saturated neighborhoods or understand the level of competition from existing hosts like "Michael."

📌 Optimized Listing Strategies: Knowing the popularity of "Entire home/apt" and "Private room" can guide potential hosts on what type of property to list.

🛠️ Resource Allocation: The seasonal review trend can help hosts anticipate peak seasons for staffing, maintenance, and marketing efforts.

🧳 Understanding Guest Behavior: The high review counts for specific property types and the seasonal trends indicate guest preferences and travel patterns in NYC.

PAGE 2: Airbnb Listings Analysis: Deep Dive into Room Types and Host Performance:

<img width="1444" height="770" alt="2" src="https://github.com/user-attachments/assets/a2aa9532-b9c7-46e2-852c-b3e5e93dd33c" />


🌟 1. Features and Highlights: This dashboard view provides focused insights into specific aspects of the Airbnb market, addressing key business questions:

🎯 2. Business Problems Addressed:

🏡 Property Popularity: Which specific listings are receiving the most reviews, indicating high guest satisfaction or booking volume?

🛏️ Room Type Dominance: What is the overall distribution and total count of different room types (entire home/apt, private room, shared room)?

🌍 Host Geographical Spread: How do top hosts distribute their listings across different New York City boroughs?

📍 Neighborhood Listing Density: Which neighborhoods have the highest concentration of Airbnb listings?

📈 3. Dashboard Walkthrough & Visuals:

📊 Overall Room Type Distribution & Counts:

📌 "Total room type" (3): Confirms that there are three distinct room types being analyzed.

🏠 "Entire home/apt" (25.35K): Shows that "Entire home/apt" is the most prevalent room type by count.

🚪 "Private room" (22.23K): Indicates that "Private room" is also highly common, just slightly less than "Entire home/apt".

🧑‍🤝‍🧑 "Shared room" (1158): Highlights that "Shared room" constitutes a very small fraction of the total listings.

📈 These summary cards immediately give a high-level overview of the supply breakdown.

🌟 Top Reviewed Properties:

📊 "Max of number_of_reviews by name" Bar Chart: Displays a ranked list of individual properties with the highest number of reviews. "Room ne..." leads with 629 reviews, followed by "Great Be..." (607), and "Beautiful..." (597). This visual is valuable for identifying highly-rated or frequently booked listings, which could be benchmarks for new hosts. 📅 The date filter (3/28/2011 - 7/22/2025) suggests the analysis covers a broad historical period.

🛏️ Room Type Count Breakdown:

📉 "Count of id by room_type" Bar Chart: Graphically reinforces the dominance of "Entire home/apt" (approx. 25K) and "Private room" (approx. 22K) over "Shared room" (approx. 1K), providing a clear visual representation of the supply.

🌆 Host Listings by Borough:

📋 Table showing "host_name" vs. "Boroughs" (Brooklyn, Manhattan, Queens, Staten Island, Total): This crucial table details how key hosts distribute their listings geographically. For instance, "Michael" has a significant presence in Manhattan (211 listings) and Brooklyn (159), highlighting their broad reach. "David" also shows a strong presence in Manhattan (201). This provides insight into the strategic footprint of top hosts.

🗺️ Neighborhood Listing Concentration:

📋 Table showing "neighbourhood_group" vs. "Count of calculated_host_listings_count": This table re-emphasizes the high density of listings in Manhattan (21,598) and Brooklyn (20,057), confirming them as the primary Airbnb hubs in NYC. Other boroughs have significantly fewer listings, which could indicate less market saturation or lower demand.

💡 4. Impacts and Analysis:

📌 Benchmarking for Hosts: Hosts can use the "Max of number_of_reviews" list to understand what makes a listing highly successful and potentially emulate features or service quality.

🔍 Market Opportunity Identification: The room type distribution clearly shows that "Entire home/apt" and "Private room" are the most common and likely in demand. This informs potential hosts about the most viable listing types. The low number of "Shared rooms" might suggest a niche market or less demand.

📊 Competitive Intelligence: The "Host listings by borough" table allows for an understanding of the geographical strategy of major players. A new host can identify if a top competitor is strong in their target borough.

📍 Strategic Location Planning: The "Neighborhood listing concentration" data is vital for anyone looking to enter the market, guiding them to areas with high existing supply (potential high competition) or lower supply (potential for growth).

🔗 Supply Chain Understanding: The breakdown by room type and neighborhood provides a clear picture of the Airbnb supply landscape in New York City, crucial for market analysis and policy-making.

📈 Overall Conclusion: The analysis concludes that the NYC Airbnb market is primarily concentrated in Manhattan and Brooklyn, dominated by "Entire home/apt" and "Private room" listings. Key hosts manage substantial portfolios across these boroughs. A clear seasonal peak in activity is observed during summer, particularly July and August. These findings are crucial for hosts to strategize pricing and property types, and for all stakeholders to understand market supply and demand.
