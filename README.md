# Quantium-Retail-Strategy-and-Analytics

## Introduction

This project is part of a **job simulation hosted by Quantium** on **Forage**, designed to give participants real-world experience in retail data analytics. Quantium is a data science and AI company that partners with leading organizations to help them make data-driven decisions.

In this simulation, I stepped into the role of a **Retail Data Analyst**, working on a request from the **Category Manager for Chips**, who needed insights into customer purchasing behavior across the chip category. The aim is to uncover trends in chip purchases, understand customer segments, and provide actionable recommendations to support the **supermarket's chip strategy for the next six months**.

The simulation consists of three parts. This repository focuses on **Part 1: Data Preparation and Customer Analytics**, which covers cleaning the data, exploring customer behavior, and identifying meaningful customer segments.

---

## Project Objectives

This phase of the project focuses on preparing the data for analysis and extracting key insights on chip buying behavior. The main objectives are:

**1. Data Cleaning & Preparation**

  * Inspect transaction and customer datasets for nulls, inconsistencies, and outliers.
  * Ensure category filtering is correctly applied to isolate chip products only.
  * Clean and standardize relevant numeric and categorical fields.
  * Merge customer and transaction data into a usable analysis dataset.

**2. Exploratory Data Analysis**

  * Analyze total chip sales, purchasing trends, and key drivers of sales.
  * Identify high-performing customer segments and regional behavior.
  * Visualize insights using charts and graphs.

**3. Customer Segmentation**

  * Group customers based on purchasing behavior and demographic features.
  * Investigate relationships between segment behavior and packet size preference.
  * Prepare actionable insights and strategic recommendations for targeting.

### Tools Used

* **Python**

  * Used as the primary language for data analysis.

* **Python Libraries:**

  * `pandas` – for data cleaning, merging, and manipulation.
  * `numpy` – for numerical operations.
  * `matplotlib` & `seaborn` – for data visualization and trend analysis.

* **Jupyter Notebook**

  * Used for interactive development, exploration, and presentation of code and insights.

---

## 📓Full Project Notebook

You can explore the complete analysis process—including data cleaning, exploration, customer segmentation, and insights generation—in the Jupyter Notebook provided below:

[Click here to view the full project notebook](Quantium_task1.ipynb)

---

## Conclusion

This comprehensive exploratory data analysis has illuminated key aspects of customer behavior and product performance within the chips category. We found that sales are primarily driven by specific customer segments, notably **Budget - Older Families**, **Mainstream - Young Singles/Couples**, and **Mainstream - Retirees**, each contributing through distinct purchasing patterns – either by sheer customer volume or by higher units purchased per transaction. Product preferences show a lean towards larger pack sizes, with specific brands like Twisties holding unique positions. Furthermore, the analysis confirmed a strong seasonal sales surge around December. These insights, derived from a clean and validated dataset, provide a robust foundation for developing targeted retail strategies aimed at optimizing sales, enhancing customer engagement, and driving sustained growth.

---

## Recommendations

Based on these findings, we propose the following strategic recommendations:

1.  **Tailored Marketing & Promotions:**
    * **Fortify Engagement with Top Segments:** Develop targeted marketing campaigns and loyalty programs specifically for **Budget - Older Families**, **Mainstream - Young Singles/Couples**, and **Mainstream - Retirees**. Promotions for Older Families could focus on multi-pack offers, while Mainstream segments might respond well to value-added bundles or new flavor introductions.
    * **Re-evaluate Strategy for New Families:** Investigate the specific needs and purchasing habits of **New Families** to understand their low engagement. This could involve product innovation, targeted promotions, or alternative communication channels.

2.  **Optimized Product Assortment and Placement:**
    * **Prioritize Top-Performing Products & Pack Sizes:** Ensure consistent availability and prominent shelf placement for top sellers like **Dorito Corn Chp Supreme 380g** and **Smiths 330g/380g varieties**.
    * **Leverage Twisties Brand Power:** Given the strong affinity of Mainstream Young Singles/Couples for 270g packs exclusively from Twisties, consider co-promotions with Twisties, or explore similar pack sizes for other popular brands if market demand warrants.

3.  **Dynamic Pricing & Value Proposition:**
    * **Premium Opportunities for Mainstream Singles/Couples:** Given their willingness to pay a higher average price per unit, explore opportunities for introducing premium or limited-edition chip varieties targeted specifically at **Mainstream Midage and Young Singles/Couples**.
    * **Value Focus for Budget Segments:** Continue offering competitive pricing and value packs for the **Budget - Older Families** segment, as their higher sales volume is driven by larger unit purchases.

4.  **Capitalize on Seasonal Peaks:**
    * Implement robust inventory planning and increased marketing efforts in the **lead-up to December** to maximize sales during this peak period. Develop specific holiday-themed promotions or limited-time offers to capture increased consumer spending.

5.  **Further Customer Segmentation and Store Performance Analysis:**
    * The performance of top-contributing **stores** (e.g., Store 226) will also be rigorously analyzed in **Task 2 of the retail strategy analytics** to identify best practices and potential for replication across the network.

By strategically acting on these insights, the business can optimize its retail strategy to enhance sales, improve customer engagement, and drive sustained growth within the chips category.
