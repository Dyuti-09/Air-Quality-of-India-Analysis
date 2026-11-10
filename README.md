# India Air Quality Data Warehouse 
# Project Overview
This project focuses on designing and developing a SQL Server-based data warehouse to organize and prepare air quality index (AQI) across India for analytical reporting.
The warehouse follows a Madellion Architecture consisting of three layers:
1. Bronze Layer:
   Stores raw air quality datasets at city and station level with daily and hourly records.
2. Silver Layer:
    Performs data cleaning , data standardization, data type conversions, and data quality checks.
3. Gold Layer:
   Organizes transformed datasets into fact and dimension views that can be used to build dashboard and generate business insights.
   
<img width="762" height="452" alt="image" src="https://github.com/user-attachments/assets/4832a496-8dad-4d51-8fc8-f2789d29d5e0" />

# Technology Stack
1. Microsoft SQL Server
2. SQL Server Management Studio (SSMS)
3. SQL
4. Medallion Architecture

# Data Warehouse Structure

The project includes four primary datasets:

Station Hourly Air Quality
Station Daily Air Quality
City Hourly Air Quality
City Daily Air Quality

<img width="892" height="546" alt="ChatGPT Image Nov 10, 2026, 06_16_41 PM" src="https://github.com/user-attachments/assets/41d19cae-d044-460b-8f0d-8476908cea03" />

<img width="1107" height="322" alt="ChatGPT Image Nov 10, 2026, 06_17_38 PM" src="https://github.com/user-attachments/assets/d1f9367a-cca8-4f77-9a1f-5ab5775ed37e" />



<img width="722" height="461" alt="image" src="https://github.com/user-attachments/assets/6f5a14d8-d455-4940-9dff-96cdcdae9b90" />
It also incorporates station and geographical attributes to support location-based analysis.

# Phases of Project :
<img width="687" height="486" alt="image" src="https://github.com/user-attachments/assets/72a81b9b-9159-4c9c-a734-4390b9204de5" />

Detailed Project Documentation in the link below:
https://app.notion.com/p/Air-Quality-of-India-Analysis-403e744e57ea8060b565f10221643c30



# Project Status:

Current stage: Gold Layer development completed; preparing for analytical exploration and visualisation.


