# Namma-Yatri-Trips-Analysis
This repository contains all the essential files and documentation needed to understand, implement, and explore the Namma Yatri data dashboard. The project leverages Power BI for data visualization, SQL for data extraction and manipulation, and Excel for raw data storage.

## Project Overview

Namma Yatri is a community initiative aimed at providing a seamless auto and cab booking experience across several cities including Bengaluru, Delhi, Hyderabad, Chennai, Kochi, Mysore, and Tumkur. This project is designed to track and visualize key performance metrics of the service, providing insights into operations, user engagement, and financial performance.

### Key Components:

1. **Data Visualization (Power BI)**:
   - **Purpose**: The data dashboard is designed to give an at-a-glance view of crucial metrics, including the number of completed trips, search activities, fare estimates, driver earnings, and conversion rates.
   - **Visuals**:
     - **Trips vs Duration**: Visualizes the relationship between the number of trips and their duration.
     - **Fare vs Duration**: Shows how the fare correlates with trip duration.
     - **Distance vs Duration**: Displays the relationship between distance traveled and trip duration.
     - **Trip Fare by Location**: Compares total fare earnings across different locations.

2. **Data Extraction and Manipulation (SQL)**:
   - **Purpose**: SQL scripts are used to extract, transform, and load data into a structured format that can be utilized by the Power BI dashboard. These scripts handle data from various sources, ensuring it is clean, organized, and ready for analysis.

3. **Raw Data Management (Excel)**:
   - **Purpose**: Excel is used to store raw data, including trip details, fare information, and location-specific metrics. This data acts as a foundational layer for the analysis and visualization processes.
   - **Contents**:
     - Detailed trip records
     - Fare breakdowns
     - Search and quote data
     - Location-based metrics

### How to Set Up and Use the Dashboard

1. **Database Setup**:
   - Run the provided SQL scripts in your preferred database management system to create necessary tables and extract relevant data. This step is crucial for populating the dashboard with accurate, up-to-date information.

2. **Power BI Dashboard**:
   - Open the Power BI project to interact with the pre-built dashboard. Ensure the data connections to your database and Excel files are properly configured.
   - The dashboard allows for dynamic exploration of metrics, with filters and interactive visuals enabling deeper dives into specific aspects of the service.

3. **Data Updating**:
   - Regular updates to the Excel data or rerunning SQL queries will refresh the Power BI dashboard, ensuring it reflects the most current information.

### Usage and Insights

This dashboard is designed to be used by data analysts, business managers, and other stakeholders within the Namma Yatri ecosystem. It provides actionable insights into how the service is performing, where improvements can be made, and what trends are emerging in customer behavior and service delivery.

Whether you are tracking overall performance, analyzing specific trips, or comparing data across different locations, this tool is designed to be both comprehensive and user-friendly.

## About Namma Yatri

Namma Yatri is dedicated to providing an efficient and reliable transport service across various Indian cities. By utilizing this dashboard, stakeholders can ensure that the service is continuously optimized to meet user expectations and operational goals.
