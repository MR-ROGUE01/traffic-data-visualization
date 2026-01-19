# Traffic Data Visualization

## Overview
This project analyzes and visualizes urban traffic data to identify congestion patterns, peak traffic hours, and energy usage trends. The goal is to convert raw traffic data into meaningful insights that can support data-driven urban planning decisions.

---

## Dataset
The dataset (`dt.csv`) includes traffic-related information such as:
- City
- Vehicle Type
- Day Of Week and Hour Of Day
- Speed and Traffic Density (Low, Medium, High)
- Energy Consumption (used as a pollution proxy)

---

## Objectives
- Identify peak traffic hours  
- Analyze congestion across vehicle types  
- Detect potential pollution hotspots  
- Compare weekday and weekend travel patterns  

---

## Methodology
- Data preprocessing using **Pandas**
- Categorical traffic density encoded as:
  - Low → 1, Medium → 2, High → 3
- Grouping and aggregation using `groupby` and `mean`
- Visualization using **Matplotlib**

---

## Visualizations
- Peak traffic hour analysis
- Vehicle type vs congestion comparison
- City-wise energy consumption
- Weekday vs weekend speed comparison

---

## Technologies Used
Python, Pandas, Matplotlib, Git, GitHub

---

## Conclusion
This project demonstrates how effective data visualization and aggregation techniques can reveal valuable insights from traffic data and support informed decision-making.

---

