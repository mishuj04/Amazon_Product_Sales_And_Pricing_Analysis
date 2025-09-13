# 📊 Amazon Product Sales & Pricing Analysis

This Power BI dashboard provides a comprehensive analysis of **Amazon product purchases, pricing, discounts, and ratings**.  
It helps visualize key metrics, track category-wise performance, and evaluate the impact of promotions (sponsored, coupons, best-seller tags).  

---

## 📂 Dataset Information  

### 🔹 Original Dataset  
- **File:** `amazon_products_sales_data_cleaned.csv`  

### 🔹 Processed Dataset  
- **File:** `New_Data_Amazon.csv`  
- Cleaned & preprocessed using **Python (Pandas)** before loading into Power BI.  

### 🔹 Columns Description  
- **product_title** → Name of the product  
- **product_rating** → Average customer rating (1–5 scale)  
- **total_reviews** → Total number of reviews  
- **purchased_last_month** → Purchases made in the last month  
- **discounted_price** → Current selling price after discount  
- **original_price** → Original listing price  
- **discount_percentage** → Discount % applied on original price  
- **is_best_seller** → Badge type (Amazon’s Choice, Best Seller, Deal, etc.)  
- **is_sponsored** → Whether the product is sponsored or organic  
- **has_coupon** → Availability of coupon discount  
- **buy_box_availability** → Whether product is in Amazon’s Buy Box (0/1)  
- **sustainability_tags** → Labels like “Energy Efficient”, “Made in Italy”, etc.  
- **product_category** → Category of product (Laptops, Phones, Electronics, etc.)  
- **month** → Month of purchase (numeric)  
- **year** → Year of purchase  

---

## 📌 Features  

- **Filters (Left Panel)**  
  - Product Rating (range selector)  
  - Month selector  
  - Sponsorship (Organic vs Sponsored)  
  - Best Seller & Deal Type  

- **Key Metrics (KPIs)**  
  - 🛒 **Total Purchases**  
  - ⭐ **Average Rating**  
  - 💲 **Average Pricing**  

- **Visualizations**  
  - **Purchase Count by Product Category** (Top selling categories)  
  - **Average Pricing by Sustainability Tags**  
  - **Average Discounted Price by Category**  
  - **Avg Pricing vs Avg Discount %** (line + bar comparison)  

---

## 🛠️ Tech Stack  

- **Tool:** Microsoft Power BI  
- **Data Preprocessing:** Python (**Pandas**)  
- **Data Cleaning:** Removed duplicates, handled missing values, converted data types, added calculated columns (Discount Amount, Revenue Estimate, etc.)  
- **Modeling:** DAX measures for KPIs (Avg Pricing, Discount %, Revenue Estimate, etc.)  
- **Theme:** Dark background with Orange highlights (Amazon theme)  

---

## 📈 Insights You Can Derive  

- Which product categories drive the highest purchases  
- Pricing trends and discount strategies across categories  
- Impact of sustainability tags on pricing  
- Effect of promotions (sponsored/coupon/best seller) on sales  
- Relationship between ratings, purchases, and pricing  
