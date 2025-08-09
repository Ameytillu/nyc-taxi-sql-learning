# NYC Taxi SQL Learning & Analysis

This project explores and analyzes the **NYC Taxi Trip dataset** hosted on Google BigQuery using SQL.  
It includes **data exploration queries**, **data cleaning scripts**, and **insights** — all written, tested, and version-controlled with Git.

## 🗂 Dataset
The dataset used is the **NYC Taxi Trips** data available in Google BigQuery’s public datasets.

- **Source:** [`bigquery-public-data.new_york_taxi_trips`](https://console.cloud.google.com/marketplace/details/city-of-new-york/nyc-tlc-trips)
- **Years Analyzed:** 2019 – 2023
- **Taxi Types:** Yellow Taxi

---

## 🛠 Queries Included

### 1. **Exploratory Analysis**
- Count total trips in a given year  
- Calculate average trip distance  
- Find busiest pickup locations  
- Find peak hours of the day  
- Compare weekday vs weekend trips and fares  
- Highest tipping routes  
- Seasonal trends in trip volume  
- Monthly average fare trends  
- Average speed analysis  
- Trip distribution by passenger count

### 2. **Data Cleaning & Quality Checks**
- Remove negative fares and totals  
- Filter date range to plausible trip times  
- Remove trips with impossible distances  
- Drop duplicate rows  
- Ensure valid passenger counts  
- Keep only plausible trips (distance, fare, passenger sanity checks)

---

## 📈 Next Steps

1. Create a **final cleaned dataset view** in BigQuery for easy reuse.
2. Connect to **Tableau** and build a dashboard for:
   - Trip Volume Trends  
   - Pickup/Dropoff Heatmaps  
   - Fare vs Distance Analysis
3. Add SQL scripts for geospatial analysis (borough-to-borough trips).

---
