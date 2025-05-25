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

### 1. A Few Product Categories Drive Most of the Sales

Fruits & Vegetables, Snack Foods, Household, and Frozen Foods contribute over 60% of total revenue. In contrast, Seafood, Hard Drinks, and Breakfast Items generate less than 5% combined.


### 2. Supermarket Type 1 Dominates in Sales Performance

Supermarket Type 1 leads all other formats in total sales, indicating a successful combination of store layout, product variety, and customer engagement.


### 3. Older Outlets Perform Better Than Newer Ones

Outlets established before 2015 (notably 1998, 2010, and 2012) show significantly stronger sales than newer outlets, which have yet to catch up in performance.


### 4. Tier 3 Locations Offer the Greatest Revenue Potential

Tier 3 outlets outperform Tier 1 and 2 in both total and average sales, revealing high demand in smaller urban or semi-urban markets.


---

## Recommendations

1. Expand Supermarket Type 1 by opening at least three new outlets in high-performing regions, using sales data to guide location choice and completing the rollout within 12 months.

2. Increase sales of top categories (Fruits & Vegetables, Snack Foods, Household, Frozen Foods) by 15% over the next two quarters through focused inventory allocation and promotional efforts.

3. Audit outlets opened after 2015 to identify performance gaps, and implement targeted improvements to increase their sales by at least 10% within six months.

4. Prioritize Tier 3 areas for expansion and localized marketing, aiming for a 20% sales boost or at least two new store openings in these high-demand zones by year-end.

---

---

## Conclusion

This analysis transformed a complex dataset into actionable insights that support smarter retail decisions. By identifying high-performing outlet types, customer preferences, and hidden market opportunities, the project offers a strategic foundation for improving efficiency, aligning with consumer demand, and guiding future investments. The findings highlight the value of understanding business performance through structured exploration and thoughtful segmentation.
