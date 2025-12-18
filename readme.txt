🚲 London Bike Sharing Analysis (Tableau)

Project Overview
This project analyzes London bike-sharing patterns using historical ride and weather data. The goal was to understand how factors such as season, weather, temperature, and wind speed influence bike usage over time.

Dataset
Source: Kaggle – London Bike Sharing Dataset
Time period covered: 2015–2017

Key Features Used
	•	Ride count
	•	Date & time (daily / weekly aggregation)
	•	Season (mapped from numeric codes)
	•	Weather conditions (mapped from numeric codes)
	•	Temperature (°C)
	•	Wind speed (km/h)

Data Preparation
	•	Cleaned and transformed data in Excel
	•	Created readable labels using mappings:
	•	Seasons (Spring, Summer, Autumn, Winter)
	•	Weather conditions (Clear, Cloudy, Rain, Snow, etc.)
	•	Created calculated fields in Tableau (e.g., total rides, moving averages)

Visualizations
	•	19-week moving average trend of bike rides
	•	Time-series analysis of ride volume
	•	Heatmap showing ride intensity by temperature vs wind speed
	•	Interactive filters for time and conditions

Key Insights
	•	Bike usage peaks during summer and clear weather
	•	Extreme cold, high wind, and heavy rain significantly reduce rides
	•	Moving averages highlight strong seasonal patterns

🔗 Tableau Public Dashboard:
https://public.tableau.com/shared/Q9C7Y5SF3?:display_count=n&:origin=viz_share_link