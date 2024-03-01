## Bank Customer Acquisition Analysis for a Term Deposit Product

An anonyms company had conducted a telemarketing campaign. Through the campaign, the company had collected data about the prospects' demographics : The channel through which the customer was gained, its cost, conversion rate and total revenue it generated in return. 

The company’s marketing team wants to launch yet another telemarketing campaign for the same product. As an analyst at the company, we want to answer the following questions using the past data:

- Which channels are more likely to influence the prospectus ?
- What is total customer acquisition cost and its distribution across different channels?
- which channel is most and least effective at converting customers?
- which channel is least and most profitable in terms of return on investment?

## Problem and Business Objective

- To reduce customer acquisition cost by selecting the most efficient channel for marketing.
- To improve the conversion rate, i.e., the fraction of prospects who respond to the campaign

## Data

- ***Campaign data:***  Customer ID, channel, cost, conversion rate, revenue, etc.


## Tasks

To solve the problem, we should build a model to determine total cost of acquisition and also channel wise distribution of it along with total revenue generated from it. 

Based on this information, we need to plot bar charts defining the channels with highest Return on investment.

## Checkpoints

The checkpoints for the assignment are as follows:

1. Perform data preparation and EDA.

2. Create a data frame with the variables channels and cost and group it by channels to determine channel wise distribution of cost of acquisition.

3. Create a data frame with the variables channels and conversion rate and group it by channels to determine channel wise distribution of conversion rate.

4. Create a data frame with the variables channels and revenue and group it by channels to determine channel wise distribution of revenue.

5. define an attribute  ‘Return on Investment’ as revenue/cost and group it by channel to determine ROI according to channel

6. Plot charts of each data frame created using python libraries to visualise the insights.
