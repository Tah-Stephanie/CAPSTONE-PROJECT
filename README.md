# Global-Superstore Dashboard

![](https://github.com/Tah-Stephanie/CAPSTONE-PROJECT/blob/main/Cover%20Page.png)

## Introduction
This Power BI project is a Capstone project which aims at analysing data from an unknown store called “Global Superstore”. The project report answered all the business questions which will in turn help in drawing out meaningful insight from the Superstore dataset which would aid management in making informed decisions to improve performance and profitability. 
**_ Disclaimer_** The dataset used do not represent any company or country but just as imaginary data used to perform some analysis

### Problem statement

Question 1. a) What are the three countries that generated the highest total profit for Global Superstore in 2014? b) For each of these three countries, find the three products with the highest total profit. Specifically, what are the products’ names and the total profit for each product? 

Question 2. a) Identify the 3 subcategories with the highest average shipping cost in the United States. 

Question 3. a) Assess Nigeria’s profitability (i.e., total profit) for 2014. How does it compare to other African countries? b) What factors might be responsible for Nigeria’s poor performance? You might want to investigate shipping costs and the average discount as potential root causes. 

Question 4. a) Identify the product subcategory that is the least profitable in Southeast Asia. Note: For this question, assume that Southeast Asia comprises Cambodia, Indonesia, Malaysia, Myanmar (Burma), the Philippines, Singapore, Thailand, and Vietnam. b) Is there a specific country i n Southeast Asia where Global Superstore should stop offering the subcategory identified in 4a?

 Question 5. a) Which city is the least profitable (in terms of average profit) in the United States? For this analysis, discard the cities with less than 10 Orders. b) Why is this city’s average profit so low? 

Question 6. a) Which product subcategory has the highest average profit in Australia?
 
Question 7. a)Who are the most valuable customers and what do they purchase?

### Skills and concepts demonstrated

-The following skill sets were used: 
-Data cleaning
-Data transformation
-Data Modelling
-DAX
-Filters
-Power Query
-Data Visualization

### Modelling
![](https://github.com/Tah-Stephanie/CAPSTONE-PROJECT/blob/main/Data%20Model%20Global%20superstore.png)
The sourced dataset had 3 tables, all which were fact tables hence no direct relationship could be established between them.

Using power query, a calendar table was created which was then directed linked to one of the fact table ‘Orders’.

The model type was a star schema because we had one dimension table linked to one fact table. The 2 other fact tables did not have any active relationship and were also not useful for our analysis.

## Visualisations
The report is made up of 2 pages which answers the 7 business questions
![](https://github.com/Tah-Stephanie/CAPSTONE-PROJECT/blob/main/Global%20Superstore%20Dashboard%201.png)
![](https://github.com/Tah-Stephanie/CAPSTONE-PROJECT/blob/main/Global%20superstore%20Dashboard%202.png)

### Features
The 3 slicers are used to filter our report according to Country, Market, and Segment

### Analysis:

#### Sales analysis
![](https://github.com/Tah-Stephanie/CAPSTONE-PROJECT/blob/main/Sales%20Analysis.png)
Total profits made from sales equal 1.5 million
Total sum of sales equals 12.6 million
Number of orders made equal 51k
Number of customers equals 795
Number of product segments equals 3

#### Country analysis
! [] ()
Number of countries equals 147

#### Profit analysis by country in the year 2014
! [] ()
Top 3 countries which generated the most profit in 2014 include:
 The United States which generated a profit of 93,403.98k
 India  which generated a profit of 48,435.11k
 China  which generated a profit of 46,646..30k
 
#### Product profit analysis by country
! [] ()

The product with the highest profit in the United States include:

Canon Image Class with a 25.2k profit
Fellowes PB500 electric punch plastic comb 7.75k
Hewlette Parkard Laser 6.98k

The product with the highest profit in India include:

Sharp wireless fax digital  with a 2.89k profit
Hp copy machine color 2.86k
Samsung smart phone 2.67k

#### Analysis of the 3 subcategories with the highest average shipping cost in the United States.

! [] ()

The three sub categories include:
Copiers with average shipping cost being 165.28k
Machines with average shipping cost being 132.24k
Tables with average shipping cost being 69.95k


#### Analysis of the average profit of all African countries in 2014
! [] ()
The country with the highest average profit is South Africa with an average profit of 9,363.24k

The country with the least average profit is Nigeria with an average profit of -23,285.19k

#### Analysis of factors which might be responsible for Nigeria’s poor performance

! [] () 
Nigeria had an average shipping cost of 7k and an average discount of 1%

#### Analysis of sub-categories in Southeast asian countries
![] ()
The least profitable sub-category are tables. 
The country where Global superstore should stop selling this category is Indonesia

#### Analysis of the least profitable city (in terms of average profit) in the United States
![]()

The least profitable city in the United states is Lancaster with an average profit of -157.37k and a total of 46 orders

#### Analysis of the  product subcategory with the highest average profit in Australia?

! [] ()

The most profitable sub-category are appliances with an average profit of 139.01K

#### Analysis of the most valuable customers
! [] ()

There are 10 most valuable customers in order of average sales


