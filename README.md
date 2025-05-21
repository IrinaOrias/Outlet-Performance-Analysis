# Blinkit Data Exploration – Outlet Performance Analysis

---

## Executive Summary

This report provides a comprehensive overview of retail outlet performance using transactional sales data.  
Using SQL and Excel, I explored total revenue, product performance, outlet characteristics, and customer behavior.

**The analysis revealed:**
- Over **1.2 million** in total sales, with **1,559 unique items** sold and an **average transaction value of $140.99**
- Strong customer preference for **Low Fat** products
- High-performing outlet types like **Supermarket Type 1**, and strong engagement in **Tier 3** locations
- Clear trends in outlet performance by **size** and **establishment year**
- Opportunities to optimize **product offerings**, **regional strategies**, and **outlet formats**

These insights can guide operational improvements, marketing campaigns, and outlet development strategies.

---

## Objective

The objective of this project was to evaluate the performance of various retail outlets based on business dimensions such as item type, outlet size, location, year of establishment, and customer preferences.

The analysis was conducted using SQL for data aggregation and Excel for data cleaning and visualization.  
The findings support data-driven decisions in outlet expansion, product planning, and targeted marketing.

---

## Data Overview

The analysis is based on a transactional dataset simulating grocery retail activity across multiple store formats.  
Each row represents the sale of a product at a specific outlet, along with related attributes describing the item, the store, and the sales result.

**Source Dataset:**  
[Download from Google Drive](https://drive.usercontent.google.com/download?id=1EdSbZUdL9852dLdq14HgYfToQqymtBl-&export=download)

### Key Features of the Dataset:

#### Product-Level Fields:
- `Item_Identifier`: Unique code for each product  
- `Item_Weight`: Weight in kilograms  
- `Item_Fat_Content`: Nutritional classification (e.g., Low Fat, Regular)  
- `Item_Visibility`: Percentage visibility in the store (shelf exposure)  
- `Item_Type`: Product category (e.g., Dairy, Fruits and Vegetables, Snacks)  
- `Item_MRP`: Maximum retail price

#### Outlet-Level Fields:
- `Outlet_Identifier`: Unique store ID  
- `Outlet_Establishment_Year`: Year the store began operations  
- `Outlet_Size`: Store size category (Small, Medium, High)  
- `Outlet_Location_Type`: Geographic classification (Tier 1, Tier 2, Tier 3)  
- `Outlet_Type`: Format of store (e.g., Supermarket Type 1, Grocery Store)

#### Sales & Rating:
- `Item_Outlet_Sales`: Total sales of each item at that outlet  
- `Rating`: Customer rating (where available)

### Data Preparation Process:
- Standardized inconsistent entries in `Item_Fat_Content` (e.g., "low fat" vs "Low Fat")
- Handled missing values in `Item_Weight` and `Outlet_Size`
- Created new groupings for analysis: fat content segments, outlet size %, location tiers
- Removed outliers in visibility and formatted values for readability
- Prepared clean pivot tables and visualizations in Excel

---

## Key Performance Indicators (KPIs)

1. **Total Sales**: Cumulative item revenue  
2. **Average Sales**: Mean sales per transaction or product  
3. **Number of Items**: Count of unique product identifiers  
4. **Average Rating**: Overall customer satisfaction

---

## Granular Metrics

1. **Total Sales by Fat Content**  
2. **Total Sales by Item Type**  
3. **Fat Content by Outlet Location for Total Sales**  
4. **Total Sales by Outlet Establishment Year**  
5. **Percentage of Sales by Outlet Size**  
6. **Sales by Outlet Location**  
7. **All Metrics by Outlet Type**

---

## Key Findings

### 1. Fat Content Preferences
- Low Fat products significantly outperformed Regular ones  
- Consumers favor healthier choices

### 2. Product Type Performance
- Top-selling: Fruits and Vegetables, Snack Foods, Household, Frozen Foods  
- Underperformers: Seafood, Hard Drinks, Breakfast Items

### 3. Outlet Establishment Year
- Outlets from 1998, 2010, and 2012 generated the most revenue  
- Newer outlets showed weaker performance

### 4. Outlet Location Performance
- Tier 3 locations outperformed Tier 2 and Tier 1  
- Strong demand observed in non-urban areas

### 5. Outlet Size Efficiency
- Medium outlets = 42% of total sales  
- Large outlets = only 21%, underperforming by size

### 6. Outlet Type and Fat Content
- Supermarket Type 1 dominates across both Low Fat and Regular products  
- Strong candidate for expansion

---

## Recommendations and Action Points

### 1. Expand Supermarket Type 1  
- Focus on Tier 3 and high-growth locations  
- Proven sales leader across product categories

### 2. Strengthen Medium Outlet Strategy  
- Highest efficiency in revenue contribution  
- Optimize and replicate this format

### 3. Leverage Product Demand  
- Promote Low Fat and essential categories  
- Align inventory and marketing accordingly

### 4. Address Underperformance in New/Large Outlets  
- Evaluate planning, staff readiness, and product mix  
- Adjust strategies based on local demand


