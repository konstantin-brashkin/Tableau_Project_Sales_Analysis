# Introduction

Hi! This is my **Tableau Portfolio Project** which involves working with SuperStore Sales🛒 Dataset.  
This project includes steps such as **Joining tables** together, **creating Calculated fields**, **creating Map chart** 🌍,
**Bar chart**📊, **Scatter plot** ● and **Line Area Chart**📈, and the final step is to combine all the visualizations into one
**Dashboard**!

You can download the actual **Tableau Packaged Workbook** from this repository or directly by this link: [Sales Analysis Tableau Project.twbx](/Sales%20Analysis%20Tableau%20Project.twbx/)  
Also here is the dataset I worked with: [SuperStore Sales DataSet.xlsx](/SuperStore%20Sales%20DataSet.xlsx/)

# Join Tables

First step is to import dataset into **Tableau**. The dataset contains three tables: Order, Product and Customer. In order to be able to combine data from these tables 
I established relationship between them:  
![1_join_tables.png](assets%2F1_join_tables.png)  
This will allow Tableau smartly and efficiently **Join**🔗 these tables together when needed.

# Creating Calculated Fields
My second step was to create **Calculated fields** from existing ones by using simple math formulas and build-in Tableau functions.

### 1. Shipping Time🚚
![2_shipping_time.png](assets%2F2_shipping_time.png)  
By using build-in function _"DATEDIFF()"_ I created a **Calculated field** that represents the number of days from the moment the product is ordered until it is actual delivered.
### 2. Profit Margin💰
![3_profit_margin.png](assets%2F3_profit_margin.png)  
Another useful **Calculated field** is Profit Margin, which I created by simply dividing the Sum of Profit by the Sum of Sales.
# Map Chart
Once all the preparations are complete, it's time to create some nice visualizations!  
First one is a **Map Chart**🌍:
![4_map_chart.png](assets%2F4_map_chart.png)  
This chart shows the total sales in different states of US, the size of the dots represents the number of sales and their color represents the profit margin.  
The larger the size, the more sales were made in that state. The closer the color to blue, the better is profit margin.  
For example, we can see that despite the fact that there is quite a large number of sales in the Pennsylvania state, however, its profit margin is not very good.
# Bar Chart
![5_bar_chart.png](assets%2F5_bar_chart.png)
# Scatter Plot
![6_scatter_plot_chart.png](assets%2F6_scatter_plot_chart.png)
# Line Area Chart
![7_line_area_chart.png](assets%2F7_line_area_chart.png)
# Building Dashboard
![8_dashboard.png](assets%2F8_dashboard.png)
# Conclusions


**Thank you for your attention!**


