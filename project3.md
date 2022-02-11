
## Abstract

The goal of this project is to use a clustering model to determine customer segments and achieve higher profit margins. I worked with supermarket data from Kaggle in order to help my client, Trader Joe's, better understand their customers so they know what products to sell and when to anticpate busy/slow periods in order to increase their profits. After refining a model, I built an interactive dashboard to visualize and communicate my results using Tableau. 

## Design

The market size of the supermarket/grocery store industry in the US has grown 2.7% per year on average between 2017 and 2022. This steady increase implies that competition has risen as well. A single supermarket chain can see upwards of 3500 customers per day and a typical American visits the supermarket 1.6 times per week. 

My target client is Trader Joe's, a large supermarket chain with over 500 lcations in the US and annual sales estimated to be nearly $14 billion. The growth of supermarkets in cities is increasing, along with market competition, and supermarkets must establish clear points of differentiation in order to survive and keep profit margins high.

The desired impact of this project is to help Trader Joe's improve profits by using customer & product segmentation to identify areas of improvement. My impact hypothesis is that doubling down on selling best-selling products will help drive revenue, and thus there should be a designated 'best-sellers' shelf so customers can easily find their favorite goods.

I explored Kaggle and found a dataset on supermarket sales, which I used in order to optimize for profits. I analyzed various features: Customer type, Gender, Product line, Unit price, Quantity, Tax, Total price, Payment type, Cost of goods sold, Gross margin percentage, Gross income, and Customer Rating. 

There are two solution paths, with one being more robust than the other. The simpler solution path is to use EDA to identify features that either contribute or take away from potential profits. The more robust solution path utilizes a clustering model to segment customers and products and maximize the value of each customer to the business. 

In the short term, this project is deemed a success if profits increase due to more attention and care to a certain customer segment (ie: families, college students, singles). In the long term, success would look like an overall increase in profits when efforts are applied to each segment. 


## Data

Kaggle: https://www.kaggle.com/aungpyaeap/supermarket-sales

## Algorithms & Analysis

I started off by looking at my data in Google Sheets and performed data cleaning and exploratory data analysis to narrow down the key features for subsequent visualization. I used Python packages (matplotlib and seaborn) to create basic charts and exported a cleaned up csv into Tableau for more advanced visualizations to address my client's problems.

I initially looked at the breakdown of features related to customers, namely gender (male/female) and customer type (member/non-member). After preliminary EDA, it was evident that these segments had little to no influence on product purchases or supermarket gross imcome.

Looking at the days of the week, it’s clear to see that Tuesdays and Saturdays are the busiest days of the week in terms of total income over thr 3 month period. An idea to increase profits is to have sales on certain items or offer senior discount on one of the slower days of the week. This will incentivize shoppers to come in and purchase more items.

In looking at product segments, I looked at quantity and gross income of product purchases. Fashion & food/beverage items are most purchased products, and food/beverage and sports/travel bring in the most revenue. An idea here is to increase prices for the most purchased items since they are so popular. Sports/travel products did not sell as much as other products, but they contributed significantly to the supermarket income. Health and beauty items generally contributed the least in terms of profit & purchased quantity. My recommendation is to pare down on health/beauty items and remove most from the storefront except for a few top-selling individual products.

The peak hour in average gross income is at 2 pm. Since the afternoon is quite busy, an option is to have more people on staff during this time.

The last chart depicts customer ratings per product line. The main conclusion from this chart is that people dont have strong feelings one way or another towards supermarket product categories. Food/ beverage has a slightly higher rating than the others, but it’s a stretch. 

## Tools
- Google Sheets
- Python 
- Matplotlib
- Seaborn
- Tableau

## Communication
My analysis will be presented in Google Slides using visualizations created with Tableau and Python. See GitHub repository for project files and code.
