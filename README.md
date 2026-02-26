# 🍽 Zomato Sales & User Performance Dashboard (Power BI)

## 🧠 Project Overview

This project analyzes Zomato’s sales performance, user growth, customer behavior, and city-level business metrics using Power BI.

The objective was to design a multi-page, interactive business intelligence dashboard that provides insights into revenue trends, user acquisition & churn, order performance, and geographic distribution.

The solution leverages data modeling, DAX measures, and dynamic filtering to simulate a real-world food delivery analytics system.

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
- Dynamic Top N city filtering

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

The data model follows a relational structure with multiple interconnected tables:

- **Users Table**
  - Age
  - Gender
  - Marital Status
  - Occupation

- **Orders Table**
  - Order Date
  - City
  - Order Type
  - Value
  - User ID

- **Menu Table**
  - Cuisine
  - Price
  - Restaurant ID

- **Restaurant Table**
  - City
  - Country
  - Cuisine
  - Rating
  - Rating Count

- **Measure Table**
  - DAX measures for KPIs
  - Calculated metrics for dynamic analysis

Relationships were established using primary and foreign keys to enable accurate cross-filtering and aggregation.

---

## 📊 Key KPIs Analyzed

### 🔹 Sales Metrics
- Total Sales: 987M
- Total Orders: 150K
- Total Quantity: 2M
- Sales by Year Trend (2017–2020)

**Insight:** Sales peaked in 2018 before gradually declining, indicating potential market saturation or competition growth.

---

### 🔹 User Metrics
- Total Users: 100K+
- Active Users: 78K
- Gained Users: 12K
- Lost Users: 33K

**Insight:** User churn is significant, suggesting need for retention strategies.

---

### 🔹 Category Performance
- Veg Sales: 122M
- Non-Veg Sales: 106M
- Others: 24M

**Insight:** Vegetarian category slightly outperforms non-veg in revenue contribution.

---

### 🔹 City-Level Performance
- Top Sales City: Tirupati
- Urban vs Rural segmentation
- Rating & Active User comparison by city

**Insight:** Revenue concentration in specific cities highlights geographic dependency.

---

## 🛠 Tools & Technologies Used

- Power BI Desktop
- Data Modeling
- DAX (Calculated Measures)
- Time Intelligence Functions
- KPI Cards
- Drill-down & Top-N Filtering
- Interactive Navigation Buttons
- Multi-page Dashboard Design

---

## 📈 Advanced DAX Concepts Used

- CALCULATE()
- FILTER()
- SUMX()
- DISTINCTCOUNT()
- Time-based aggregation
- Dynamic Top-N ranking
- Gain vs Lost user calculation

---

## 📷 Dashboard Preview

### 🔹 Overview Page
![Overview](overview.png)

### 🔹 User Performance Page
![User Performance](user.png)

### 🔹 City Performance Page
![City Performance](city.png)

---

## 💡 Business Recommendations

- Implement retention campaigns to reduce user churn.
- Focus marketing efforts in high-performing cities.
- Strengthen customer loyalty in cities with high lost users.
- Expand high-performing cuisine segments.
- Monitor year-over-year sales decline for strategic adjustments.

---

## 🎯 Project Outcome

This project demonstrates:

- Strong Power BI dashboard development  
- Data modeling and relational schema design  
- Advanced DAX calculations  
- Multi-page BI reporting  
- Business-focused analytics storytelling  
- KPI-driven performance monitoring  

---

## 🚀 Skills Demonstrated

Power BI | DAX | Data Modeling | Business Intelligence | User Analytics | Sales Analytics | Dashboard Design
