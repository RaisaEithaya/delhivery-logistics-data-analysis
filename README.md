# Logistics Delivery Data Analysis Dashboard (Power BI)

## Project Overview
This project presents a comprehensive logistics delivery analysis dashboard built using Power BI.  
It focuses on evaluating delivery performance, delays, and route efficiency by comparing actual delivery data with optimized route estimates.

---

## Objectives
- Analyze delivery timelines and performance trends  
- Measure on-time vs delayed shipments  
- Compare actual vs expected (OSRM) delivery time  
- Identify inefficiencies in logistics operations  
- Provide actionable insights to improve delivery performance  

---

## Key Metrics
- Total Shipments: 14,817  
- Total Distance Covered: 33.91M  
- Average Delivery Time: 416.93 mins  
- On-Time Delivery Rate: 81.97%  
- Delayed Shipments: 18.03%  

---

## Dataset Overview

### Trip Details
- `trip_uuid` – Unique trip ID  
- `route_type` – FTL (Full Truck Load) / Carting (Local delivery)  
- `source_name` / `destination_name` – Origin & destination hubs  

### Time Metrics
- `actual_time` – Actual delivery time  
- `osrm_time` – Expected time based on optimized routing  
- `start_scan_to_end_scan` – Total trip duration  

### Distance Metrics
- `actual_distance_to_destination` – Actual distance traveled  
- `osrm_distance` – Expected distance  

### Performance Indicators
- `is_cutoff`  
  - 1 = On-time delivery  
  - 0 = Delayed delivery  
- `factor` – Efficiency indicator comparing actual vs expected performance  

### Segment-Level Analysis
- `segment_actual_time` – Actual time for each trip segment  
- `segment_osrm_time` – Expected time for segment  
- `segment_factor` – Segment efficiency metric  

---

## Dashboard Features
- KPI Cards (Total shipments, delivery time, on-time %)  
- Actual vs Expected (OSRM) analysis  
- Delivery time distribution (Histogram)  
- On-time vs delayed shipment analysis  
- Route type comparison (FTL vs Carting)  
- Operational performance insights  

---

## Key Insights
- Majority of deliveries are completed within expected time ranges  
- Around 18% of shipments experience delays  
- Gap observed between actual and expected delivery times  
- Small number of trips contribute to major delays (outliers)  
- Route type impacts delivery efficiency  

---

## Tools Used
- Power BI  

---

## Business Impact
This dashboard helps in:
- Monitoring delivery performance KPIs  
- Identifying delays and inefficiencies  
- Improving route planning and operations  
- Enhancing customer satisfaction through timely deliveries  


---

## Files Included
- Power BI Dashboard (.pbix)  
- Dataset (CSV/Excel)
- Key columns.doc

---



## Support
If you found this project useful, please consider giving it a star
