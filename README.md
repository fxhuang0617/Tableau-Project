# Tableau-Project
# Customer revenue analysis
## There are 6 tasks to do and then combine the 6 sheets to a dashboard. The dashboard can give us an interactive interface to look at the insight of the data in a visualization way.

1. Revenue per State
We have to use 'total' column as the row and 'State' as the column to create a map chart. The map chart can show us the total revenue for each state.
![image](https://github.com/fxhuang0617/Tableau-Project/blob/45c7a0108c536ad209e0e492c9ee4a2e9933dbde/Tableau_pic/Revenue%20per%20State.png)
We have to go to 'total' text format to set the numbers as currency in million.

2. Revenue based on month of the year
In this part, we have to firdst change the column month from string to date. Then we use month as the column and total revenue as the row. We also drag row to the label to let it show up the total revenue number for each month.
![image](https://github.com/fxhuang0617/Tableau-Project/blob/main/Tableau_pic/Revenue%20per%20month.png)

3. Revenue based on Age
In this task, we have to create bins for age in different group. We use 10 years as each gap. After age bins is created, we drag it as column and drag total revenue as row. In the detail format, we need to set the currency format and label the total revenue.
![image](https://github.com/fxhuang0617/Tableau-Project/blob/main/Tableau_pic/Revenue%20based%20on%20age.png)

4. Quantity and Discount correlation
We want to see the correlation between the customer buying and discount. So we set discount as percentage in the column and quantity in the row.
![image](https://github.com/fxhuang0617/Tableau-Project/blob/main/Tableau_pic/Quantity-Discount%20correlation.png)

5. Percentage of Revenue per Region
For this task, we want to know the revenue percentage in each region. Also, we would like to represent it in a donut chart.
To complete the donut chart, we have to create two pie charts, one for the percentage for each region, another for just a circle and leave it blank.
Then we use dual axis for two pie charts to merge together.
![image](https://github.com/fxhuang0617/Tableau-Project/blob/main/Tableau_pic/Revenue%20per%20region.png)

6. Revenue per Category per Gender
In this task, we can just put 'Gender' and 'Total' as columns and put 'Category' into row. And it will display like the following graph.
![image](https://github.com/fxhuang0617/Tableau-Project/blob/main/Tableau_pic/Revenue%20each%20gender%20in%20category.png)
In this display we can hardly to compare the difference between two genders of the overall revenue in each category. In order to have a more easy and comparable way to visualize the result, we would like to use a butterfly chart to represent it. In the butterfly chart we have to caclutae the total revevue for each gender seperately. And we reverse the direction of the female total revenue and add a zeroaxis between two gender graphs to put a category list. The result will like the following graph.
![image](https://github.com/fxhuang0617/Tableau-Project/blob/main/Tableau_pic/Revenue%20based%20on%20Gender.png)

## Dashboard
We like to summarize all of the tasks together to distribute to clients. The way we can do is building a dashboard report and create an interactive surface to give client a direct way to have the insight from different aspects.
![image](https://github.com/fxhuang0617/Tableau-Project/blob/main/Tableau_pic/Dashboard.png)
At the top of the dashboard, users can select category to see the corresponding graphs and numberws by the following tasks. Also, users can directly click on one of the task to see the corresponding insight on others tasks.
