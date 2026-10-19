# OLA Data Analysis and Visualization Project

This repository showcases a data analysis and visualization project based on OLA ride-booking data using Microsoft Power BI. The project focuses on exploring ride-booking performance, vehicle-related insights, customer behaviour, and rating patterns through interactive dashboards. It aims to present data in a clear and meaningful way to support business analysis and decision-making.

---

## Project Objective

The objective of this project is to analyze OLA ride-booking data and develop interactive dashboards to explore:

- Overall ride-booking performance and key metrics.
- Vehicle-related trends and performance.
- Customer behaviour and booking patterns.
- Customer and driver rating patterns.
- Business insights through interactive data visualizations.

---

Repository Structure
This repository contains the following files and folders:

1. OLA-Data-Analyst-Project.pdf
    Blueprint of the project, detailing:
  SQL queries.
  Power BI dashboards.
  Segregation of insights and visualizations.
2. https://github.com/Poojasri-25/OLA-Data-Analysis-and-Visualization-Project/blob/main/Booking_details%20dataset.xlsx
  Dataset containing 100,000+ rows with the following columns:
  Date, Time, Booking_ID, Booking_Status.
  Customer_ID, Vehicle_Type, Pickup_Location, Drop_Location.
  V_TAT, C_TAT, Booking_Value, Payment_Method.
  Ride_Distance, Driver_Ratings, Customer_Ratings.
  Cancellation details and reasons.
  Source for SQL queries and Power BI visualizations.
3. Ola_Data_Analysis.sql
  SQL script with 10 structured queries to derive key insights, including the creation of reusable views:
  Retrieve all successful bookings.
  Calculate the average ride distance for each vehicle type.
  Count the total number of rides canceled by customers.
  Identify the top 5 customers by total bookings.
  Analyze the number of rides canceled by drivers due to personal or car-related issues.
  Find the maximum and minimum driver ratings for Prime Sedan bookings.
  Retrieve all rides where payment was made using UPI.
  Calculate the average customer rating per vehicle type.
  Compute the total booking value of successful rides.
  List all incomplete rides along with their reasons.
4. https://github.com/Poojasri-25/OLA-Data-Analysis-and-Visualization-Project/blob/main/OLA%20analysis.pbix
  Power BI file with interactive dashboards, divided into 5 main sections:
  Overall Trends: Ride volume over time and booking status breakdown.
  Vehicle Insights: Top vehicle types by distance and ratings.
  Revenue Analysis: Payment method breakdown and top spenders.
  Cancellations: Reasons for cancellations by customers and drivers.
  Ratings Analysis: Distribution and comparison of customer vs. driver ratings.
5. Ola-Slides
  Folder containing 5 PNG images used as canvas backgrounds for the Power BI dashboards.
   https://github.com/Poojasri-25/OLA-Data-Analysis-and-Visualization-Project/blob/main/Overview.png
   https://github.com/Poojasri-25/OLA-Data-Analysis-and-Visualization-Project/blob/main/Vehicle.png
   https://github.com/Poojasri-25/OLA-Data-Analysis-and-Visualization-Project/blob/main/Rating.png
   https://github.com/Poojasri-25/OLA-Data-Analysis-and-Visualization-Project/blob/main/Customer.png
7. Portfolio Dashboard
  The complete dashboard is designed for showcasing in your portfolio, emphasizing interactive storytelling and professional design.


## Dashboard Preview

Dashboard screenshots will be added here to provide a quick preview of the Power BI report.

Overview.png

Vehicle.png

Customer.png

Rating.png


## Key Areas of Analysis

### 1. Overall Booking Analysis

- Explore overall ride-booking performance.
- Understand booking trends and key performance indicators.
- Identify patterns that can help evaluate business performance.

### 2. Vehicle Analysis

- Explore vehicle-related performance patterns.
- Compare available vehicle categories.
- Identify areas for further investigation and improvement.

### 3. Customer Analysis

- Examine customer-related booking patterns.
- Explore customer behaviour using the available data.
- Identify trends that may help improve customer experience.

### 4. Rating Analysis

- Analyze rating-related patterns.
- Explore customer and driver experience indicators.
- Identify areas where service quality may require attention.

*Note: Specific numerical findings and business recommendations will be documented after validating the dashboard results.*

---

## How to Use the Repository

1. **Clone or Download**: Download the repository or clone it using Git.
2. **Install Power BI Desktop**: Install Microsoft Power BI Desktop on your computer.
3. **Open the Dashboard**: Open `OLA analysis.pbix` in Power BI Desktop.
4. **Explore the Report**: Navigate through the Overview, Vehicle Analysis, Customer Analysis, and Rating Analysis pages.
5. **Interact with Visuals**: Use available filters and slicers to explore the data from different perspectives.

---

## Tools and Technologies Used

- **Microsoft Power BI**: For data visualization, interactive dashboards, and reporting.
- **Data Analysis**: To explore ride-booking data and identify meaningful patterns.

---

## Future Enhancements

- Include SQL queries for deeper data analysis.
- Add data cleaning and transformation documentation.
- Integrate Python for advanced analysis and predictive modelling.
- Add dashboard screenshots and detailed business insights.
- Enhance the report with additional KPIs, filters, and drill-through functionality where appropriate.

---

## Project Status

**Current Status:** Power BI dashboard created with four report pages.

Additional project documentation, dataset details, screenshots, and analysis scripts can be added as the project develops.

---

## Author

Created as a data analytics portfolio project to demonstrate practical skills in Power BI reporting and data visualization.


