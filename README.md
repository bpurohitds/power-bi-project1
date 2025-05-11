# power-bi-project1
🎓 Student Purchase Behavior Analysis | Power BI Project
Analyzed U.S. student spending across store types and locations using a survey dataset. Built an interactive Power BI report with advanced visuals and data governance features.

# 🎓 Student Purchase Behavior Analysis | Power BI Project

**Course:** Microsoft Power BI - IntelliPaat  
**Domain:** Retail Analytics  
**Tools & Tech:** Power BI Desktop, Power BI Service, DAX, Data Modeling, Row-Level Security  

---

## 📘 Project Description

This project focuses on analyzing student spending habits in various U.S. retail stores based on a survey dataset. The goal was to build a comprehensive Power BI dashboard to generate actionable insights into purchase behavior segmented by store location, store setting, age group, and product categories (e.g., video games, books, gadgets, toys, sports).

---

## 🔑 Key Objectives

- Build dynamic and interactive dashboards using Power BI
- Derive business insights through visualizations
- Implement role-based access control (RLS)
- Deploy and schedule refreshes in Power BI Service
- Leverage natural language Q&A features for quick data discovery

---

## 📊 Features & Visualizations

### 1. **Tabular Visualization**
- Conditional formatting based on Total Amount of Purchase (TAP):
  - **Red**: TAP < 35,000  
  - **Yellow**: 35,000 ≤ TAP < 60,000  
  - **Blue**: TAP ≥ 60,000  

### 2. **Matrix Visualization**
- Shows Outdoor Sports spending across age groups and store settings  
- Includes color formatting for comparative analysis

### 3. **Funnel Chart**
- Visualizes TAP by store setting  
- Displays values as **% of first stage** for drop-off insight

### 4. **Pie Chart**
- Represents TAP by different store locations  
- Filtered to **Suburban** store setting using filter context

### 5. **Scatter & Sand Dance Plots**
- **Scatter Plot:** Compares Video Games vs Outdoor Sports by age  
- **Sand Dance Plot:** Shows Indoor Sports vs Video Games across age groups

### 6. **Row-Level Security (RLS)**
- User-based data restriction using a user mapping table  
- Example: User "Mani" sees only Rural data

### 7. **Power BI Service Integration**
- Dashboard published on Power BI Cloud  
- **Master Dashboard** includes Funnel and Scatter plots  
- Data refresh scheduled **every 4 hours (6x/day)**

### 8. **Q&A Feature**
- Natural language insights via:
  - Average student age
  - Donut chart: TAP by store location

---

## 🗂️ Dataset

- **Name:** Student Survey  
- **Type:** Structured tabular data  
- **Fields:** Age, Store Location, Store Setting, Product Categories, Purchase Amounts

---

## 🚀 Outcome

- Built a fully interactive, color-coded, and role-secure dashboard  
- Enabled automated, cloud-based reporting with minimal manual intervention  
- Empowered users to explore insights via Q&A and visual drill-downs  

---

## 📷 Screenshots (Optional)

![image](https://github.com/user-attachments/assets/7a9ed541-158b-4cd7-9ded-31d6f02d3f26)

![image](https://github.com/user-attachments/assets/207e27d0-8283-4407-904c-b074397de97d)


---

## ✅ Status

✔️ Completed  
🔄 Cloud-synced with scheduled refresh  
🔐 Role-based access implemented

---
