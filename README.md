<h1> Rise in Global Temperatures & Predictions </h1>

![b57be4aaf0e4679a35924d2a8d60432e](https://github.com/user-attachments/assets/3a92f6ee-a11d-4e23-99ca-8dbf54e11aae)

<h2> Data Source </h2>
The data provided comes from [NOAA, Climate Data Online](https://www.ncei.noaa.gov/cdo-web/datasets/), which gives all types of data from the past and future predictions.

<h2> Business Problem/Solution </h2>

The risk of extreme weather events such as droughts, floods, and hurricanes is expected to rise which complicates resource planning, insurance costs, and operational stability. Additionally, regulatory pressures are likely to grow as governments strive to meet international climate goals. To address this, companies are adopting predictive analytics and data-driven models to assess future climate risks and implement adaptive strategies. For example, agricultural companies could leverage climate data to optimize crop selection, while insurers can refine risk assessments based on location-specific climate forecasts. These predictive tools enable businesses to make informed decisions that reduce their carbon footprint, mitigate risks, and improve resilience to climate impacts.

It raises the question for businesses. 
<b> 
- What is causing the climate to drastically change overtime? 
- What areas are being affected the most?
- What natural disaster will be the main concern as the climate changes?
- How does one prepare for what's to come?
</b>

![6ecface122f0a1ea71a440918156a919](https://github.com/user-attachments/assets/443c4d0c-7df8-4eeb-ae3a-a466d6a9cb5c)

<h2> Data Cleaning </h2>

I cleaned over 16 .csv files from National Centers For Environmental Information (NOAA) using Google Sheets, eliminating unnecessary data, filling in empty slots, and reorganizing before importing 10 tables to BigQuery.

1. <b>normals_monthly:</b> monthly typical climate conditions for thousands of locations across select locations, consisting of 8 columns and 163 rows.
2. local_climatological_data: summary of daily extremes and averages of temperature, degree days, weather, sea level pressure, and extreme wind speeds.
3. flooding: monthly precipitation observations for all countries, consisting of 7 columns and 195 rows.
4. heat_stress: areas with higher exposure to heat related risks, consisting of 3 colummns and 56 rows.
5. water_stress: areas with higher exposure to water related risks, consisting of 3 colummns and 37 rows.
6. wildfires: weather conditions associated with wildfires, consisting of 4 columns and 90 rows.
7. hurricane_typhoons: areas that are most vulnerable to hurricanes and typhoons, 4 columns and 56 rows.
8. sea_level_rise: data showing areas being affected as sea levels rise, consisting of 6 columns, and 165 rows.
9. temperature_change: exposure to climate impacts, resilience, greenhouse gas emissions, and energy use, consisting of 9 columns and 195 rows.
10. snowfall_index: rating scale factors in population, snowfall amounts, and storm coverage in select locations, consisting of 5 columns and 148 rows.


