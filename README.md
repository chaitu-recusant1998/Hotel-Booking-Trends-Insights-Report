# 🏨 Hospitality Analytics Dashboard: Hotel Booking Trends & Insights

## 📌 Overview
This project presents an end-to-end data analysis solution for the hospitality industry using **Power BI**. The dashboard provides actionable insights into hotel booking trends, revenue performance, and customer behavior.

In a highly competitive hospitality market, data-driven decisions are essential. This analysis helps hotel management understand performance gaps, optimize pricing strategies, and improve occupancy and revenue.

---

## ❓ Problem Statement
Hotels often struggle to answer critical business questions such as:
- Are pricing strategies optimized for maximum revenue?
- How does occupancy impact overall performance?
- Which channels or time periods drive the most revenue?

This project aims to analyze hotel booking data and uncover insights that support better decision-making in pricing, operations, and customer experience.

---

## 📊 Dataset Information
- **Source:** Excel files  
- **Data Includes:**
  - Booking details (dates, channels, room types)
  - Revenue and pricing data
  - Customer ratings
  - Occupancy and cancellation data  
- **Volume:** ~130,000+ records in the fact table with multiple dimension tables

---

## 📈 KPIs Explained
- **Revenue:** Total income generated from bookings  
- **RevPAR (Revenue per Available Room):** Revenue earned per available room  
- **DSRN (Daily Sellable Room Nights):** Total rooms available for sale per day  
- **Occupancy %:** Percentage of rooms occupied  
- **ADR (Average Daily Rate):** Average revenue earned per booked room  
- **Realisation %:** Percentage of successful check-ins vs bookings made  

---

## 🧹 Data Cleaning & Transformation
Data preparation was performed using **Power Query**:
- Removed duplicates and handled missing values  
- Standardized date formats and categorical fields  
- Created derived columns (e.g., weekday/weekend classification)  
- Ensured data consistency across tables  

---

## 🧩 Data Modeling
A **Star Schema** was implemented for efficient data modeling:
- **Fact Table:** Booking transactions (~130K records)  
- **Dimension Tables:** Date, Hotel, Room Type, Booking Channel, etc.  
- Established relationships using primary and foreign keys  

This structure improves performance and simplifies DAX calculations.

---

## 🧮 DAX & Calculations
Key measures and columns were created using **DAX**:
- Revenue calculations  
- RevPAR, ADR, Occupancy % measures  
- Week-over-Week (WoW %) change metrics  
- Calculated columns for weekday/weekend segmentation  

---

## 📊 Dashboard Features

### 🔹 Interactivity
- Slicers for filtering by date, hotel, and booking channel  
- Drill-down capabilities for detailed analysis  
- Tooltip charts showing weekly KPI trends  

### 🔹 Visualizations Used
- KPI cards for quick performance tracking  
- Line charts for trend analysis  
- Bar charts for comparison  
- Table visuals for weekday vs weekend insights  

---

## 🔍 Key Insights
1. **Flat Pricing Strategy Identified**  
   ADR remains consistent week-over-week, indicating a lack of dynamic pricing.  
   ➤ Opportunity: Implement dynamic and weekend pricing to increase revenue.

2. **Strong Correlation Between Occupancy & Ratings**  
   Higher occupancy aligns with better customer ratings.  
   ➤ Suggests service quality impacts booking demand.

3. **High Cancellation Rates Impact Performance**  
   Hotels with lower occupancy show higher cancellation percentages.  
   ➤ Indicates operational or customer experience issues.

4. **Underperforming Online Direct Channel**  
   Direct offline ADR is highest, while online direct ADR is lowest.  
   ➤ Opportunity: Improve pricing and promotional strategies for online channels.

5. **Weekday vs Weekend Trends Matter**  
   Clear differences in booking patterns highlight the importance of segmentation.

6. **Advanced Dashboard Capabilities**  
   WoW% tracking and tooltip trend charts enhance analytical depth and usability.

---

## 🛠️ Tools & Technologies
- Power BI  
- Excel  
- DAX  
- Power Query  
- Power BI Service  

---

## 📸 Screenshots
👉 Insert dashboard screenshots here

---

## 🎯 Learnings
- Built a complete BI solution using real-world hospitality data  
- Gained hands-on experience with data modeling (Star Schema)  
- Developed strong skills in DAX calculations and KPI design  
- Created interactive and user-friendly dashboards  
- Learned how to translate data into business insights  

---

## 🚀 Future Improvements
- Implement forecasting models for demand prediction  
- Add customer segmentation analysis  
- Integrate real-time data sources  
- Enhance UI/UX with better visual storytelling  

---

## ✅ Conclusion
This project demonstrates how data analytics can drive meaningful insights in the hospitality industry. By leveraging Power BI, the dashboard highlights key opportunities in pricing strategy, customer experience, and revenue optimization—making it a valuable tool for decision-makers.

---

💬 Feedback and suggestions are always welcome. Constructive criticism is highly appreciated!
