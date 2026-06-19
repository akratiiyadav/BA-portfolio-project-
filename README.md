# Business Analyst Portfolio Projects

Three end-to-end BA projects covering operations analysis, customer analytics, and demand forecasting — built to demonstrate real-world business analyst skills using SQL, Python, Excel, and Power BI.

---

## About Me
Akrati Yadav — Aspiring Business Analyst with hands-on experience in requirements gathering, process mapping, data analysis, and stakeholder reporting.

📧 akratiy68@gmail.com | 🔗 [LinkedIn URL] | 📍 Kanpur,Uttar pradesh

---

## Project 1: QuickKart — Order Management System (Operations Analysis)

**Business problem:** QuickKart, a fictional e-commerce platform, was facing 28% SLA breaches on deliveries, untracked returns, and 19% cart abandonment on mobile checkout.

**What I did:**
- Wrote a full Business Requirements Document (BRD) with stakeholder register and functional requirements
- Mapped the as-is and to-be order lifecycle process across 4 actors (Customer, OMS, Warehouse, Logistics)
- Ran SQL queries on the Olist e-commerce dataset to identify SLA breach rates by delivery zone and return rates by category
- Built a Power BI dashboard tracking on-time delivery rate, refund TAT, and cart conversion
- Wrote 9 user stories with acceptance criteria across 2 sprints in JIRA format

**Tools used:** SQL · Python (Pandas) · Power BI · Excel · JIRA · Confluence

**Dashboard:**

![QuickKart Dashboard](screenshots/quickkart_dashboard.png)
*Replace this image with your Power BI dashboard screenshot*

**SQL query and output:**

![QuickKart SQL](screenshots/quickkart_sql_query.png)
*Replace this image with a screenshot of your query + result table*

**Full project document:** [`QuickKart_OMS_BA_Project.docx`](./QuickKart_OMS_BA_Project.docx)
**SQL queries:** [`quickkart_queries.sql`](./quickkart_queries.sql)

---

## Project 2: RetailMart — Customer Segmentation (RFM Analysis)

**Business problem:** RetailMart's email engagement had dropped to an 8% open rate because every customer received the same generic campaign, regardless of purchase behavior.

**What I did:**
- Built an RFM (Recency, Frequency, Monetary) model in Python to segment 80,000+ customers into 6 actionable groups: Champions, Loyal, New, At Risk, Needs Attention, Lost
- Cleaned and transformed the UCI Online Retail II dataset using Pandas
- Built pivot tables in Excel to summarize segment value
- Designed a Power BI dashboard showing segment distribution and revenue contribution
- Wrote segment-specific marketing recommendations with projected business impact

**Tools used:** Python (Pandas) · Excel (Pivot Tables) · Power BI

**Segment distribution:**

![RFM Segments](screenshots/retailmart_segments.png)
*Replace this image with your segment distribution chart*

**Python notebook output:**

![RFM Code](screenshots/retailmart_notebook.png)
*Replace this image with a screenshot of your RFM scoring code + output table*

**Full project document:** [`RetailMart_Customer_Segmentation_Project.docx`](./RetailMart_Customer_Segmentation_Project.docx)
**Python notebook:** [`rfm_analysis.ipynb`](./rfm_analysis.ipynb)

---

## Project 3: GreenLeaf Mart — Sales Forecasting & Inventory Planning

**Business problem:** GreenLeaf Mart, a 12-store grocery chain, was losing an estimated Rs. 13 lakh per month combined from stockouts and overstock due to manual, gut-feel inventory ordering.

**What I did:**
- Built a 30-day demand forecast using Exponential Smoothing (Holt-Winters) on daily sales data
- Validated the model using MAPE (Mean Absolute Percentage Error), targeting under 15% error
- Translated the forecast into safety stock and reorder point recommendations per product category
- Identified weekly and monthly seasonality patterns (weekend spikes, month-end salary cycle effects)
- Designed a Power BI dashboard tracking forecast accuracy and reorder points

**Tools used:** Python (Pandas, Statsmodels, Scikit-learn) · Excel · Power BI

**Forecast vs actual:**

![Sales Forecast](screenshots/greenleaf_forecast.png)
*Replace this image with your actual-vs-forecast chart*

**Reorder point table:**

![Reorder Table](screenshots/greenleaf_reorder_table.png)
*Replace this image with your inventory recommendation table*

**Full project document:** [`GreenLeaf_Mart_Sales_Forecasting_Project.docx`](./GreenLeaf_Mart_Sales_Forecasting_Project.docx)
**Python notebook:** [`sales_forecasting.ipynb`](./sales_forecasting.ipynb)

---

## Skills Demonstrated Across All Projects

| Skill | Project 1 | Project 2 | Project 3 |
|---|---|---|---|
| Requirements gathering (BRD) | ✅ | | |
| Process mapping | ✅ | | |
| SQL | ✅ | | |
| Python (Pandas) | ✅ | ✅ | ✅ |
| Statistical modeling | | | ✅ |
| Excel (Pivot Tables) | | ✅ | ✅ |
| Power BI / Dashboarding | ✅ | ✅ | ✅ |
| Agile (JIRA user stories) | ✅ | | |
| Stakeholder documentation (Confluence) | ✅ | | |
| Customer segmentation | | ✅ | |
| Demand forecasting | | | ✅ |

---

## How to Use This Repo

1. Each project folder contains the full Word document with the business context, methodology, and recommendations
2. Each project's code (SQL/Python) is in its own file, runnable on the linked public datasets
3. Screenshots show real output — not mockups

## Datasets Used (all free and public)

- Project 1: [Olist Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) (Kaggle)
- Project 2: [Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) (UCI ML Repository)
- Project 3: [Store Item Demand Forecasting](https://www.kaggle.com/c/demand-forecasting-kernels-only) or [Rossmann Store Sales](https://www.kaggle.com/c/rossmann-store-sales) (Kaggle)

---

*Last updated: April 2026*
