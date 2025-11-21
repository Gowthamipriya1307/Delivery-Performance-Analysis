# Last-Mile Delivery Performance Analysis

## Overview
This project focuses on conducting a comprehensive analysis of **last-mile delivery performance** using a dataset of 200 package deliveries. The primary goal is to identify operational strengths, determine the main drivers of Service Level Agreement (SLA) breaches, and provide actionable recommendations for improvement across warehouses, cities, and courier performance.

The analysis is structured following standard **business intelligence** and **Excel dashboard** creation practices, ensuring outputs are intuitive and easily consumable by operational teams.

---

## Project Files & Key Outputs

| File / Output | Description |
|---------------|-------------|
| `delivery_performance.csv` | The raw dataset used for all analytical work. |
| `delivery_dashboard.xlsx` | Complete Excel workbook with raw data, helper columns, pivot tables, KPI calculations, and the final dashboard presentation. |
| `dashboard.png` | Static snapshot of the final dashboard layout. |
| KPI Cards | Quick-view metrics including **Average Delivery Hours**, **Overall SLA Breach Rate**, and **Percentage of Delayed Orders**. |
| Pivots & Charts | Visual breakdowns of performance by **City**, **Warehouse**, and **Delay Reason**. |

---

## Key Insights

- **Location Bottlenecks:**  
  Bangalore (BLR1) has the **highest Average Delivery Hours (~14.39 hrs)** and **highest SLA Breach Rate (~51.52%)**, indicating a localized need for operational review.

- **Root Cause Focus:**  
  Top delay reasons are **Traffic**, **Hub Delay**, and **Weather** (~57 incidents each). Focusing on **reducing Hub Delay** provides the most direct operational win.

- **Pickup Lag Impact:**  
  Average time from order acceptance to package pickup is **1.37 hours**, contributing nearly **9%** to total fulfillment time, highlighting a critical internal hand-off efficiency gap.

---

## Action Recommendations

1. **Targeted Warehouse Review:**  
   Conduct a process audit and increase staffing at **BLR1 Warehouse** to reduce internal Hub Delay issues driving high SLA breach rates.

2. **Lag Time Alerting:**  
   Implement automated alerts for packages breaching a **1.5-hour Pickup Lag** to trigger corrective actions and expedite dispatch.

3. **Courier Performance Optimization:**  
   Identify worst-performing couriers (high delivery times despite low volume) for **re-training, shift capacity adjustment, or route optimization** strategies.

---

## Dashboard Overview
The Excel dashboard provides an interactive and visual representation of the metrics and insights, allowing operational teams to quickly identify problem areas and monitor improvements.

---

## Technologies & Tools
- **Excel**: For data cleaning, pivot tables, KPI calculations, and dashboard creation.
- **CSV**: Source data format.
- **PNG**: Dashboard snapshot for reference.

---

## License
This project is for internal analysis purposes and can be adapted for operational performance monitoring in last-mile delivery operations.
