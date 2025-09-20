# Realestate-Sales-Analysis

# 🏡 Real Estate Luxury Housing Analytics (Bangalore)

This project analyzes **Luxury Housing Market Trends in Bangalore** using a dataset of real estate transactions.  
It combines **Python, MySQL, and Power BI** to build a complete data pipeline — from data cleaning → database storage → SQL analysis → interactive dashboards.

---

## 📌 Project Workflow

1. **Data Collection**  
   - Input dataset: `Luxury_Housing_Bangalore.csv`

2. **Data Cleaning & Transformation (Python)**  
   - Removed special characters from prices (`₹`, `Cr`)  
   - Handled missing values (unit size, amenity score)  
   - Standardized text fields (builder names, configurations, micro-markets)  
   - Derived new fields:  
     - `Price_per_Sqft`  
     - `NRI_Flag`  
     - `Booking_Status`  

3. **Database (MySQL with SQLAlchemy)**  
   - Created schema `realestate`  
   - Loaded cleaned dataset into `housing` table  

4. **SQL Analytics**  
   Example queries implemented:
   - Market trends by **quarter & micro-market**  
   - Builder performance (total & avg ticket size)  
   - Amenity score impact on booking success  
   - Booking conversion by micro-market  
   - Demand for housing configurations (3BHK, 4BHK, etc.)  
   - Sales channel efficiency  
   - Builder contribution each quarter  
   - Possession status vs buyer type  
   - Geographical concentration of projects  
   - Top 5 builders by revenue  

5. **Visualization (Power BI)**  
   - Built interactive dashboards answering key business questions.  
   - Visuals include: Line chart, Bar/Column charts, Scatter plots, Pie/Donut charts, Matrix tables, Maps, and KPI cards.

---

## 🛠️ Tech Stack

- **Language:** Python (Pandas, SQLAlchemy, PyMySQL)  
- **Database:** MySQL  
- **Visualization:** Power BI  
- **Version Control:** Git & GitHub  

---

## 📂 Repository Structure
Realestate-Sales-Analysis/
│
├── data/ # Raw & processed datasets
│ ├── Luxury_Housing_Bangalore.zip # Original dataset
│ ├── housing_cleaned.zip # Cleaned dataset
│
├── notebooks/ # Jupyter notebooks
│ └── codes.ipynb # Data cleaning, SQL load & analysis
│
├── reports/ # Analysis & reports
│ ├── Luxury_house_sales_analysis.zip # Project analysis files
│
├── README.md # Project documentation


