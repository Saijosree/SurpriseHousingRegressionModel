# Surprise Housing Regression Model
> To build a L1 and L2 Regession Models to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
- The company is looking at prospective properties to buy to enter the market.
- The company wants to know:
	Which variables are significant in predicting the price of a house, and
	How well those variables describe the price of a house.
- The company has collected a data set from the sale of houses in Australia.



## Conclusions
- Optimal values of alpha for ridge and lasso regression are 1.0 and 0.0001 respectively
- Top most predictors of Lasso
	RoofMatl_ClyTile                             	
	Condition2_PosN                
	PoolQC_Gd                            
	OverallQual_Excellent                     
	OverallQual_Very Excellent                 
	GrLivArea                               

- Five most predictors of Ridge
	Condition2_PosN                                   
	RoofMatl_ClyTile                          
	PoolQC_Gd                                     
	PoolQC_Ex                                               	
	1stFlrSF                                                
	GrLivArea   




## Technologies Used
- Numpy
- Pandas
- Seaborn
- Matplotlib
- sklearn

