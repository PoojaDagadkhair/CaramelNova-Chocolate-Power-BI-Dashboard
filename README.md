# 🍫 CaramelNova Chocolate Dashboard (Power BI)

## Description
An interactive Power BI dashboard created for the fictional chocolate brand **CaramelNova** to analyze sales, profit, shipments, products, regions, and salesperson performance. This project demonstrates strong skills in data modeling, DAX, and report design.

---

## Dashboard Highlights
- Total Sales, Total Profit, Profit %
- Total Boxes Sold and Shipment Count
- Current Year vs Previous Year comparison
- Shipment distribution analysis
- Top products and top salespersons
- Region-wise sales performance

---

## Tools Used
- Power BI Desktop  
- Power Query  
- DAX  

---

## Data Model
- Star schema design
- Fact table connected to Product, Geography, Salesperson, and Calendar tables

---

## Dataset Columns

### Fact Table
- ShipmentID  
- SPID  
- PID  
- GID  
- Shipdate  
- Amount  
- Boxes  
- Order_Status  
- Cost_per_box  

### Product Table
- PID  
- Product  
- Category  

### Geography Table
- GID  
- Geo  
- Region  

### Salesperson Table
- SPID  
- Sales_person  
- Team  
- Picture  

### Calendar Table
- cal_date  
- month_name  
- month_num  
- year  
- weekday_name  
- weekday_num  

---

## Key Concepts Applied
- Data cleaning and transformation using Power Query
- Star schema data modeling
- Evaluation context in DAX
- Year-on-Year calculations
- KPI creation and condit
