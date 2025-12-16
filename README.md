# Marketing Campaign Dashboard – Power BI
This project analyzes and visualizes customer campaign performance using Power BI. It helps identify high-value customer segments and channel effectiveness, providing data-driven insights for optimizing future marketing strategy.

## Objective
* How well did the campaign perform based on Revenue and Response Rates?
* Which Shopper Types (Store, Online) drive the most value and transactions?
* Which customer segments (Loyalty, Marital Status) are most receptive to campaigns?

## Tools Used
* Power BI – for data visualization and interactive dashboard creation.
* CSV / Excel – for source data management (Marketing Campaigns Data Set).
* DAX – for creating key performance indicators (KPIs) and custom measures like CPR%.

## Dataset
* File: Marketing Campaign/Customer Profile Data (implied).
* Key Metrics: Total Revenue, Total Transactions, Total Campaign Responses, and the calculated CPR% (Complaint Rate).

## Dashboard Overview
### Page 1: Campaign Analysis (Performance & Flow)
* **KPIs:** Displays the high-level metrics for performance (Revenue, Transactions, Responses) and risk (CPR%).
* **Customer Flow:** Uses a **Decomposition Tree** to analyze campaign response by tracking Shopper Type → Loyalty → Marital Status.
* **Trends:** Shows the Yearly Revenue Trend and the ratio of Complaining Customers.

### Page 2: Shopper Behavior (Value & Demographics)
* **Sales Focus:** Compares Total Sales and Orders across different Shopper Types (Store, Online, Both).
* **Demographics:** Distributes Revenue by Marital Status (e.g., Married contributes the highest share).
* **Order Volume:** Analyzes Orders by Family Size, revealing that smaller households place the most transactions.
