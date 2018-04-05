# Predict_Weekly_Sales_Walmart

To predict the weekly sales of 45 Walmart stores provided by Walmart in their official data which may vary according to the holidays like Christmas, Thanksgiving etc. 

Historical sales data for 45 Walmart stores located in different regions. Three datasets:
1) Stores.csv: Contains information about the 45 stores, indicating the type and size of store.
2) Train.csv: Historical data from 2010-02-05 to 2012-11-01. Contains following fields- Store Number, Department Number, Date of the week, Weekly Sales, Whether the week is a special holiday week
3) Features.csv: Contains Store number, Date of the week, Average temp in region, Cost of fuel in region, Consumer Price Index, Unemployment rate, Whether the week is a special holiday week 

Steps:
1) Exploratory data analysis to find variables which could be used to predict sales. To find co-relation between various independent variables and weekly sales. 
2) Plotted graph to show mean weekly sales and type of store
3) Plotted graph to show mean weekly sales of each department during two weeks of Christmas and Thanksgiving 
4) Plotted line graph to compare sales of each year, we found out that there is similar pattern for sales in each year
5) Merged the datasets train data and stores. Dropped the irrelevant columns. Converted the categorical variable is_holiday to numerical
6) Plotted heat map to find the co-relation between different variables
7) Adding Previous year weekly sales data for the same date so that we can use it to predict sales of next year
8) Applied Linear Regression to predict sales of each week for each stores. Dependent variable - Weekly_sales. Independent variables - Prev_yr_sales, IsHoliday, Temperature

Recommendations:
1) Anticipate demand for that week and determine how many associates will be needed
2) Walmart can offer promotional schemes by grouping products from different departments to promote sales based on graph
3) Regulate the transportation frequency required for stock updation
