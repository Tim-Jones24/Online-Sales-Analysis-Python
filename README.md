# Online Sales Analysis-Python
This repository contains an end-to-end data analysis project on online sales transactions using Python. It includes data preprocessing, enrichment, business insights, visualizations, and correlation analysis.


### 🛒 End-to-End Online Sales Transactions Analysis Using Python

This project presents a complete data analytics pipeline that transforms raw online transaction data into actionable business insights. From data cleaning and enrichment to deep analysis and visualization, this project answers key business questions that help inform strategic decisions around product performance, regional demand, revenue growth, and discount impact.

---

#### Project Overview

In an increasingly digital world, online retailers generate vast amounts of transactional data daily. However, raw data is rarely clean, consistent, or ready for decision-making. This project uses **Python** and powerful data analysis libraries such as **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, and **Scikit-learn** to extract meaningful insights from online sales transaction data.

Through careful **data cleaning**, **data enrichment**, **visual storytelling**, and **correlation analysis**, the project delivers high-impact insights relevant to business and product teams.

---

####  Business Questions Answered

The following key questions were explored and answered:

1. **Product Return Insight**  
   - How many products were returned, not returned, or unspecified?

2. **Total Revenue Across Sales Channels**  
   - Which channels drive the highest revenue?

3. **Quarterly Revenue Trends (2023–2024)**  
   - How does revenue vary across quarters?

4. **Monthly Sales Trend**  
   - What does the monthly sales pattern look like over time?

5. **Total Revenue by Region**  
   - Which regions contribute most to total revenue?

6. **Regional Demand Insight**  
   - What is the total quantity of products sold per region?

7. **Demand Trend (Monthly Quantity Sold)**  
   - How does quantity sold fluctuate over months?

8. **Discount Impact on Sales**  
   - Are discounted products significantly contributing to total revenue?

9. **Total Revenue by Product Category**  
   - Which product categories are most profitable?

10. **Top 5 Products by Revenue**  
    - Which products generate the most revenue?

11. **Top Revenue Drivers via Correlation Analysis**  
    - What are the top contributing factors to revenue?


#### 🛠️ Tools & Technologies Used

| Tool                 | Purpose                                     |
|----------------------|---------------------------------------------|
| **Python**           | Core programming language                   |
| **Pandas**           | Data manipulation & preprocessing           |
| **NumPy**            | Numerical computations                      |
| **Matplotlib**       | Data visualization                          |
| **Seaborn**          | Statistical visualizations                  |
| **Scikit-learn**     | Correlation analysis                        |
| **Jupyter Notebook** | Interactive development & presentation      |

#### Data Cleaning & Enrichment

✅ Checked and handled missing values  
✅ Corrected misspelled values for data consistency  
✅ Recalculated `Total Sales` (Revenue) from Unit Price × Quantity  
✅ Created new features:
- `Discount Amount`
- `Discount Sales`
- `Year`, `Month`, `Month Number`, `Quarter` (for trend analysis)

---
### Key Insights & Recommendations

#### 🔍 Summary of Key Insights

From the comprehensive analysis of the online sales transaction dataset, the following actionable insights were uncovered:

1. **Retail Sales Channel Dominates Revenue**

   * The majority of revenue was generated through retail channels, indicating that customers often purchase in bulk through this channel.

2. **Quarterly and Monthly Revenue Trends**

   * Peak revenue was recorded in **Q1**, particularly in **January and November 2023**, suggesting seasonal demand patterns or promotional events.

3. **Top Performing Region**

   * The **Northern region** led in revenue performance, contributing a total of **₦243,329**, making it the most lucrative market.

4. **Impact of Discounts on Revenue**

   * Discounted sales had a significant positive influence on revenue, highlighting the effectiveness of discount strategies in driving volume.

5. **Leading Product Category**

   * The **Laptop** category outperformed all others, generating a total of **₦260,648**, establishing it as the most profitable product category.

6. **Top 5 Revenue-Generating Products**

   * All top 5 products by revenue were laptops:

     * **Lenovo ThinkPad**
     * **HP Spectre**
     * **Dell XPS13**
     * **MacBook Air**
     * **Pixel 7**

7. **Top Revenue Drivers Identified via Correlation Analysis**

   * Five primary factors contributing to revenue were identified with high correlation scores:

     * **Discount Sales**
     * **Unit Price**
     * **Discount Amount**
     * **Quantity Sold**
     * **Product**

---

#### Business Recommendations

Based on the insights derived, the following recommendations are proposed for improved decision-making and sales optimization:

1. **Double Down on High-Performing Channels and Regions**

   * Focus marketing and logistics efforts on **retail sales channels** and the **Northern region**, which show strong customer demand and revenue contribution. Consider creating exclusive deals or incentives in these areas to maintain momentum.

2. **Promote Laptops and Plan Seasonal Campaigns**

   * Given the dominance of laptops in the top-performing products and categories, **increase inventory, marketing, and promotional campaigns** for laptop products—especially leading up to **Q1 and months like January and November** to maximize peak-season sales.

3. **Leverage Discount Strategies Strategically**

   * Since discounted sales significantly boost revenue, implement **targeted discount campaigns**—especially on high-margin products—to encourage higher volumes while maintaining profitability. Dynamic pricing models can be introduced to optimize discount effectiveness.

---

#### Acknowledgments
Special thanks to Jude Raji for providing the dataset and the open-source community and Python ecosystem for making robust tools for data analysis accessible and efficient.

📫 Contact
Project by: Jones Osele
Role: Data Analyst | ML
📧 Reach me on LinkedIn : https://www.linkedin.com/in/osele-jones/



