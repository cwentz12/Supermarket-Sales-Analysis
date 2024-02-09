# Supermarket Sales Data: Exploratory Data Analysis Project

## Overview

A supermarket chain is looking to expand their business. The company leadership team has provided the data team with historical supermarket sales data. Leadership is interested in finding answers to several questions:

1) What is the average purchase total of a customer's cart?
2) What was the average overall customer rating?
3) How do customer ratings compare at each of our 3 branch locations?
4) Which branch location is most profitable?
5) Do members tend to spend more money than non-members?
6) What is our best selling product line?
7) How do sales fluctuate during the week? Which day of the week is most profitable?

## Dataset 

The dataset is a public Kaggle dataset concerning supermarket sales data in Malaysia from January 1st, 2019 to March 30th, 2019.

The dataset is included as a CSV file in this repository and can also be found at https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales/


![Sales and Ratings](https://github.com/cwentz12/Exploratory-Data-Analysis/assets/115527862/2acc6b43-a351-4229-add6-f3906fc2482c)


The dataset can be used to answer a number of useful questions about customer ratings, most profitable branch locations, most profitable product lines, and most profitable days of the week. 

One limitation of the data is that the "cogs" (cost of goods sold) column is actually the pre-tax total for the customer instead of the expected cost paid by the supermarket to obtain goods. The "gross income" and "gross margin percentage" columns have calculations based upon the "cogs" column. I excluded these columns from my analysis, as noted in the notebook section on data cleaning. 

Another limitation of the data is that the sales were captured during a relatively short timeframe. A longer timeframe could have offered more information about sales fluctuations during holidays and the different seasons of the year. 

The dataset is also from 2019 and may not reflect current consumer trends.

## Conclusion

1) Customer ratings were evenly distributed between 4.0 to 10.0. The business should consider conducting customer surveys to determine which factors are negatively impacting the customer experience.

2) The overall best selling product line was "Food and Beverages". Customer surveys could be used along with customer segmentation analysis to continue to optimize product line offerings. A better understanding of customer demographics can help offer items customers are more likely to buy.

3) Obtaining correct values for the cost of goods sold would allow for further analysis of profit margins across product lines.

4) Saturday had the highest total sales while Monday had the lowest total sales. The company can use this information along with other data with a longer timeframe to help optimize staffing. 
