# Ecommerce-Analysis
Data Analysis with Python and visualization with Tableau for an E-commerce Store

# Ecommerce - Data Analysis:


![image](https://github.com/mtchagoue/Retail-data-analysis/assets/115325778/f0b551ce-1224-4033-8ccd-2aafdc22ebd5)


## **Introduction:**
Selling online is amazing. It offers great opportunities to reach clients worldwide. This particular company has been selling online for the past 3 years and they have gathered many data. Our role here is to analyze the data to have some insights. 
## **Problem Statement:**
We will use Python pandas to analyze and answer few questions related to these sales data. Few of the questions we will be answering:
-	What is the sales trend?
-	What are the top 10 products by sales
-	What are the most selling products
-	Preferred shipping method?
-	Most profitable category? Least profitable one?
	
Are you thinking about setting up your own online ecommerce?  We will show you how an analysis can be done.

## **Data sourcing:**
This is the link where we get the data .

Datalink from : https://github.com/EDSOfficial/Sales-Analysis.git

## Analysis and Visualization:

# Analysis:
Data are from January 2011 to December 2014.
Checking the sale trend shows the sales have been growing with the years. 
data_monthly_trend = data.groupby('month_year').sum()['sales'].reset_index(). Same with the quantity. Overall, Business is good.
Top products by sale are Cellphones. Apple Smart phone, Cisco Smart phone, Motorola, nokia.
And the least product by sale are : Disposable bags, Xerox, seal envelopes.
The next insight the most sold product is confusing with the most product by sale. For a better understanding, you have to understand that the products who bring the most money is because they are expensive and they are not the most sold by quantity.
Hence the most sold products by quantity after grouping will be most_sold.sort_values('quantity', ascending=False) : staples, cardinal Index tab, eldon cart, Rogers cart. 
Their clients’ preferred shipping method is Standard Class… the most profitable category is technology.
Their most profitable region is Canada with the least order


# visualization:


https://public.tableau.com/app/profile/archange.tchagoue1597/viz/WalmartDataAnalysis_17048273030200/WalmartRegionalSalesAnalysis?publish=yes


![image](https://github.com/mtchagoue/Retail-data-analysis/assets/115325778/10aef814-1a37-4cb7-bdc7-5e88aae7b8b5)


![image](https://github.com/mtchagoue/Retail-data-analysis/assets/115325778/f86460ed-f355-4105-97b1-7c9d4d5a26dd)

 











