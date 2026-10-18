#Sales Performance Dashboard | Excel Portfolio Project
Author: Srikanth Kamuni
Project type: Sales analytics · Excel dashboard · Pivot tables
#Project description
An Excel-based sales performance dashboard analyzing 2,000 order records across products, regions, channels and customer types. The project organizes transaction data into reusable sales KPIs and segmented summaries to support business reporting and exploratory analysis.
#Business problem
Sales teams need a reliable way to monitor revenue, order volumes and unit sales while identifying differences across channels, geographic regions and product categories. Reviewing raw orders alone makes comparisons and trends harder to interpret. This workbook uses Excel summaries and a dashboard to present the sales data in a more accessible format.
#Dataset overview
- Worksheet: Sales_Data
- Records: 2,000 rows
- Columns: 12
- Date range: 2026-01-01 to 2026-12-31
- Other worksheets: Pivot_Table, Dashboard
- Currency: Not specified in the workbook
- Provenance: Not documented; publication rights should be confirmed
#Key performance indicators
KPI	Value	Calculation
Total revenue	3,462,605.32	SUM(Revenue)
Unique orders	2,000	Distinct count of Order ID
Units sold	7,552	SUM(Quantity)
Average revenue per order	1,731.30	Total revenue / unique orders


#Data dictionary
Column	Definition
Order ID	Unique identifier for a sales order; use distinct counts when reporting orders.
Date	Recorded order date, used for month-based trends.
Region	Geographic sales territory or business region.
Sales Channel	Route through which an order was sold (e.g., Online or Retail Store).
Customer Type	Customer segment classification (New or Returning).
Product Category	Broad classification of the product sold.
Product	Specific item purchased.
Salesperson	Sales representative associated with the order.
Quantity	Number of units included in the order.
Unit Price	Listed price per unit in unspecified currency.
Discount	Recorded discount fraction; e.g., 0.05 represents 5%.
Revenue	Recorded order revenue after applicable discount, subject to rounding.


Analysis dimensions
The workbook supports comparisons by month, region, sales channel, customer type, product category, product, and salesperson.
Workbook structure
- Sales_Data: Order-level source records.
- Pivot_Table: KPI summaries and grouped revenue calculations.
- Dashboard: Excel dashboard layout and visual reporting objects.
How to use
1. Open Sales Dashboard.xlsx in Microsoft Excel desktop.
2. Review the Sales_Data table and Pivot_Table summaries.
3. Navigate to Dashboard to explore the visuals and available interactive controls.
4. If source data is modified, refresh the workbook's pivot tables and verify KPI totals.
Data quality and interpretation
- Revenue is not equivalent to profit.
- Currency, data origin, and extraction method are not specified.
- The workbook includes 2026 dates beyond the current date; treat it as a practice dataset unless its provenance is established.
- Verify data rights and any personal information before public distribution.
- Validate dashboard visuals in Excel; not all chart and slicer objects are visible to simple worksheet readers.
