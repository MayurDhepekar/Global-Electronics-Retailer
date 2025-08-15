# Global-Electronics-Retailer

# 📊 Retail Pulse – Global Electronics Retailer Dashboard

## 📖 Project Overview
This project simulates the role of a **Data Analyst** for *Maven Electronics*, a global retail company.  
The objective was to transform **raw CSV datasets** into a **clean relational data model** and design an **interactive Excel dashboard** to help leadership track performance, identify trends, and make data-driven decisions.

---

## 🔍 Objectives & Workflow

### 1️⃣ Data Profiling & Preparation
- Connected to raw CSV files: Sales, Products, Customers, Stores, Exchange Rates.
- Performed data cleaning:
  - Removed redundant fields (e.g., Zip Code)
  - Standardized text formats (City names in proper case)
  - Created derived columns (Customer Age, Age Range)
- Built a **custom Calendar table** for day, week, month, quarter, and year-level analysis.

### 2️⃣ Relational Data Model
- Designed a **star schema** with fact and dimension tables.
- Established **1:many relationships** between Sales and Customers, Products, Stores, Calendar.
- Added custom `ExchangeKey` to link Sales with Exchange Rates.
- Normalized Products into Category and Subcategory dimension tables.

### 3️⃣ Data Enrichment & KPI Calculations
- Created a **Measures Table** in Excel for:
  - Total Orders
  - Total Revenue (USD)
  - Average Order Value (AOV)
  - Average Delivery Time (days)
- Performed trend and segment analysis.

### 4️⃣ Interactive Dashboard Design
- Developed the **Retail Pulse** dashboard with:
  - KPI cards
  - Revenue trends by month
  - Revenue by product category
  - Slicers for store and year
- Applied consistent themes, number formatting, and minimal clutter for clarity.

---

## 📊 Key Insights
- 📦 **Total Orders:** 26,326  
- 💰 **Total Revenue:** $55,755,480  
- 💳 **Average Order Value:** $2,117.89  
- ⏱ **Average Delivery Time:** 4.5 days  
- 📈 Seasonal peaks with revenue spikes nearing or exceeding $2.5M  
- 🖥 Top Product Category: Computers  
- 📊 Other strong categories: Home Appliances, Cameras & Camcorders, Cell Phones, TV & Video  
- 🎯 Lower categories: Audio, Music/Movies, Games & Toys  

---

## 💡 Tools & Skills Used
- **Microsoft Excel** – Power Query, Pivot Tables, Charts, Slicers, Data Modeling
- **Data Cleaning & Transformation**
- **Star Schema Modeling**
- **KPI Development & Trend Analysis**
- **Dashboard Design & Visualization**

---

## 📂 Repository Contents
- `Data/` – Raw CSV files (Sales, Products, Customers, Stores, Exchange Rates)
- `Retail_Pulse_Dashboard.xlsx` – Final Excel dashboard
- `README.md` – Project documentation

---

## 🔗 Links
- **Project Link:** https://mavenshowcase.com/project/42478  

---

## 🙏 Acknowledgments
Special thanks to **Maven Analytics** and instructor **Chris Dutton** for providing a practical, hands-on learning experience that mirrors real-world analytics work.

