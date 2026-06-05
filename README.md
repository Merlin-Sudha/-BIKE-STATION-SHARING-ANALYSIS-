# 🚲 Bike Station Sharing Analysis Dashboard

## 📌 Project Overview
The **Bike Station Sharing Analysis Dashboard** provides a comprehensive view of bike-sharing operations across multiple European cities and contractors. It consolidates key performance indicators (KPIs) such as station availability, bike distribution, and contractor contributions into a single interactive platform.

---

## 🎯 Objectives
- Identify the busiest bike-sharing stations across Europe to optimize resource allocation and maintenance schedules.
- Monitor operational health by tracking open vs. closed stations.
- Compare bike distribution across contractors and cities to evaluate regional performance.
- Analyse growth trends in bike-sharing infrastructure (2022–2025) to forecast expansion needs.
- Visualize geographic spread of bike stations to identify coverage gaps.

---

## 📂 Data Sources
- **Timeline:** 2022–2024  
- **Domain:** Europe bike station sharing  

---

## 🛠️ Tools & Technologies
- **Excel** – Data preprocessing  
- **Power BI** – Data transformation, modelling, and visualization  

---

## 🔧 Data Preprocessing
- Handled missing values  
- Removed duplicates  
- Corrected data types  
- Renamed columns for readability  
- Ensured uniqueness across key identifiers  

---

## 🔄 Data Transformation
- Created a **Calendar Table** for time-based analysis  
- Developed custom columns for reporting accuracy  
- Derived KPIs (e.g., available bikes, closed stations)  
- Extracted latitude & longitude from position data  

---

## 📊 Data Modelling & DAX
- Established relationships between tables  
- Defined cardinality and lookup tables  
- Key DAX Measures:
  - **Total Stations:** 2.856K  
  - **Closed Stations:** 206  
  - **Open Stations:** 2.65K  
  - **Available Stands:** 32K  
  - **Total Bikes:** 57K  
  - **Available Bikes:** 20K  

---

## 📈 Exploratory Data Analysis (EDA)
Interactive dashboards include:
- **Bar Chart:** Top 5 stations by bike count  
- **Pie Chart:** Station status (open vs. closed)  
- **Tree Map:** Contractor name vs. bike count  
- **Line Chart:** Yearly updates (2022–2025)  
- **Map Chart:** Geographic distribution of stations  
<img width="1377" height="797" alt="Screenshot 2026-06-05 115117 (1)" src="https://github.com/user-attachments/assets/84849cc3-0b04-4df6-8f25-38385d405563" />

---

## 🔍 Key Insights
### Descriptive Analytics
- Busiest hubs: **INSA** and **Hanover Quay East**  
- Majority of stations are open → strong operational reliability  
- Contractors like **Bruxelles-Capitale, Lyon, Dublin** dominate bike counts  
- Steady growth from 2022–2025, sharp rise in 2025  

### Diagnostic Analytics
- Demand concentrated in specific hubs → uneven distribution  
- 206 closed stations linked to contractor inefficiencies or low demand  
- Smaller contractors struggle with infrastructure  

### Predictive Analytics
- Stations projected to surpass **3K+ by 2026**  
- Demand requires **25K–30K available bikes** in next 2 years  
- Growth opportunities in **Eastern Europe & Southern Italy**  

### Prescriptive Analytics
- Increase available bikes in high-demand hubs  
- Investigate closed stations to reduce closures below 10%  
- Support smaller contractors with infrastructure investment  
- Expand into underrepresented regions  

---

## ✅ Conclusion
The dashboard confirms strong growth in bike-sharing across Europe, with reliable operations and over **2.8K stations**. High-demand hubs highlight the need for increased bike availability, while contractor disparities and closed stations require targeted action. Expansion into **Eastern Europe and Southern Italy** will ensure balanced coverage and sustainable urban mobility.

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bike-station-dashboard.git

