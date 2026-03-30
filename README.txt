Samsung Supply Chain & Logistics Dashboard
Built with Power BI | Author: Sagar Singh
==========================================

PROJECT OVERVIEW
----------------
This Power BI dashboard provides a comprehensive view of Samsung's Supply Chain and
Logistics operations. It is designed to help business stakeholders monitor key performance
metrics across suppliers, inventory, shipments, and customers — all in one place.


DASHBOARD PAGES (6 Pages)
--------------------------

1. HOME
   - Landing page of the dashboard
   - Navigation buttons to all sections: Overview, Supplier, Inventory, Shipment, Customer
   - Samsung branding with Supply Chain & Logistics theme


2. OVERVIEW
   Key business KPIs at a glance:
   - Gross Revenue      : 186.86M
   - Profit             : 48.56M
   - Total Revenue      : 176.95M
   - Profit Margin %    : 55.84%
   - Total Shipment     : 8K
   - Perfect Order %    : 75%

   Visuals included:
   - Supplier by Lead Time (bar chart)
   - Inventory Stock by product
   - Total Delay Shipment by carrier
   - Total Revenue by customer name


3. SUPPLIER
   Detailed supplier performance analysis:
   - Sum of Total Cost  : 78.13M
   - Sum of Orders      : 129K
   - Avg Lead Time      : 11.53 days
   - Avg Quality Score  : 96.63
   - Avg Unit Cost      : 880.71
   - Count of Suppliers : 7

   Visuals included:
   - Unit Cost by Month (line chart)
   - Avg Lead Time by Country (China, Japan, South Korea, Taiwan, India, Vietnam)
   - Avg Lead Time by Supplier Name
   - Order Quantity by Supplier Name
   - Unit Cost by Supplier Name
   - Avg Quality Score by Supplier Name


4. INVENTORY & PRODUCTION
   Inventory health and production defect tracking:
   - Inventory Value    : 160K
   - Safety Stock       : 89K
   - Turnover Rate      : 1.17
   - Days of Inventory  : 311.88
   - Avg Defective Units: 5.36
   - Defective Units    : 24K

   Visuals included:
   - Average Defective Units by Month (line chart)
   - Inventory Value by Month (line chart)
   - Defect Rate by Product Name (Galaxy S24 Ultra highest at 4.3K)
   - Current Stock vs Safety Stock vs Reorder Point by Product (grouped bar chart)


5. SHIPMENT
   Logistics and delivery performance:
   - Total Shipment     : 8K
   - Shipment Cost      : 19.42M
   - Total Delay        : 573
   - Total Shipment Qty : 3M
   - Total Delivered    : 6K
   - Delivered %        : 75.29%

   Visuals included:
   - Total Delay & Total Delivered Ship by Carrier (grouped bar)
   - Total Shipment by Status - Delivered (75.29%), In Transit, Delayed, Processing
   - Total Delay by Carrier (Maersk Line highest: 87)
   - Shipment Cost by Month (line chart)
   - Total Delay by Delay Reason (Carrier Capacity: 90, Documentation Issue: 78...)


6. CUSTOMER
   Revenue and profitability from customer perspective:
   - Gross Revenue      : 186.86M
   - Profit             : 48.56M
   - Total Revenue      : 176.95M
   - Profit Margin %    : 55.84%
   - Discount Amount    : 9.92M
   - Perfect Order %    : 75%

   Visuals included:
   - Profit by Channel Type (Online 41.49%, Retailer 40.28%, Direct)
   - Revenue by Channel Type (donut chart)
   - Revenue by Customer Name (Amazon, Flipkart, Best Buy, MediaMarkt, Samsung Direct)
   - Profit by Product Name (Galaxy S24 Ultra: 9.2M highest)
   - Total Revenue, Profit & Growth Revenue by Month (combo chart)


TOOLS & TECHNOLOGIES USED
--------------------------
- Tool       : Microsoft Power BI Desktop
- Data Tables: dim_customer, dim_date, dim_facility, dim_product, dim_supplier,
               fact_inventory, fact_procurement, fact_production, fact_sales, fact_shipment
- Visuals    : Bar charts, Line charts, Donut charts, KPI cards, Combo charts
- Navigation : Button-based page navigation


KEY INSIGHTS
------------
1. Profit Margin is strong at 55.84% — healthy business performance
2. Maersk Line causes the most shipment delays (87) — needs attention
3. Galaxy S24 Ultra has highest defect rate (4.3K) — quality review needed
4. 75.29% deliveries are on time — room for improvement
5. Amazon.com Inc. is the top revenue customer (37M)
6. Carrier Capacity is the #1 reason for delays (90 cases)
7. China & Japan have the highest avg lead times (12.5 & 12.4 days)


AUTHOR
------
Sagar Singh
Dashboard created: March 2026
