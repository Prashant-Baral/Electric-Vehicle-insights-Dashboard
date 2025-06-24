# Electric Vehicle Insights Dashboard

Welcome to the **Electric Vehicle Insights Dashboard** project! 🚗⚡  
This project provides an interactive, Excel-based dashboard that analyzes electric vehicle (EV) adoption trends, compliance with clean fuel standards, and market share insights for Washington State, USA.

---

## 📋 Project Overview

Electric vehicles are crucial in the transition towards a greener and more sustainable future. This dashboard uses real-world EV registration data to offer actionable insights into:

- EV adoption trends over time
- Compliance with clean alternative fuel vehicle (CAFV) programs
- Market share distribution by vehicle manufacturer
- Average electric range by make
- Adoption patterns across electric utility providers

The project aims to support policymakers, businesses, and environmental advocates in making informed decisions regarding EV infrastructure and planning.

---

## 📂 Dataset Information

- **Source:** [data.gov - Electric Vehicle Population Data](https://catalog.data.gov/dataset/electric-vehicle-population-data)
- **Fields Used:**
  - Vehicle Identification Number (VIN)
  - Make (Manufacturer)
  - Model Year
  - CAFV Status (Clean Alternative Fuel Vehicle Status)
  - Utility Provider
  - Electric Range (in miles)

- **Initial Records:** ~250,000
- **After Preprocessing:** 39,322 records

---

## ⚙️ Data Preprocessing Steps

- **Data Volume Reduction:** Focused on top 10 vehicle makes and recent 6 model years.
- **Column Cleanup:** Standardized names and removed inconsistencies.
- **Missing Value Handling:**
  - CAFV status missing entries marked as "Eligibility Not Defined".
  - Electric range missing values filled with make-based averages.
- **Data Type Formatting:** Proper typing of columns for seamless dashboard interaction.
- **Sheet Organization:**
  - Raw Data
  - Filtered and Cleaned Data
  - Pivot Tables
  - Average Calculations
  - Final Dashboard
- **Hyperlink Integration:** Quick access to dataset and LinkedIn profile.

---

## 📊 Key Dashboard Insights

| Objective | Key Findings | Visualization |
|:---|:---|:---|
| EV Adoption Trends | Rapid growth after 2013; anomaly in 2025 due to pre-registrations. | Line Chart |
| CAFV Compliance | 31.7% eligible, 56% undefined, 11.7% not eligible. | Pie Chart |
| Market Share by Make | Tesla dominates (~19,309 vehicles), followed by Chevrolet and Nissan. | Tree Map |
| Average Electric Range | Chevrolet leads with 124 miles average range. | Bar Chart |
| Adoption by Utility Provider | Puget Sound Energy serves the majority of EVs. | Bar Chart |

---

## 🎯 Project Conclusion

- **Washington State** is experiencing a steady increase in EV adoption, especially after 2017.
- **Tesla** is the leading EV manufacturer, but other brands like Chevrolet and Nissan also hold significant market shares.
- The majority of EVs are served by **Puget Sound Energy**.
- There is still a large portion of vehicles with **undefined CAFV status**, suggesting opportunities for better data collection.

---

## 🚀 Future Scope

- Expanding analysis to other states for a national perspective.
- Integrating real-time data feeds for dynamic insights.
- Enhancing dashboard interactivity with more filters and slicers.
- Improving CAFV status tracking for more precise compliance analysis.
- Supporting EV infrastructure planning with refined data-driven strategies.

---

## 👨‍💻 About Me

**Prashant Baral**  
B.Tech CSE Student @ Lovely Professional University | Data Science Enthusiast

🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/prashant-baral-286282278/)

---

> *"Driving the future, one electric mile at a time."* 🌱
