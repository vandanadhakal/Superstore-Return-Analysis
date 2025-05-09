# Superstore Return Analysis
Tableau: Worksheets, Dashboard, Story

## Objective
To help the CEO of Superstore understand the root causes of high rate of returns on orders and how to reduce the volume of returned orders.

## Executive Summary
Superstore Data Analysis is carried out to understand the root cause of customers returns. Analysis shows the following:
Multiple reasons are causing customers to return products. Here are the causes:
> Certain months of a year, high returns during February, August, September, October, December
> 
> Delivery method like Same Day (44.6%) and First Class (30.0%) has high return rate but low sales
> 
> West Region and their States like Utah, California etc, have high return rate
> 
> For most of the months, higher the discount (total count) provided, higher the returns
> 
> Sub-categories like Machines and Fasteners have higher return rates (>30%) than others


## Project Description 
Online store Superstore is loosing lots of money through customers returns. The business wants to understand what is causing the returns across products. Do sales always correlate positively with returns? Is Rate of Return always the best approach to analyze data? What does the customers buying and returning behavior tell? What further steps can the business do curb the returns? This project tries to answer these questions through data analysis and visualization with the aim to help Superstore make informed data-driven decision.

The Tableau project can be found <a href='https://public.tableau.com/app/profile/vandana.dhakal/viz/SuperstoreReturnAnalysis_17431936226380/SuperstoreStory'><u>here</u></a>

Raw data file can be found <a href='https://github.com/vandanadhakal/Superstore-Return-Analysis/blob/main/Superstore.xls'><u>here</u></a>


## Methodology
The data was processed using Tableau. Spreadsheets, Dashboards and Stories were created to analyze the data. Various fields were analyzed to see how they affected the return rates. Geographic region, states and delivery method were analyzed together to understand return concentration areas. Customers return rates and number of orders/returns were analyzed to understand the pattern of buying and returning. An analysis of how should return be measured i.e Return Rate (%), Cost of Returns ($) or Total Count of Returns (Count) and their applicability is also assessed.

## Root Causes
It was determined through visualization and analysis that the following criteria affected the return rates:

**1. Month of the year:**
Certain months of a year like `February`, `August`, `September`, `October` and `December` have return rates that are upward of 25%. The total number of discounts provided to customers during these months are relatively higher than other months except in February. Thus, these months are prone to higher return rates.

**2. Region/State:**
Some geographical regions have higher return rates than others. `West` and `East` region has the highest and second highest return rates in the country. `Utah`, `California` and `Oregon`, all West region states, have the 3 highest return rates in the country.

**3. Ship Mode:**
`Same Day` ship-mode has the highest return rate than other modes. `First Class` ship-mode has second highest return rate.

**4. Discount:**
There is a strong correlation between discount (total count) and the return rate with respect to months of the year.

**5. Sub-category:**
Some sub-categories have higher rate of returns than others. `Machines` and `Fasteners` have a high rate of return (>30%), while Envelopes have the least at 17.2%.

**6. Category:**
From the 3 categories (Technology, Office Supplies and Furniture), Technology has the highest return rate. But the return rate across all 3 categories is similar. Thus, this criterion is not a significant root cause of returns.

[Video Demonstration for Geography Dashboard](https://www.youtube.com/watch?v=fxmY5O-TfiA)

[Video Demonstration for Multiple Root Cause Dashboard](https://www.youtube.com/watch?v=T-9-UZF3S3w)


<img src='https://github.com/vandanadhakal/Superstore-Return-Analysis/blob/main/Root%20Causes.png'>


## How to Target Root Causes

**Changes on Return Policies**
Limiting free returns 
Charging for excess return costs

**Optimizing Delivery Methods**
Incentivizing Standard Class customers by discount/coupons
Increasing subscription fee and limiting number of free returns

**Enhancing Product Quality**
Quality checks before shipment
Asking for customers input on quality of products
Involving vendors to meet quality standard if necessary

**Further Analyze Subcategories including Sales, Return, Profit and Cost of Returns**

**Improving Customers Engagement** 
Request for sincere feedbacks on products/returns
Sending personalized emails to summarize return history

**Mix Approach to Discount and Months**
Boosting sales during low demand month by providing discounts/coupons 
Limiting free returns count during peak sales months


<img src="https://github.com/vandanadhakal/Superstore-Return-Analysis/blob/main/Proposed%20Steps.png"> 

## Limitation
1. The data doesn't include returns in the Sales and Profit data. Customers Hilary Holden and Roland Murray have 100% return rates. The total sales and total profit of these customers are positive, which can’t be true when all that were bought were returned. 
2. Cost of returns isn't taken into account in the data. Thus, the profit/sales provided is not representative of the actual profit/sales of the company including all the costs.
## Assumptions
1. The ship-mode have subscription service with Same Day having the highest price per subscription. First class and second class having 2nd and 3rd highest subscription price respectively.
2. Standard Class has no subscription fee.

## Conclusion
1. Superstore is bleeding money on customers returns
2. Returns are eating their profit and sales revenue
3. They need to proactively look for approaches to reduce product returns
4. They need to make sure they have high quality products to make customers return to their websites to buy products not return them

