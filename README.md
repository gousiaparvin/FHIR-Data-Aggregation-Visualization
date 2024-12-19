# FHIR-Data-Aggregation-Visualization

Title: FHIR Data Aggregation & Visualization Dashboard

Overview: This project focuses on creating an interactive and visually appealing dashboard using Google Looker Studio to analyze and visualize healthcare data. The dashboard is designed to provide actionable insights into patient demographics, health conditions, mortality rates, and geographical distributions. It leverages advanced data visualization techniques and interactivity to support decision-making in healthcare management.

Key Features:
Data Integration:
Imported a synthetic dataset of patient records enriched with population data for cities such as Houghton, Marquette, Baraga, and Portage.
Cleaned and prepared the data to ensure compatibility with Looker Studio, including adding calculated fields and hierarchies.

Interactive Visualizations:
Gender and Marital Status Analysis: Pie charts displaying the distribution of gender and marital status among patients.
City-Wise Patient Distribution: A bar chart showing patient counts for each city, enhanced with dynamic filters and calculated fields for percentage distribution.

Mortality Insights:
A scorecard for the Death Toll, with advanced filters to display deceased patients dynamically.
Added calculated fields to track mortality trends efficiently.
Condition Analysis: Bar chart visualizing the prevalence of various health conditions, allowing drill-down by city for deeper insights.
Observation Trends: Line charts to track observations (e.g., glucose levels, blood pressure) over time.
Geo Chart: A map visualizing patient distributions across cities, highlighting the geographical spread and population-adjusted patient density.

Advanced Features Implemented:
Dynamic Filters: Dropdown filters for cities, conditions, and demographics to enable user-driven exploration.

Calculated Fields:
Created fields such as Patients_Per_1000 and Condition_Percentage for advanced metrics.
Used formulas like COUNT_DISTINCT(Patient_ID) and percentage-based calculations to add depth to the analysis.
Drill-Down Simulation: Enabled multi-level data exploration using hierarchical blending and filters.

Usability Enhancements:
Tooltips added to charts for quick reference to additional information.
Clear and descriptive titles for each visualization to improve accessibility.
Cohesive design and layout to ensure a seamless user experience.

Tools and Technologies Used:
Google Looker Studio: For building the interactive dashboard and creating advanced visualizations.
Data Manipulation: Used calculated fields for dynamic metrics and filtering.
CSV Data Processing: Cleaned and prepared the dataset using Excel for Looker compatibility.
Visualization Techniques: Geo Charts, Scorecards, Pie Charts, and Bar Charts.

Learning Outcomes:
Hands-on experience in data visualization and dashboard creation.
Advanced usage of Google Looker Studio features such as calculated fields, dynamic filters, and hierarchical blending.
Understanding of patient demographics, healthcare trends, and geographical health insights.How to View the Dashboard:

Open the https://lookerstudio.google.com/s/n60CyJNXz1E
Explore the filters and charts to interact with the data dynamically.
