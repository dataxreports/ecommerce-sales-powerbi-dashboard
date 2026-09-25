Data preparation was performed using Power Query in Power BI.

The following transformations were completed:

Reviewed the dataset and checked the available fields.
Verified and adjusted data types for date, numeric, and text columns.
Created an Order Year field from Order Date.
Created an Order Month field for monthly sales analysis.
Created an Order Month Number field to sort months chronologically.
Created an Order Quarter field for quarterly analysis.
Created a Shipping Days field by calculating the difference between Ship Date and Order Date.
Shipping Days Calculation

The Shipping Days column was calculated using:

Duration.Days([Ship Date] - [Order Date])

The Order Month field was sorted by Order Month Number to ensure that monthly charts display months in calendar order rather than alphabetical order.
