# Weather Data Analysis Dashboard — India (2014–2021)

An interactive Power BI dashboard for exploring and analyzing historical weather data collected from airports/weather stations across India between 2014 and 2021.

The project focuses on understanding how weather conditions vary across different locations, dates, months, years, and times of the day. The dashboard provides interactive visual analysis of multiple meteorological parameters and was also used as part of a research study.

## Dashboard Preview

![Weather Data Dashboard](images/weather-dashboard.png)

## What the Dashboard Does

The Power BI report allows users to interactively explore weather data using filters and visualizations.

The main dashboard includes filters for:

- **Time** — analyze weather conditions at different times of the day
- **Date** — examine specific dates
- **Month** — compare weather conditions across months
- **Year** — analyze trends across different years
- **Station Name** — compare weather conditions across different airports/weather stations

All visuals update dynamically based on the selected filters.

### Temperature & Dew Point Analysis

The dashboard shown above compares:

- Average Dry Bulb Temperature
- Average Wet Bulb Temperature
- Average Dew Point

The line chart makes it possible to observe how these measurements change throughout the day for a selected location and time period.

The dashboard also displays summary metrics such as maximum and minimum dry-bulb temperature and average dry-bulb temperature for the selected filters.

## Other Weather Parameters

The Power BI report contains additional report pages for analyzing other meteorological parameters, including atmospheric pressure and other weather-related measurements.

These pages allow the same dataset to be explored from different weather perspectives while retaining interactive filtering by location, date, month, year, and time where applicable.

## Data

- **Data period:** 2014–2021
- **Geographical coverage:** Airports/weather stations across India
- **Data source:** Indian Meteorological Department (IMD)
- **Data type:** Historical meteorological observations

## Key Objectives

- Analyze historical weather patterns across different locations in India
- Study variations in weather conditions throughout the day
- Compare meteorological measurements across months and years
- Explore relationships between different weather parameters
- Build an interactive dashboard for easier interpretation of large-scale weather data

## Research

The analysis was also used as part of a research publication based on the study of meteorological data.

**Research Paper:** [Add research paper link here]

## Technologies Used

- **Power BI** — interactive dashboards, data modeling, visualizations, and filters
- **Python** — data processing and analysis
- **SQL** — data handling/querying where applicable
- **Machine Learning** — Ridge Regression and Random Forest analysis as part of the broader project/research work

## Repository Structure

```text
Weather-Data-Analysis/
│
├── README.md
├── WeatherData.pbix
├── images/
│   └── weather-dashboard.png
└── data/
    └── README.md
```

> The raw dataset is not included in this repository if it is subject to source or usage restrictions.

## How to Explore the Dashboard

1. Download the `.pbix` Power BI report.
2. Open it using **Power BI Desktop**.
3. Select a station, year, month, date, or time using the available filters.
4. Explore the charts and summary metrics.
5. Navigate between report pages to analyze different meteorological parameters.

## Project Highlights

- Interactive Power BI dashboard
- Multi-dimensional filtering by location and time
- Historical weather analysis covering 2014–2021
- Multiple meteorological parameters
- Visual analysis of daily and long-term weather patterns
- Research-oriented data analysis
