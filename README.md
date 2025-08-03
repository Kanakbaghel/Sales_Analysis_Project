<p align="center">
  <img src="https://img.shields.io/badge/Tool-Power%20BI-yellow?logo=powerbi&logoColor=white" alt="Power BI Badge" />
  <img src="https://img.shields.io/badge/Status-Completed-success" alt="Completed Badge" />
</p>

<h1 align="center">Sales Analysis - Power BI Mini Project</h1>
<p align="center"><em>Graded assignment for the Data Science &amp; Business Analytics Program by IIT Guwahati</em></p>

---

## Objective

Design and develop an interactive dashboard using **Power BI** to analyze customer order data. This includes deriving insights related to:

- ✅ Total order volume  
- ✅ Sales trends by product category  
- ✅ Regional customer segmentation  
- ✅ Monthly growth patterns  
- ✅ Key customer behavior metrics

---

## Learning Outcomes

- Translate complex datasets into **engaging, data-driven stories**
- Build structured, audience-focused narratives to support strategic decisions
- Apply visualization and DAX techniques to highlight business KPIs

---

## 🗂️ Dataset Components

### 🧑 Customers Table  
Captures demographic & regional attributes:
- `CustomerID`, `Name`, `Age`, `Gender`, `Region`, `CustomerSince`, `Email`

### 🛒 Orders Table  
Captures purchase activity:
- `OrderID`, `CustomerID`, `ProductID`, `OrderDate`, `Quantity`, `TotalSales`

### 📦 Products Table  
Provides product and pricing metadata:
- `ProductID`, `ProductName`, `Category`, `UnitPrice`, `Supplier`

---

## Power BI Implementation

### 🔗 Data Modeling  
- Built relationships between **Customers**, **Orders**, and **Products**  
- Created a star schema for efficient filtering and aggregation

### Visualizations Created  
| Metric                    | Chart Type             |
|-----------------------------|---------------------------|
| Total Orders                | Card                      |
| Total Sales                 | Card                      |
| Sales by Product Category   | Donut / Pie Chart         |
| Monthly Sales Trends        | Line Chart                |
| Customer Segmentation       | Stacked Bar by Region     |

### DAX Measures  
- `Average Order Value`  
- `Monthly Sales Growth (%) = (Current - Previous) / Previous`  

---

## Design & Formatting Strategy

- Used theme-consistent **color palettes** and **data labels**  
- Structured layout to support intuitive storytelling  
- Added headers, custom tooltips, and cleaned slicers  
- Saved as: `Sales_Analysis_Dashboard.pbix`

---
<img width="984" height="560" alt="image" src="https://github.com/user-attachments/assets/ac4fb9d7-a4f9-4c2c-8677-cedc5aea3f07" />
<p align="center"><strong>--- Presenting Sales Analysis ---</strong></p>

---
## Skills & Tools Applied

| Tool            | Usage                            |
|-----------------|----------------------------------|
| **Power BI**    | Visualization, Modeling, DAX     |
| **DAX**         | Measure calculation & KPIs       |
| **Data Modeling** | Star schema design             |
| **Storytelling**| Structuring insights by audience |

---

## Reflections

This project deepened my ability to merge **technical BI skills** with **business storytelling**. By transforming raw sales and customer data into visual narratives, I learned how to:

- Identify drivers of revenue by product and region  
- Segment and profile customers by behavior and demographics  
- Present actionable insights to stakeholders in a concise format

---

> _“Data becomes meaningful when it tells a story that leads to better decisions.”_  
<p align="center"><em>Crafted with ♥ by <strong>Kanak Baghel</strong> | <a href="https://www.linkedin.com/in/kanakbaghel">LinkedIn</a></em></p>
