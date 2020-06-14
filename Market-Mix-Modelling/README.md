# Questions to ask before starting?

Why do we need econometric techniques like OLS, multivariate time series models to estimate a marketing ROI?

Why can‘t we be simply estimate the ROI, which can be calculated as the ratio of income to the investment or expenditure?

The answer to the above questions is simple and straightforward: 

each brand has a different characteristic, tastes, and so different market and cost structure. Thus the marketing efforts of each brand are not homogeneous; it depends on different kind of promotions and advertising.
It is very useful to separate and decompose the effect of marketing effort. 
The purpose of econometric modelling is to create response curves for each type of marketing spend and then use them to calibrate an optimization model to determine a more optimal marketing mix.




A) This is on a simple and fabricated dataset which doesn't cover all the complexity of MMM 
===========================================================================================

# Problem Statement/Use Case:
1) Identify the key levers affecting the sales paramater
2) By how much tweak at every Advertisement endpoint can be increase the sales
3) Budget Optimization

Data Understanding
==================

1) Spend on TV advertisement
2) Spend of Radio Ads
3) Spend on Ads in newspaper
4) The response variable- Sales



          
B) MMM for an ecommerce firm ( this will account for most of the possible complexities handled during MMM)
============================

ElecKart is an e-commerce firm based out of Ontario, Canada specialising in electronic products. Over the last one year, they had spent a significant amount of money on marketing. Occasionally, they had also offered big-ticket promotions (similar to the Big Billion Day). They are about to create a marketing budget for the next year, which includes spending on commercials, online campaigns, and pricing & promotion strategies. The CFO feels that the money spent over the last 12 months on marketing was not sufficiently impactful, and, that they can either cut on the budget or reallocate it optimally across marketing levers to improve the revenue response.

Imagine that you are a part of the marketing team working on budget optimisation. You need to develop a market mix model to observe the actual impact of different marketing variables over the last year. Using your understanding of the model, you have to recommend the optimal budget allocation for different marketing levers for the next year.

 
Data Understanding
==================

You have to use the data from July 2015 to June 2016. The data consists of the following types of information:

 

Order level data

FSN ID: The unique identification of each SKU

Order Date: Date on which the order was placed

Order ID: The unique identification number of each order

Order item ID: Suppose you order 2 different products under the same order, it generates 2 different order Item IDs under the same order ID; orders are tracked by the Order Item ID.

GMV: Gross Merchandise Value or Revenue

Units: Number of units of the specific product sold

Order payment type: How the order was paid – prepaid or cash on delivery

SLA: Number of days it typically takes to deliver the product

Cust id: Unique identification of a customer

Product MRP: Maximum retail price of the product

Product procurement SLA: Time typically taken to procure the product

Apart from this, the following information is also available:

Monthly spend on various advertising channels

Days when there was any special sale

Monthly NPS score – this may work as a proxy to ‘voice of the customer’

Stock Index of the company on a monthly basis 


 # working files on (B) will hit the git in sometime.


