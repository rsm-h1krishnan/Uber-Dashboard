Uber Trip Analysis: Data-Driven Operational Insights

Project Overview
This project involved a comprehensive analysis of Uber trip data using Power BI to decode complex booking trends, revenue streams, and trip efficiencies. By transforming raw data into three specialized dashboard layers, this analysis provides stakeholders with the granular insights needed to optimize driver allocation, refine pricing models, and enhance customer satisfaction.

Strategic Business Objectives
The primary goal was to move beyond static reporting to a dynamic decision-support system. The analysis focused on:

Trend Identification: Pinpointing daily and hourly fluctuations in ride demand.

Operational Efficiency: Evaluating trip performance in terms of average distance (3 miles) and duration (16 min).

Financial Impact: Analyzing revenue patterns across different payment methods and vehicle types.

Demand Forecasting: Mapping high-traffic pickup and drop-off points to optimize driver positioning.

Key Performance Indicators (KPIs)
The dashboard monitors six high-level metrics to provide an immediate snapshot of health:

Total Bookings: 103.7K trips.

Total Booking Value: $1.6M in gross revenue.

Avg Booking Value: $15.00 per ride.

Total Trip Distance: 349K miles covered.

Avg Trip Distance & Time: 3 miles / 16 minutes.

Technical Implementation & Dashboard Architecture
1. Overview Analysis (Strategic Layer)
Focused on the "Big Picture," this dashboard uses a Disconnected Table and Measure Selector to allow users to toggle the entire view between Total Bookings, Booking Value, and Distance.

Payment & Trip Type: Breakdown of Card vs. Cash usage and Day vs. Night patterns (34.72% of trips occur at night).

Vehicle Grid: A matrix view evaluating performance across different vehicle categories with conditional formatting to highlight outliers.

2. Time Analysis (Operational Layer)
Designed to optimize driver supply, this layer utilizes a Heatmap (Hour of Day vs. Day of Week) to visualize "hot zones" for demand.

Demand Peaks: Area charts track bookings in 10-minute intervals to identify exact rush-hour windows.

Weekly Cycles: Line charts compare weekday vs. weekend demand (Sat/Sun showing peak volumes of 18.7K - 19.2K).

3. Details & Location Analysis (Granular Layer)
Leverages Drill-Through functionality and complex data modeling (activating inactive relationships) to track the journey from specific Pickup points to Drop-off locations.

Top 5 Locations: Identifies the highest-traffic zones for strategic resource allocation.

UI Enhancements: Includes "Clear All Filters" buttons and Bookmarks for a seamless, app-like user experience.

Top Insights
Peak Demand: Demand rises steadily through the morning, peaking in the late afternoon/evening hours (15:00 - 18:00).

Revenue Concentration: Weekend bookings significantly outperform mid-week numbers, suggesting a need for weekend-specific surge pricing or driver incentives.

Trip Efficiency: With an average trip of 3 miles taking 16 minutes, the data suggests heavy urban congestion or short-distance city commuting as the primary use case
