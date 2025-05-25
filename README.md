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
- **`Item_Identifier`** – a unique product ID  
- **`Item_Type`** – product category (e.g., Snacks, Household)  
- **`Item_Fat_Content`** – nutritional label (Low Fat or Regular)  
- **`Item_Visibility`** – shelf display percentage  
- **`Item_MRP`** – product price  


#### **Store Information**
- **`Outlet_Identifier`** – unique store ID  
- **`Outlet_Establishment_Year`** – year the store was established  
- **`Outlet_Size`** – size classification (Small, Medium, High)  
- **`Outlet_Location_Type`** – location tier (1, 2, or 3)  
- **`Outlet_Type`** – store format (e.g., Supermarket Type 1)  

#### **Data Preparation**
Data was initially **cleaned in Excel** using filters, standardization, and missing value treatment.  
It was then **analyzed in SQL** for calculations, aggregations, and insights.

---

##  Key Insights

- **Top Product Categories**:  
  *Fruits and Vegetables*, *Snack Foods*, and *Household* products lead in sales, reflecting strong customer preferences.

- **Best Performing Outlet Type**:  
  *Supermarket Type 1* shows outstanding sales performance compared to all other outlet types, indicating a highly effective store format.

- **Sales by Establishment Year**:  
  Outlets opened in **1998** are top performers, but recent years (2020–2022) also show consistent contribution, suggesting that newer outlets are viable.

- **Location Type Trends**:  
  **Tier 3 locations** account for the largest portion of sales (39%), outperforming Tier 2 (33%) and Tier 1 (28%).

---

##  Recommendations

1. **Expand Supermarket Type 1 in High-Performing Tiers**  
   Launch **3 new Supermarket Type 1 outlets** in **Tier 3** zones within **12 months** to capture high demand. Use top-selling categories as anchor products.

2. **Boost Sales of High-Demand Categories**  
   Increase inventory and promotional investment for *Fruits & Vegetables*, *Snack Foods*, and *Household* by **20%** to raise combined sales by **15%** over the next **2 quarters**.

3. **Review and Optimize Underperforming Formats**  
   Evaluate the performance of *Supermarket Type 2 and 3* formats within **2 months** and implement improvements in layout or product mix at low-performing sites to increase sales by **10%** in **6 months**.

4. **Capitalize on Tier 3 Potential with Loyalty Programs**  
   Roll out a loyalty or discount program in **Tier 3** regions by **Q3**, targeting a **25% increase in customer retention** by year-end.

5. **Audit Recently Opened Stores for Optimization**  
   Conduct a review of stores launched from **2020 to 2022**. Select **5 outlets** for layout reconfiguration and refine product assortments with the goal of lifting sales by **8–10%** within **3 months**.



---

## Conclusion

This analysis transformed a complex dataset into actionable insights that support smarter retail decisions. By identifying high-performing outlet types, customer preferences, and hidden market opportunities, the project offers a strategic foundation for improving efficiency, aligning with consumer demand, and guiding future investments. The findings highlight the value of understanding business performance through structured exploration and thoughtful segmentation.
