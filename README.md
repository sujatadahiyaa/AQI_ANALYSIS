**Air Quality Index (AQI) Analysis Dashboard**

Interactive Power BI dashboard analyzing city-level Air Quality Index (AQI) data — KPI cards, geo-mapped pollution hotspots, top polluted cities, and AQI trends. A second page breaks down dominant pollutants (PM2.5, PM10, SO2, O3, NO2, CO) with city-wise comparisons and category distribution charts.

📁 **Dataset**

- **City** – location of each air quality reading
- **AQI** – composite Air Quality Index score
- **AQI_Category** – classification band (Good, Moderate, Poor, Severe, etc.)
- **Dominant_Pollutant** – the pollutant driving the AQI score at that location
- **PM2_5, PM10** – particulate matter concentrations
- **SO2, O3, NO2, CO** – gaseous pollutant concentrations

🖥️ **Dashboards**

**1. Air Quality Index Overview**


- KPI cards: Average, Max, and Min AQI
- Geo-map visualizing AQI by city
- "Top 10 Polluted Cities" ranked bar chart
- AQI trend chart across categories
- Slicers for City & AQI Category, plus a custom theme toggle

**2. Pollutant Analysis**


- Pollutant breakdown by dominant pollutant (PM2.5, PM10, SO2, O3, NO2, CO)
- City-wise comparison across all six pollutants
- Donut chart showing AQI category distribution
- Consistent KPI cards, slicers, and theme toggle for UX continuity


**🛠️Tech & Skills Used**

- Power BI Desktop
- DAX measures (Avg/Max/Min AQI calculations)
- Data modeling & relationships
- Geo-spatial visualization
- Interactive slicers & dynamic theming
- Dashboard UX/storytelling design


🎯 **Purpose**

This project transforms raw environmental readings into an actionable, at-a-glance tool for spotting pollution hotspots and understanding which pollutants are driving poor air quality in specific cities — useful for researchers, planners, or anyone exploring environmental data analytics.


🚀**How to Use**


1. Clone or download this repository.
2. Open AQI_ANALYSIS.pbix in Power BI Desktop (free download from Microsoft).
3. Use the slicers (City, AQI Category) to filter the data.
4. Toggle the theme switcher to change the report's look and feel.
5. Explore both report pages via the tabs at the bottom of the report.


**📸 Screenshots**

<img width="930" height="434" alt="P4" src="https://github.com/user-attachments/assets/23a730d8-700e-468b-8883-94b7bb872a47" />

<img width="930" height="434" alt="p2" src="https://github.com/user-attachments/assets/f87e8fb5-24e4-451d-a786-eb8b2a052f2e" />
