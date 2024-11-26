# Project Background
Yellow Zen, a coffee bean store founded in 2019, wants to enhance their sales. To do this, they provide a dataset that includes detailed data on coffee orders, customer profiles and coffee products from January 2019 to August 2022. The goal is to extract valuable insights in order to drive business growth and improve customer engagement in the coffee industry. I am collaborating with the Sales and Marketing teams to analyze the data, adjust pricing and optimize marketing strategies. Leveraging these insights, we aim to increase sales, improve customer satisfaction, and ultimately drive revenue growth for coffee retailers.

**Key Business Metrics**:
* **Total Sales Revenue:** Total dollar amount from sales. We want to track this over time (monthly/yearly) to spot trends.
* **Sales by Product:** Revenue generated by different products (taking into account coffee type, roast type, and size). This helps better understand which items are driving sales.
* **Sales by Location:** Since the coffee store has multiple locations, understanding the performance of each is essential. This gives us an overview of sales in each location (e.g. which stores sells the most, which product is most popular, and/or what size is the favourite).
* **Sales by Month/Year:** Coffee shops often experience variations in sales depending on the time of the day or the season. Understanding these patterns can help with promotion timing.

**Insights and Recommendations** are provided on the following key areas:
* **Products Popularity:** An analysis of products trends.
* **Customer Preferences:** An evaluation of most in demand products among customers.
* **Regional Sales Variance:** An analysis of number of sales across each country.
* **Average Profit:** An assessment of products, understanding their impact on revenue.
* **Trends in Product Revenue Over Time & Seasonality:** An evaluation of revenue per products over month and year to better understand how to leverage marketing strategies based on trends and seasonality.



