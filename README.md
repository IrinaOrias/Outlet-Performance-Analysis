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

### Key Fields in the Dataset:
- `Item_Identifier`: Unique product ID  
- `Item_Type`: Product category (e.g., Snacks, Household, Frozen Foods)  
- `Item_Fat_Content`: Nutritional category (Low Fat, Regular)  
- `Item_Visibility`: Shelf visibility as a percentage  
- `Item_MRP`: Product price  

- `Outlet_Identifier`: Unique outlet ID  
- `Outlet_Establishment_Year`: Year store opened  
- `Outlet_Size`: Store size (Small, Medium, High)  
- `Outlet_Location_Type`: Tier classification (1, 2, or 3)  
- `Outlet_Type`: Store format (e.g., Supermarket Type 1)

- `Item_Outlet_Sales`: Sales amount per item per store  
- `Rating`: Customer satisfaction score (optional)

The data was cleaned in Excel using filters, standardization, and missing value treatment. SQL was then used for all calculations and aggregations.

---

## Key Findings

### 1. Fat Content Preferences
- **Low Fat products** generated significantly more revenue than Regular items  
- Health-conscious purchasing behavior is clearly present

---

### 2. Product Type Performance
- **Top-selling categories**: Fruits and Vegetables, Snack Foods, Household, Frozen Foods  
- **Lowest-performing categories**: Seafood, Hard Drinks, Breakfast Items

---

### 3. Outlet Establishment Year
- Highest total sales came from outlets opened in **1998, 2010, and 2012**  
- **Newer outlets** (post-2015) underperformed in comparison

---

### 4. Outlet Location Performance
- **Tier 3** stores outperformed Tier 1 and Tier 2 stores  
- Indicates high demand and market opportunity in smaller urban zones

---

### 5. Sales by Outlet Size (Proportional Contribution)
- **Medium outlets**: 42% of total sales  
- **Small outlets**: 37%  
- **High outlets**: 21%

---

### 6. Outlet Type + Fat Content
- **Supermarket Type 1** had the highest sales across both Low Fat and Regular items  
- Consistently strong performer, ideal for format expansion

---

## Recommendations and Action Points

### 1. Expand Supermarket Type 1 Format

**Observation:** Supermarket Type 1 consistently leads in sales across all segments  
**Recommendation:** Focus future outlet openings in this format, especially in Tier 3 zones  
**Action:** Use sales forecasting to identify ideal Tier 3 locations for growth

---

### 2. Invest in Medium-Size Outlets

**Observation:** Medium outlets generate the highest share of total revenue  
**Recommendation:** Optimize this format in existing and upcoming locations  
**Action:** Prioritize staffing, inventory, and marketing resources accordingly

---

### 3. Promote High-Demand Product Segments

**Observation:** Low Fat products and essentials like fruits and snacks are bestsellers  
**Recommendation:** Promote these items with special campaigns and bundles  
**Action:** Highlight health-conscious categories and reinforce visibility in-store and online

---

### 4. Reevaluate New and Large Outlets

**Observation:** Newer and larger formats show weaker performance  
**Recommendation:** Audit operations, location selection, and local product fit  
**Action:** Use dashboard filters to monitor underperformers and test targeted improvements

