# INT-375-Python-Project-Crime-Mapping
Project Overview
This project performs Exploratory Data Analysis (EDA) on real-world crime data to uncover meaningful insights and patterns. Using Python libraries like Pandas, Matplotlib, Seaborn, and Folium, the project visualizes:

Temporal crime trends

Geographical hotspots

Crime type distributions

Victim demographics

Resolution status of cases

These insights aim to support data-driven decisions for public safety and law enforcement resource planning.

📂 Dataset Information
Name: Crime Data from 2020 to Present

Source: Data.gov

Format: Excel (.xlsx)

Cleaned and preprocessed for better usability

📑 Key Features in Dataset:
DATE OCC, TIME OCC: Time of the incident

AREA NAME, LAT, LON: Location-based data

CRM_CD_DESC: Crime type

VICT AGE, VICT SEX, VICT DESCENT: Victim details

WEAPON DESC: Weapon used (if any)

STATUS DESC: Case resolution status

🧰 Libraries & Tools Used :-
pandas – Data manipulation and analysis

numpy – Numerical operations

matplotlib & seaborn – Visualizations

folium – Interactive geographic maps

plotly – Advanced, interactive charts

📊 Features & Analysis Performed
1️⃣ Crime Distribution and Trends Over Time
Grouped by year, month, and hour

Found peak hours: 6 PM to 12 AM

Higher crime in summer months and weekends

Visualizations: Line plot, histogram, heatmap

2️⃣ Geographic Crime Hotspots
Mapped high-crime areas using Folium HeatMap

Identified districts like 77th Street with higher incidents

Visualizations: Bar chart, interactive map (saved as crime_hotspots_map.html)

3️⃣ Crime Type and Weapon Analysis
Common crimes: Theft, Assault, Burglary

Frequent weapons: Handguns, Knives

Visualizations: Bar plots, pie charts

4️⃣ Victim Demographics
Most victims aged 20–40

Slightly more male victims

Affected ethnicities: Hispanic, Black

Visualizations: Histogram, gender/ethnicity bar plots

5️⃣ Resolution Status
Majority marked as Pending Investigation

Some crimes like Robbery have low clearance

Visualizations: Donut chart, stacked bar chart

📌 Sample Outputs
📈 Temporal Trends

🌍 Heatmaps of Crime Locations

📊 Top Crime Types & Weapons

👤 Demographic Analysis

✅ Solved vs Unsolved Crime Stats
