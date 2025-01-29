# MTA Subway Operational Metrics Dashboard Analysis Report

<Tablau Dashboard>https://public.tableau.com/app/profile/yue.hu7240/viz/MTASubway/Overview
## 1. Introduction
This report presents insights derived from the MTA Subway Operational Metrics Dashboards, which utilize data spanning January 2020 to November 2024 from data.ny.gov. The analysis aims to provide an in-depth understanding of subway service performance, ridership trends, station utilization, delays, and incidents.

## 2. Data Sources and Key Metrics
The analysis integrates six primary datasets:

1. **MTA Subway Service Delivered**: Tracks the percentage of scheduled trains operating during peak hours.
2. **MTA Daily Ridership and Traffic**: Captures daily subway ridership estimates systemwide.
3. **MTA Subway Stations**: Contains information on subway stations, including locations and identifiers.
4. **On-Time Performance**: Measures the percentage of trains arriving at terminal locations within five minutes of their scheduled time.
5. **MTA Subway Trains Delayed**: Provides details on the number and percentage of delayed trains and associated delay categories.
6. **Major Incidents**: Records significant incidents affecting 50 or more trains.

## 3. Data Processing and Preparation
To ensure consistency and usability across datasets, the following steps were undertaken:

- **Date Formatting**: Converted the month field to a standardized date format for temporal analysis.
- **Line Name Mapping**: Standardized line names across datasets for accurate integration and visualization.

## 4. Dashboard Design Overview

### 4.1 Overview Dashboard
The Overview dashboard provides a high-level visualization of four key operational metrics:

- **Service Delivered**: The percentage of actual service compared to scheduled service during peak times.
- **Ridership**: Fluctuations in monthly ridership.
- **On-Time Performance**: Patterns in punctuality across time periods.
- **Incident Percentage**: Proportion of trains impacted by major incidents.

### 4.2 Station Dashboard
Focuses on station-level metrics, with features including:

- **Station Count by Borough**: Breakdown of lines and stops by borough (excluding Staten Island).
- **Top 10 Stations and Lines**: Based on scheduled line counts and ridership data.
- **Interactive Subway Map**: Allows filtering by lines and stops for geographic visualization.

### 4.3 Delays & Incidents Dashboard
Delivers insights into delays and incidents, with:

- **Delayed Lines and Reasons**: Breakdown of delays by line and associated reporting reasons.
- **Incident Lines and Reasons**: Analysis of incidents by line and disruption causes.