**Data Merging, Data Cleaning, and Dashboard:** The Excel file used to consolidate, analyze and visualize data can be found [here.](https://github.com/andrealopezp/CoffeeAnalysis/blob/main/coffee_analysis.xlsx)



# Data Structure & Initial Checks
Yellow Zen main database structure as seen below consists of three tables: "orders", "customers", and "products", with a total row count of 1,000 records.\
The merged dataset contains information about coffee bean sales.

![Data Structure](/assets/Dataset_ERD.png)

The dataset includes:
* **1. Orders:** Information about order details like date, quantity, and product type. By analyzing these variables we can extract purchasing behaviour which will help us identify opportunities for process optimization and marketing strategies.
* **2. Customers:** By examining clients' details such as customer demographics (city, country) and loyalty card, we can discover trends in customer preferences.
* **3. Products:** Details about products will help us know product popularity.



# Executive Summary

### Overview of Findings
Since its foundation in 2019, sales have shown steady growth, particularly in Arabica, Liberica, and Robusta, with Liberica seeing the biggest rise. The United States leads in sales, while Ireland and the United Kingdom lag behind. Customers tend to prefer larger packages (2.5 kg) and seasonal peaks indicate effective promotions. Additionally, the top transactions exceeded $200, highlighting valuable purchases, while the lowest one is $2,69. This difference suggests a broad variety of profiles making purchases ranging from affordable to premium. Liberica generates the highest profits, especially in light roasts. On the contrary, Robusta is the least profitable. Regarding roast preferences, they are similar, with medium and light roasts being the most popular in key markets.

The following sections will explore additional contributing factors and highlight key opportunity areas for improvement.

![Dashboard](/assets/Dashboard.png)



# Insights
An analysis has been carried out on the coffee bean sales available between January 2019 and August 2022 and useful observations have been extracted for making strategic decisions. Below we list the ideas:
* **1. Products Popularity**:
    * The most popular coffee bean across regions:
        * In the United States, with Arabica being the most popular coffee type (216 orders), followed by Excelsa (189 orders), Liberica (188 orders), and Robusta (181 orders).
        * In Ireland, the sales distribution is fairly consistent across various coffee types, with Arabica (41 orders), Liberica (39 orders), Robusta (38 orders), and Excelsa (35 orders).
        * In the United Kingdom, the most popular coffee type is Excelsa(23 orders), followed closely by Robusta (22 orders), Liberica (21 orders), and Arabica (7 orders).
    * As for the distribution of roast types, there is little variation. All types are consumed at similar rates.
        * In the United States, sales are alike for all types of roast, Medium is the most popular (267 orders), followed by Light (259 orders) and Dark (248 orders).
        * In Ireland, the most popular roast type is Dark (66 orders), followed by Light (48 orders) and Medium (39 orders).
        * In the United Kingdom, the different roasts have a very even distribution, Medium (28 orders) being the most popular, followed by Light (26 orders), and Dark (19 orders).
* **2. Customer Preferences**:
Generally, customers prefer to purchase the larger quantity packages over the smaller ones. That is, the preferred ones are those of 2,5 kg, followed by those of 1 kg, 0,5 kg and 0,2 kg.
* **3. Regional Sales Variance**:
The United States dominates the market (78%), while Ireland and the United Kingdom have the lowest number of orders (15% and 7% respectively).
* **4. Average Profit**:
    * Liberica shows the highest profits, particularly with Light roast type.
    * Excelsa and Arabica have different prices, and Light roast type is the one which produces higher profits too.
    * Robusta is the most affordable one and offers the fewest profits.
Regarding average transaction value (ATV):
    * The top transaction value is $220,79, followed by $218,73 and $204,93.
    * The lowest transaction value is $2,69.
* **5. Trends in Product Revenue Over Time & Seasonality**:
The trend shows a slight and stable growth over time, indicating increased demand or success in recent sales strategies. Specifically, we observe a steady increase in sales in three types of coffee beans: Arabica, Liberica and Robusta. Liberica being the one growing the most. On the contrary, a slight decrease is noticed in Excelsa.\
There are consistent peaks in sales during specific months, indicating a seasonal effect, which seems related to specific promotions since they do not coincide with holiday periods marked by the calendars of said countries.

# Recommendations
* **1. Products Popularity**
    * **Expanding Liberica Sales**: Considering that Liberica shows the strongest growth, especially in 2022, increase marketing efforts around this coffee type to capitalize on the trend, specially in the United States.
* **2. Customer Preferences**
    * **Optimizing Package Offerings**: Given the fact that customers prefer larger packages (2,5 kg), promote bundle deals or discounts on bulk purchases to  boost this trend and increase average order size.
* **3. Regional Sales Variance**
    * **Targeting the U.S. Market More Forcefully**: As the United States are the dominant market at the moment, allocate more resources to boost both the presence of the brand and customer engagement. You could potentially launch exclusive products or offers for this market to solidify its leading position.
* **4. Average Profit**
    * **Improving Robusta Profit Margins**: To enhance the profitability of Robusta, reassess pricing or consider repositioning it as a budget-friendly option.
* **5. Trends in Product Revenue Over Time & Seasonality**
    * **Leveraging Seasonal Peaks**: There are consistent sales spikes during specific months, plan specific promotions for these periods to maximize sales.



# Assumptions and Caveats
* **Missing Values:**
    * **Email and Phone Number:** In both columns, there are null values (206 and 135 respectively). We assume that customers did not provide their details. However, it could also be due to technical errors in data entry.
It would be necessary to consult and/or verify with the Data Collection Team to better understand the situation and, if necessary, agree on a solution that avoids missing data in the future.

* **External Factors:** It is vital to note that influences such as local regulations, economic changes or competitive actions could directly impact prices and, therefore, sales rates.



# Tech Stack
- **Tools**: Microsoft Excel



# Data Source
In this analysis regarding the coffee beans sales of Yellow Zen, datasets were downloaded from [Coffee Bean Sales.](https://www.kaggle.com/datasets/saadharoon27/coffee-bean-sales-raw-dataset)
