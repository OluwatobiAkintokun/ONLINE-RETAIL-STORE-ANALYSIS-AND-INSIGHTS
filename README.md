# PROJECT ONLINE RETAIL STORE

# PROJECT RECAP
An online retail store has hired me as a consultant to review their data and provide insights that would be valuable to the CEO and CMO of the business. The business has been performing well and the management wants to analyse what the major contributing factors are to the revenue so they can strategically plan for next year.

The leadership is interested in viewing the metrics from both an operations and marketing perspective. Management also intends to expand the business and is interested in seeking guidance into areas that are performing well so they can keep a clear focus on what’s working. They would also like to view different metrics based on the demographic information that is available in the data.

# BUSINESS QUESTIONS

1. The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.

2. The CMO is interested in viewing the top 10 countries which are generating the highest revenue for the year 2011 only. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.

3. The CEO is looking to gain insights on the demand for their products for the year 2011. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.

4. The CMO of the online retail store wants to view the information on the top 10 customers by revenue for the year 2011. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.

# DATASET

There is only one dataset provided for this analysis.

**Online Retail-** The online retail dataset consists of the following column names: Invoice No, Stock code, Quantity, Invoice Date, Unit Price, Customer ID, and Country. (Online Retail doc attached)

# DATA CLEANING AND TRANSFORMATION
1. I filtered out quantities below 1 in the 'Quantity' column.
2. I eliminated entries with unit prices below $0 in the 'Unit Price' column.
3. I excluded outliers denoted by an asterisk (*) in the 'Description' column.
4. I removed entries where the country is listed as 'Unspecified' in the 'Country' column.
5. I excluded data pertaining to the year 2010 from the table, as it is not relevant to the business question.
6. I split the 'Invoice Date' column into three individual columns: 'Year', 'Month', and 'Quarter' as part of the data cleaning and analysis process.
7. I created a new column named 'Revenue' by applying the following formula: Revenue = (Unit Price * Quantity). The application of this formula, serves the purpose of deriving both the Revenue per product and the overall Total Revenue, thereby contributing to a comprehensive understanding of the financial performance of the store.

Note: I performed data cleaning using Microsoft Excel.

# DATA ANALYSIS

1. The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.
   
![image](https://github.com/Tanpepper29/DATA-VISUALIZATION-/assets/137109080/93735b68-ec7e-45a5-969f-931cbe60f62c)

2. The CMO is interested in viewing the top 10 countries which are generating the highest revenue for the year 2011 only. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.
   
![image](https://github.com/Tanpepper29/DATA-VISUALIZATION-/assets/137109080/c9f7ca18-a201-461f-b0ba-0b0a51b5f029)

3. The CEO is looking to gain insights on the demand for their products for the year 2011. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.
   
![image](https://github.com/Tanpepper29/DATA-VISUALIZATION-/assets/137109080/3eaae579-6b4c-4fde-bc9c-a53226712203)

4. The CMO of the online retail store wants to view the information on the top 10 customers by revenue for the year 2011. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.
   
![image](https://github.com/Tanpepper29/DATA-VISUALIZATION-/assets/137109080/2d520ab5-42a4-4d34-98f9-50adef0ada6d)

# DATA VISUALIZATION

I created a user-friendly and interactive dashboard with Power BI to showcase the outcomes of the data analysis.

![image](https://github.com/Tanpepper29/DATA-VISUALIZATION-/assets/137109080/23e9d57b-a84b-4faf-a311-1ee9b0237353)


# INSIGHTS AND RECOMMENDATIONS


1. The CEO has requested a trend of the revenue to identify potential seasonality in store sales. My analysis reveals exceptional growth during specific months. For the first 8 months, revenue maintains a consistent average of around £685k. However, a substantial upturn in revenue begins in September, with a 40% increase from the previous month.  This positive trend continues till November, reaching the highest monthly revenue of £1.5m. This analysis shows the impact of seasonality on retail store sales, particularly observed in the final four months of the year.

2. The countries leading in revenue performance for the store are Netherlands, EIRE, Germany, France, Australia, Spain, Switzerland, Belgium, Sweden, and Norway. The United Kingdom is not included in this analysis, given its already high demand. The emphasis is placed on countries where there is room for increased demand. These top performing nations consistently showcase the store's strong market presence and customer engagement across different regions. It is recommended to concentrate efforts on these markets and further capitalize on their sales potential.

3. In the third analysis, the map chart provides a visual representation of revenue distribution among various regions. Apart from the United Kingdom, countries such as the Netherlands, Ireland, Germany, France, and Australia demonstrate potentials for a significant revenue. It is recommended to allocate more investments in these regions to increase demand for products. Additionally, the map shows a concentration of sales in the European region, with little activity in the American region. Surprisingly, there is currently no demand for our products in Africa, Asia, and Russia. Implementing a new strategy tailored to these regions has the potential to boost sales revenue and profitability.

4. Finally, a detailed analysis was conducted on the top 10 customers who have consistently made significant purchases from the store. The data reveals a relatively small variation in the purchases made by these top customers. Specifically, the customer **(Customer ID- 14646)** generating the highest revenue surpassed the second highest **(Customer ID- 18102)** by 17%. This signifies that the store is not relying on a few customers to generate the revenue. This data shows that customers have limited bargaining power, and the store is in a good position.










