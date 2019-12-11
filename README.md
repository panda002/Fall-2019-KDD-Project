# Fall-2019-KDD-Project

## Project and Team Introduction
Team Name: Analytics Panda
<p>Sidharth Panda - Computer Science Graduate student at the University of North Carolina at Charlotte

## Data and Source description

This is a list of over 7,000 electronic products with pricing information across 10 unique fields provided by Datafiniti's Product Database. The dataset also includes the brand, category, merchant, name, source, and more.

Note:- This is a sample of a large dataset. The full dataset is available through Datafiniti.

Description of all the columns present in the dataset can be found in the link - https://developer.datafiniti.co/docs/product-data-schema

<p> *********************************************************************************************************************************

  
#### About Datafiniti
Datafiniti provides instant access to web data. We compile data from thousands of websites to create standardized databases of business, product, and property information.

<p> *********************************************************************************************************************************

Price Elasticity model

[Price elasticity of demand (PED or Ed)](https://en.wikipedia.org/wiki/Price_elasticity_of_demand) is a measure used in economics to show the responsiveness, or elasticity, of the quantity demanded of a good or service to a change in its price when nothing but the price changes. More precisely, it gives the percentage change in quantity demanded in response to a one percent change in price.

It gives answers to questions such as:
> “If the price of a product is lowered, how much more will be the demand?”<p>
> “If the price of a product is increased, how will that affect sales of the other products?”<p>
> “If the price is decreased, then how much should be the sale of the product to keep the revenue constant?”
 
The price change brings into effect two possibilities -

##### The price effect<p>
> For inelastic goods, an increase in unit price will tend to increase revenue, while a decrease in price will tend to decrease revenue. (The effect is reversed for elastic goods.)<p>
  
##### The quantity effect<p>
> An increase in unit price will tend to lead to fewer units sold, while a decrease in unit price will tend to lead to more units sold.

<p> *********************************************************************************************************************************
 
## [Elastic and Inelastic Demand](https://keydifferences.com/difference-between-elastic-and-inelastic-demand.html)
###
BASIS FOR COMPARISON|ELASTIC DEMAND |INELASTIC DEMAND
:---:|:-:|:---:
Meaning|When a little change in the price of a product results in a substantial change in the quantity demanded, it is known as elastic demand.|Inelastic demand refers to a change in the price of a good result in no or slight change in the quantity demanded.
Elasticity Quotient|More than equal to 1|Less than 1
Curve|Shallow|Steep
Price and Total revenue|Move in the opposite direction|Move in the same direction
Goods|Comfort and luxury|Necessity

<p> *********************************************************************************************************************************

## CRISP-DM Process
> File to be followed - PriceElasticity_price.ipynb
#### Data Understanding and EDA
  <p>We can infer from data which all products are price elastic and which aren't. If there are inelastic products i.e products whose        sales are not affected by change in price, we can get that extra revenue (left on table currently) by increasing price;
  
#### Normal EDA will include  the follwing points and may change with the project progress :-
 >  <p>How does the prices condition affect the pricing strategy of a product?
 >  <p>Is there a correlation between the prices.dateSeen of a product and its dynamic pricing across merchants?
 >  <p>What is the competitive pricing strategy for the same product from different merchants?
 >  <p>What role does a product’s category play in its listing price?
 >  <p>Price Elasticity of all the products
   
#### Data Preparation
  DWe have finished with the data preprocessing and we are ready to put the updated excel file in the Power BI tool.

#### Machine Learning
We have implemented Decision Tree and Random Forest Classifier to test the score of our classification model to classify the brands based on discount criteria and price matching criteria
#### Visualization and Buisness Insights
We will be creating some visualizations using Power BI tool from microsoft.

#### Using Power BI Tool
Power BI is a business analytics solution that lets you visualize your data and share insights across your organization, or embed them in your app or website. Connect to hundreds of data sources and bring your data to life with live dashboards and reports.(https://powerbi.microsoft.com/en-us/what-is-power-bi/)
