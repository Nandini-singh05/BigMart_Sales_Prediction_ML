# BigMart Sales Prediction using Linear Regression and Random Forest Algorithms

---

## Problem Statement

The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store. Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

--- 
## Data Dictionary 
Dataset : https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data

* Item_Identifier : Unique product ID

* Item_Weight : Weight of product

* Item_Fat_Content : Whether the product is low fat or not

* Item_Visibility : The % of total display area of all products in a store allocated to the particular product

* Item_Type : The category to which the product belongs

* Item_MRP : Maximum Retail Price (list price) of the product

* Outlet_Identifier : Unique store ID

* Outlet_Establishment_Year : The year in which store was established

* Outlet_Size : The size of the store in terms of ground area covered

* Outlet_Location_Type : The type of city in which the store is located

* Outlet_Type : Whether the outlet is just a grocery store or some sort of supermarket

* Item_Outlet_Sales : Sales of the product in the particular store.

---

## Steps Involved 
1. Importing required Libraries & Dataset

2. Data Cleaning using Pandas and KLib

3. Feature Selection & Memory Reduction 

4. EDA using Pandas Profiling & KLib

5. Data Preprocessing & Label Encoding (One Hot Encoding)

6. Splitting Data into Train and Test

7. Standardization

8. Model Building using Linear Regression & Random Forest

9. Hyper Parameter Tuning

10. Saving the Model


## Conclusion 
* Item_MRP clearly maximises the Outlet sales.
* Outlet Type being SuperMarket or Grocery Store also depicts the Outlet Sales.
* Years Established will also tend to have loyal customers and that's how the sales margin can be acheived.
---

## Application of Predicting Sales
We can tell the company what are all the challenges they may face, what are the brands or products which is sold the most & other such kind of things. This helps sales team to understand which product to sell & which product to promote & other such kind of things. They can also make several marketing plans(let's say that a particular product in a particular store is getting sold the most & we may find some insights from it - as of why this product is getting sold the most & this helps the company to make better marketing decisions)


