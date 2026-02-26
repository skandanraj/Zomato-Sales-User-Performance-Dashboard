# 🍽 Zomato Sales & User Performance Dashboard (Power BI)

## 🧠 Project Overview

This project analyzes Zomato’s sales performance, user growth, customer behavior, and city-level business metrics using Power BI.

The objective was to design a multi-page, interactive business intelligence dashboard that provides insights into:

- Revenue trends  
- User acquisition & churn  
- Order performance  
- Geographic sales distribution  

The solution leverages **data modeling, DAX measures, relational schema design, and dynamic filtering** to simulate a real-world food delivery analytics system.

> ⚠️ Note: The dataset used in this project is **synthetic/sample data** created for analytical and portfolio purposes.

---

## 📁 Report Structure

The Power BI report consists of four main pages:

### 1️⃣ Intro Page
- Interactive landing screen  
- Navigation button to dashboard  
- Branding-focused UI design  

### 2️⃣ Overview Page
- Total Sales (Amount)
- Total Orders
- Total Quantity
- Ratings
- Sales by Year Trend
- Top Performing Cities
- Category-level Sales (Veg / Non-Veg / Others)
- Dynamic Top-N city filtering

### 3️⃣ User Performance Page
- Active Users
- Total Users
- Gained Users
- Lost Users
- Gender-based user analysis
- Occupation-wise distribution
- Age-based customer segmentation

### 4️⃣ City Performance Page
- Sales by City
- Order Count by City
- Gain vs Lost Users by City
- Rating Distribution by City
- Active Users by City
- Interactive slicers (City, Name)

---

## 🗂 Data Model

The data model follows a relational schema with multiple interconnected tables:

### 🔹 Users Table
- User ID  
- Age  
- Gender  
- Marital Status  
- Occupation  

### 🔹 Orders Table
- Order Date  
- City  
- Order Type  
- Order Value  
- User ID  

### 🔹 Menu Table
- Cuisine  
- Price  
- Restaurant ID  

### 🔹 Restaurant Table
- City  
- Country  
- Cuisine  
- Rating  
- Rating Count  

### 🔹 Measure Table
- DAX measures for KPIs  
- Calculated metrics for dynamic analysis  

Relationships were established using primary and foreign keys to enable accurate cross-filtering and aggregation.

---

## 📊 Key KPIs Analyzed

### 🔹 Sales Metrics
- **Total Sales:** 987M  
- **Total Orders:** 150K  
- **Total Quantity:** 2M  
- **Sales Trend:** 2017–2020  

**Insight:** Sales peaked in 2018 before gradually declining.

---

### 🔹 User Metrics
- **Total Users:** 100K+  
- **Active Users:** 78K  
- **Gained Users:** 12K  
- **Lost Users:** 33K  

**Insight:** User churn is significant, highlighting retention challenges.

---

### 🔹 Category Performance
- Veg Sales: 122M  
- Non-Veg Sales: 106M  
- Others: 24M  

---

### 🔹 City-Level Performance
- Top Sales City: Tirupati  
- Urban vs Rural segmentation  
- Rating & Active User comparison by city  

---

## 🛠 Tools & Technologies Used

- Power BI Desktop  
- Data Modeling  
- DAX (Calculated Measures)  
- Time Intelligence Functions  
- KPI Cards  
- Drill-down & Top-N Filtering  
- Multi-page Dashboard Design  

---

## 📈 Advanced DAX Concepts Used

- `CALCULATE()`  
- `FILTER()`  
- `SUMX()`  
- `DISTINCTCOUNT()`  
- Time Intelligence  
- Dynamic Top-N Ranking  
- Gain vs Lost User Calculation  

---
## 📷 Dashboard Preview

### 🔹 Intro Page
![Intro](screenshots/Intro.png)

### 🔹 Overview Page
![Overview](screenshots/Overview.png)

### 🔹 User Performance Page
![User Performance](screenshots/User Performance.png)

### 🔹 City Performance Page
![City Performance](screenshots/City Performance.png)

### 🔹 Data Model
![Data Model](screenshots/Data Modelling.png)

---

## 📂 Accessing Raw Data

The raw dataset is embedded inside the `.pbix` file.

To access the data:

1. Download the `.pbix` file from this repository.
2. Open it in **Power BI Desktop**.
3. Go to **Table View**.
4. Select the table you want.
5. Right-click and choose **Copy Table**.
6. Paste into Excel or any data tool.

> The dataset is synthetic/sample data and does not represent real Zomato business data.

---

## 🎯 Project Outcome

This project demonstrates:

- Power BI dashboard development  
- Relational data modeling  
- Advanced DAX calculations  
- Business-focused analytics storytelling  
- KPI-driven performance monitoring  

---

## 🚀 Skills Demonstrated

Power BI | DAX | Data Modeling | Business Intelligence | User Analytics | Sales Analytics | Dashboard Design | Data Storytelling
