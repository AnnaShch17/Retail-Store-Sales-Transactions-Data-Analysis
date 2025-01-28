# Retail-Store-Sales-Transactions-Data-Analysis

## Table of Content

[Project Overview](#project-overview)<br>
[Data Source](#data-source)<br>
[Tools](#tools)<br>
[Data Cleaning and Preparation](#data-cleaning-and-preparation)<br>
[Exploratory Data Analysis](#exploratory-data-analysis)<br>
[Results and Findings](#results-and-findings)<br>
[Data Visualization](#data-visualization)<br>
[Challenges in Analysis](#challenges-in-analysis)<br>

## Project Overview

The goal of this data analysis project is to get understanding of the business trends for the retail store in 2016.

Analyzing retail store sales transactions can provide important insights that help optimize business operations, boost sales, and improve the customer experience.


## Data Source

The dataset that I used for my analysis is [Retail Store Sales Transactions](https://www.kaggle.com/datasets/marian447/retail-store-sales-transactions/data). </br>

This anonymized dataset includes 64.558 unique transactions of 5.239 SKU's sold to 22.610 customers in a retail store during the year of 2016. I assume that the retail store is in Slovakia (as the owner of the dataset is located there according to his LinkedIn profile). Dataset contains the following information: Date of Sales Transaction, Customer ID, Transaction ID, SKU Category ID, SKU ID, Quantity Sold, Sales Amount. Also, I calculated Unit Price by dividing Sales Amount by Quantity Sold.

Detailed information on consumer goods sales gathered by scanning product barcodes at electronic points of sale in the retail store. This data includes information about quantities, characteristics, prices of the items sold.


## Tools

1.	Excel and Power Query - I used Excel and Power Query for Data Cleaning.
2.	Power BI - I used Power BI for Data Analysis.


## Data Cleaning and Preparation

During the initial data preparation phase, I completed the following tasks:
1.	Data loading and inspection.
2.	Handling errors, missing values, outliers.
   

## Exploratory Data Analysis

During the analysis of the retail store sales transactions, the following questions were considered:

1.	What are the total sales over different months?
2.	Which products and product categories generate the most profit?
3.	What is the average unit price per product category? 
4.	What is the total revenue and total quantity of items sold, and the total number of transactions?
5.	What type of customers (repeat customers or one-time buyers) contributes the most to the revenue?
6.	Are there seasonal impacts on customer purchasing behavior?


## Results and Findings

Analysis of the results indicates the following. 

#### Sales Performance Insights 

The total revenue generated from all transactions in 2016 was €1.58M. The most profitable month was December with €152K in sales, followed by May with €143K, and September and October with €141K each (see graph below). The spike in revenues during these four months might be related to the holidays as well as promotion campaigns - December 24-26 (Christmas Eve, Christmas Day, St. Stephens Day, respectively), May 1 (Labour Day) and 8 (end of WW2), September 1 (Constitution Day) and 15 (Day of Our Lady of Sorrows), no holidays in October (may be, customers bought stuff for November 1 (All Saints’ Day) and 17 (Day of Freedom and Democracy) holidays). 

![Total Revenue by Year and Month](https://github.com/user-attachments/assets/8cde7212-b62b-43a3-9718-81a1d8d133fa)


Sales started to slowly increase in January, reached their peak in May, then sales declined during the summer months. From September onward, there was a recovery, with the highest sales recorded in December (with a 30% rise in total sales compared to other months).

I assume that the increase in revenue was the result of the holiday promotions and special discounts which contributed to higher sales. 
By analyzing seasonal trends, similar campaigns can be planned for future seasons to increase revenue. Strategically planning promotional events, inventory replenishment, and marketing activities/efforts ahead of time will help to take advantage of peak shopping periods and holidays, maximizing sales opportunities.

#### Product Performance Insights

Top 20 SKU Categories (out of total number of SKU Categories equals 187) provide 55 % of revenue. 

![Total Revenue by SKU Category](https://github.com/user-attachments/assets/ea8a9434-095c-4f05-842e-d149198c8ba9)


The average unit price per these SKU Categories ranges from €34 to €129.
Number of unique products (SKU) is 5239. 

42% of overall sales come from a top 200 of top-selling products, while 58% of the inventory sees little movement. There is potential to improve inventory management by reducing low performing items and concentrating on restocking high-demand products to increase profitability. Also, cross-selling opportunities or bundle offerings around top selling products might be explored to boost average transaction value.

There is no information which product groups and products each SKU Category and SKU item numbers represent.

#### Customer Performance Insights

Analysis shows that 95.2% of customers are repeat buyers, contributing about 95% of total revenue, while the other 4.8% are one-time shoppers. Repeat customers completed about 125.000 transactions, and one-time buyers – about 6.000 transactions.

![Number of Transactions by Customer Type](https://github.com/user-attachments/assets/ea9ed320-c72f-4f98-bbec-0171f0ea1854)


However, the average amount spent in each transaction of repeat buyers (€12.01) is close to this indicator of one-time buyers (€11.45).

![Average Amount Spent per Transaction by Customer Type](https://github.com/user-attachments/assets/8fa44f82-399b-406b-95bb-2ca572f71422)


This indicates that the store is successful at retaining customers and building lasting relationships. To further strengthen customer retention, it will be useful to invest into personalization efforts, such as personalized product recommendations, exclusive deals or discounts, or birthday rewards as well as introducing tailored upsell and cross-sell offers based on past purchases.

However, overrelying on the repeat customers can present risks, such as market saturation or reduced customer growth if the customer base becomes too homogenous. To avoid that, diversifying of the customer base can be used by targeting new customers or exploring new market segments to reduce dependency on existing customers, and ensure long-term growth.

Although one-time shoppers represent a small segment of the customer base and generate limited amount of overall revenue, it is a good idea to implement strategies to convert one-time buyers into repeat customers. This could be done by sending follow-up emails, offers to encourage a second purchase, or an incentive for signing up for a loyalty program.



## Data Visualization

The dashboard includes a date filter that allows to sort the data by specific dates. There are three bar charts visualizing total revenue by year and months, total revenue by top 20 SKU Categories and total revenue by top 10 products. Also, a pie chart showing number of transactions by repeat customers and one-time buyers was created.

![Sales Analysis Dashboard](https://github.com/user-attachments/assets/fe1a4232-6861-4234-abff-4a934b8decb7)





