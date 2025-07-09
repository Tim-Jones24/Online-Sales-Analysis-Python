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

#### Key Insights

🔹 Discounted products **positively correlated** with revenue  
🔹 Top 5 features contributing to revenue (Correlation Coefficients: 0.9926 to 0.289):
- **Discount Sales**
- **Unit Price**
- **Discount Amount**
- **Quantity Sold**
- **Product**

🔹 Revenue concentration was highest across **specific sales channels and regions**  
🔹 Not all high-quantity products contributed equally to revenue  
🔹 Product return rates varied significantly by product category



