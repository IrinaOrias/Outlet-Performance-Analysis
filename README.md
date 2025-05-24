# Blinkit Data Exploration – Outlet Performance Analysis

## Executive Summary

This report provides a comprehensive overview of grocery retail outlet performance using transactional sales data. Using SQL and Excel, I explored total sales, outlet characteristics, product demand, and customer preferences.

The analysis revealed:
- Over **$1.2 million** in total sales, with **1,559 unique items** and an **average sale value of $140.99**
- Strong customer preference for **Low Fat** products and essential categories like **Fruits and Vegetables**
- High-performing formats such as **Supermarket Type 1**, and strongest regional performance in **Tier 3 locations**
- Clear patterns in sales by **outlet size and establishment year**
- Key opportunities to optimize outlet strategy, inventory planning, and product promotion

These insights can support strategic decisions across operations, marketing, and expansion planning.

---

## Objective

The objective of this project was to evaluate the sales and operational performance of a grocery retail chain through an in-depth analysis of item- and outlet-level metrics.

I used SQL to calculate KPIs and segment sales data, and Excel to clean the dataset and build visualizations.  
The findings aim to inform decisions around **outlet optimization**, **category management**, and **regional investment**.

---

## Data Overview

The dataset contains over **8,000 transactional records**, representing product sales across different outlet types, sizes, and locations. Each row corresponds to the sale of a product in a specific store, with detailed item and outlet attributes.

[**Download Dataset from Google Drive**](https://drive.usercontent.google.com/download?id=1EdSbZUdL9852dLdq14HgYfToQqymtBl-&export=download)

### Dataset Overview


#### **Product Details**
The dataset captures key product attributes such as:

- **`Item_Identifier`** – a unique product ID  
- **`Item_Type`** – product category (e.g., Snacks, Household)  
- **`Item_Fat_Content`** – nutritional label (Low Fat or Regular)  
- **`Item_Visibility`** – shelf display percentage  
- **`Item_MRP`** – product price  


#### **Store Information**
It also includes store-level information:

- **`Outlet_Identifier`** – unique store ID  
- **`Outlet_Establishment_Year`** – year the store was established  
- **`Outlet_Size`** – size classification (Small, Medium, High)  
- **`Outlet_Location_Type`** – location tier (1, 2, or 3)  
- **`Outlet_Type`** – store format (e.g., Supermarket Type 1)  

#### **Data Preparation**
Data was initially **cleaned in Excel** using filters, standardization, and missing value treatment.  
It was then **analyzed in SQL** for calculations, aggregations, and insights.

---

## Key Findings

### 1. Outlet Type + Fat Content
- **Supermarket Type 1** had the highest sales across both Low Fat and Regular items  
- Consistently strong performer, ideal for format expansion

![Outlet Type and Fat Content](https://github.com/IrinaOrias/Outlet-Performance-Analysis/blob/main/images/Outlet_fat_content.PNG?raw=true)

---

### 2. Product Type Performance
- **Top-selling categories**: Fruits and Vegetables, Snack Foods, Household, Frozen Foods  
- **Lowest-performing categories**: Seafood, Hard Drinks, Breakfast Items

![Product Type Performance](https://github.com/IrinaOrias/Outlet-Performance-Analysis/blob/main/images/product_type.PNG?raw=true)

---

### 3. Outlet Establishment Year
- Highest total sales came from outlets opened in **1998, 2010, and 2012**  
- **Newer outlets** (post-2015) underperformed in comparison

![Outlet Establishment Year](https://github.com/IrinaOrias/Outlet-Performance-Analysis/blob/main/images/establishment_year.PNG?raw=true)

---

### 4. Outlet Location Performance
- **Tier 3** stores outperformed Tier 1 and Tier 2 stores  
- Indicates high demand and market opportunity in smaller urban zones

![Outlet Location Performance](https://github.com/IrinaOrias/Outlet-Performance-Analysis/blob/main/images/Location%20Perfomance.PNG?raw=true)



---

### Recommendations

### 1. **Expand Supermarket Type 1 Format**  
Open at least three new Supermarket Type 1 outlets in regions where sales of both Low Fat and Regular items are consistently strong. Use sales data to guide expansion and aim to complete rollout within 12 months.

### 2. **Boost High-Performing Product Categories**  
Prioritize inventory and promotion for top categories like Fruits & Vegetables, Snack Foods, Household, and Frozen Foods. Set a target to increase their combined sales by 15% over the next two quarters.

### 3. **Support Underperforming New Outlets**  
Conduct an audit of outlets opened after 2015 to identify gaps in product mix or customer reach. Implement targeted changes to improve their sales by 10% within six months.

### 4. **Invest in Tier 3 Locations**  
Tier 3 stores show the highest performance, indicating strong local demand. Focus marketing and possible store openings in these zones, aiming for a 20% increase in sales or two new store launches by year-end.
