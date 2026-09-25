Four DAX measures were created to support the dashboard.

Total Sales
Total Sales = SUM(train[Sales])

Calculates the total sales amount across the selected data.

Total Orders
Total Orders = DISTINCTCOUNT(train[Order ID])

Counts unique orders rather than individual product rows.

Average Order Value
Average Order Value = DIVIDE([Total Sales], [Total Orders])

Calculates average sales per unique order.

Average Shipping Days
Average Shipping Days = AVERAGE(train[Shipping Days])

Calculates the average number of days between order date and ship date.
