<img width="1140" height="645" alt="Screenshot (522)" src="https://github.com/user-attachments/assets/fab99228-853b-4224-a550-ced0741dc910" />

# Smart Office Occupancy Dashboard

A **Power BI dashboard** analyzing room occupancy and environmental sensor data from a smart office environment. The dashboard provides insights into **space utilization, user behavior, and environmental conditions**, supporting data-driven decisions for product strategy and operational optimization.

## Features

- **Occupancy Heatmap**: Visualizes occupancy patterns by day and hour, highlighting peak usage and underutilized time slots.
- **KPI Cards**: Summarizes total sessions, average occupancy, peak usage hour, session durations, and overall utilization.
- **Session Analytics**: Detailed tables and plots showing session duration, maximum occupancy, and distribution of sessions.
- **Sensor Insights**: Visualizes relationships between sensor readings (temperature, light, CO2, sound) and occupancy.

## Data Processing

- Sessions defined by occupancy changes or gaps greater than 15 minutes.
- Occupancy flags and session durations computed from timestamped data.
- Hourly and daily KPIs generated for visualization.
- Sensor correlations analyzed to identify environmental factors affecting occupancy.

## Tech Stack

- **Power BI** – Dashboard creation and visualization
- **Python / Pandas** – Data preprocessing and session calculations

## Purpose

The dashboard allows stakeholders to quickly understand **how customers interact with the Smart Office**, providing insights for space optimization, feature development, user behavior and customer success.

## Usage

1. Open the Power BI `.pbix` file included in this repository.
2. Explore visuals such as heatmaps, KPI cards, session analytics, and sensor trends.
3. Use slicers or filters to analyze occupancy by day, hour, or sensor type.

## License

This project is for educational and portfolio purposes.
