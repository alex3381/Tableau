# Unveiling Pizza Sales Insights through Key Metrics (Tableau)

In my quest to gain a thorough understanding of our business performance, The dataset was transferred from Microsoft SQL Studio to Tableau. I employed Tableau for an in-depth analysis of pivotal indicators within our pizza sales data. The goal was to compute and visually represent vital metrics, encompassing total revenue, average order value, total pizzas sold, total orders, and average pizzas per order.


https://github.com/alex3381/Tableau/assets/59268114/38692179-9c16-40c1-b9e2-16e262cba7b7




# Calculation of Total Revenue:

I crafted a calculated field named "Total Revenue" by summing up all prices.
I utilized the SUM function along with dimensions categorized as discrete and continuous fields, featuring fixed values for dimensions.

# Calculation of Average Order Value:

I derived "Average Order Value" by dividing total revenue by the total number of orders.
A field named "Total Orders" was created, employing the COUNTD([Order Id]) function for distinct counting.

# Calculation of Total Pizzas Sold:

"Total Pizzas Sold" was computed by summing up the quantities of all pizzas sold.
A field named "Total Pizzas Sold" was created using the SUM([Quantity]) function.

# Calculation of Average Pizzas Per Order:

The "Average Pizzas Per Order" was calculated by dividing "Total Pizzas Sold" by "Total Orders" ([Total Pizzas Sold]/[Total Orders]).

# Visualization in Tableau:

The calculated metrics were imported into Tableau for visualization.
Column configuration involved measure names and measure values.
The view was adjusted from standard to entire view.
Relevant metrics were selected and arranged based on the problem statement.
The dataset underwent cleaning and formatting to enhance visualization clarity.

This Tableau analysis delivers a dynamic and interactive representation of key pizza sales metrics, fostering a deeper comprehension of our business performance.
