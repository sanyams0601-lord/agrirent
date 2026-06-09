# Farm Equipment Rental Analysis Dashboard

## 📌 Overview
This project presents a **data-driven Power BI dashboard** built on the `farm_equipment_rental_dataset.csv`.  
It provides a holistic view of farm equipment rental activity across states, seasons, crops, and equipment types.  
The dashboard is designed to support **decision-making for resource allocation, cost optimization, and demand forecasting** in the agricultural rental ecosystem.

---

## 📊 Dashboard Structure
1. **Executive KPIs**  
   - Total Rentals, Total Supply, Average Rental Cost, Demand–Supply Gap.

2. **Seasonal Demand Trends**  
   - Line chart showing demand fluctuations across Kharif, Rabi, and Summer seasons.

3. **Equipment Utilization & Ranking**  
   - Bar chart ranking equipment by rental counts.  
   - DAX measure: `Equipment Rank`.

4. **Supply Gap Analysis**  
   - State-level bar chart highlighting shortages vs oversupply.  
   - Calculated column: `Gap Per Record`.

5. **Regional Demand Distribution**  
   - Map visualization of rentals and supply across states.

6. **Cost vs Demand Relationship**  
   - Scatter plot comparing rental cost per unit with demand.  
   - DAX measure: `Rental Cost Per Unit`.

7. **Crop Consumption Analysis**  
   - Tree map showing equipment usage by crop type.

---

## Tools & Techniques
- **Power BI Desktop**
- **DAX** for measures and calculated columns
- Dataset: `farm_equipment_rental_dataset.csv`

---

##  Key Insights
- Karnataka shows **equipment shortages**, while other states exhibit **oversupply**.  
- **Kharif season** drives peak demand.  
- **Seed Drill and Sprinkler** dominate equipment rentals.  
- Rental cost per unit does not strictly determine demand — crop type and equipment relevance are stronger drivers.  
- **Sugarcane, Wheat, and Rice** are the most equipment-intensive crops.

