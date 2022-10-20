[![Language](https://img.shields.io/badge/language-python-blue.svg?style=flat)](https://www.python.org)

# DA_Submission02

## Times Series Analysis : Big pharma Stock Demand forcast


### Probleme Description
Big Pharma is a large pharmaceutical distribution company in Germany. They restock their warehouses monthly but have been running into issues with `overstocking and under-stocking products`. You were employed as a data scientist to help find a solution to this problem. The sales team has provided you with data to get started on implementing your solution.

### Metadata
1.	Date: The date a product was purchased
2.	Product ID: The ID for the product
3.	Stock Demand: The quantity of product purchased (unit is in boxes)

### Objectif
The data provided includes product demand from October 2020 to October 2021. Forecast the quantity of products the company should purchase for their warehouses in the coming month. 

### Evaluation
1.	What evaluation metric would you recommend for your model and why?
2.	How would you build a machine learning pipeline for your model?
3.	How would you measure the impact your model has on the company’s operations?

NB: Be free to make your own reasonable assumptions. Please state any assumptions that you make.


### Code

[01 - Big Pharma Stock Demand](Big_Pharma_Stock_Demand.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AbdelTID/DA_Submission02/HEAD).


**Questions**

1.  What evaluation metric would you recommend for your model and why?

 > For the evaluation metric we will use the `mean absolute error` . In statistics, an error is the difference between a measurement and reality. There may not be any difference at all, but there's usually something not quite right, and we need to account for that in our model.

>Absolute error is the error in a single measurement, and mean absolute error is the average error over the course of several measurements.

>Every model come with some marge error . So all prediction will be bond by (y_predict $\pm$ mae) 

>The mean absolute error is a common measure of forecast error in time series analysis



2.  How would you build a machine learning pipeline for your model? 
> The pipeline, from data  pre processing,  modelling, training and forecast is in the notebook above.

3.  How would you measure the impact your model has on the company’s
    operations? Impact of this model on the company operations could be
    measured by:
    
> Some of the loss causing by overstocking and understocking compare to previous years and our previsions 
