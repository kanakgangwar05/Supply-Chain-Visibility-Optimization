# Supply Chain Visibility & Optimization – Milestone 2

## Overview

This milestone focuses on developing interactive Power BI dashboards to analyze inventory performance and delivery efficiency. The dashboards provide business insights into inventory management, stock optimization, and delivery performance using DAX measures, KPIs, and interactive visualizations.

---

## Inventory Turnover Calculation Approach

Inventory Turnover Ratio is used to evaluate how efficiently inventory is utilized over a period.

**Formula:**

**Inventory Turnover = Sales / Average Inventory**

If Cost of Goods Sold (COGS) is unavailable in the dataset, total sales are used as an approximation. A higher turnover ratio indicates efficient inventory management, while a lower ratio may indicate excess or slow-moving inventory.

---

## Slow-Moving and Fast-Moving Inventory Identification Logic

Products are classified based on their inventory movement and stock levels.

* **Fast-Moving Products:** Products with high sales and frequent inventory turnover.
* **Slow-Moving Products:** Products with low sales and inventory remaining in stock for longer periods.
* **Out of Stock:** Products with zero available stock.
* **Reorder Required:** Products whose current stock is below the defined reorder level.
* **Safe Stock:** Products with stock above the reorder level.

This classification helps identify products that require replenishment and products that may lead to excess inventory costs.

---

## Delivery Performance Analysis Methodology

The Delivery Performance Dashboard evaluates logistics efficiency using the following metrics:

* **On-Time Deliveries:** Deliveries completed on or before the expected delivery date.
* **Delayed Deliveries:** Deliveries completed after the expected delivery date.
* **Delivery Lead Time:** Calculated as the number of days between the order date and the delivery date.
* **Late Delivery Risk:** Categorized based on delivery delays to identify high-risk shipments.
* **Regional and Shipping Mode Analysis:** Delivery performance is analyzed across different regions and shipping methods to identify operational bottlenecks.

---

## Dashboards Developed

### Inventory Analytics Dashboard

* Inventory Turnover Ratio
* Stock Level Monitoring
* Safety Stock and Reorder Level Analysis
* Slow-Moving vs Fast-Moving Products
* Inventory by Warehouse
* Inventory by Region
* Inventory by Product Category
* Inventory Trend Analysis Over Time

### Delivery Performance Dashboard

* On-Time vs Delayed Deliveries
* Average Delivery Lead Time
* Late Delivery Risk Analysis
* Delivery Performance by Region
* Delivery Performance by Shipping Mode
* Delivery Trend Analysis
* Regional and Product-Level Drill-Downs

---

## Key Insights

* Inventory turnover helps identify products with efficient and inefficient stock movement.
* Slow-moving inventory can increase storage costs and should be reviewed regularly.
* Monitoring reorder levels helps prevent stockouts and ensures product availability.
* Delivery performance varies across regions and shipping modes, highlighting opportunities for process improvement.
* Tracking delivery lead time enables better logistics planning and customer satisfaction.

---

## Business Recommendations

* Regularly monitor inventory turnover to optimize stock levels.
* Reduce excess inventory by promoting or discounting slow-moving products.
* Increase safety stock for high-demand products to prevent stock shortages.
* Improve delivery planning in regions with frequent delays.
* Evaluate shipping modes with higher delay rates and optimize logistics operations.
* Use dashboard insights for proactive inventory replenishment and delivery performance monitoring.

---

## Tools & Technologies

* Microsoft Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* Star Schema Data Model
* Interactive Dashboards and Visualizations

---

## Project Deliverables

* **Milestone2_PowerBI.pbix**
* **Inventory Analytics Dashboard**
* **Delivery Performance Dashboard**
* Dashboard Screenshots

This dashboard enables stakeholders to monitor inventory health, improve supply chain efficiency, and make data-driven decisions for inventory optimization and delivery performance.
