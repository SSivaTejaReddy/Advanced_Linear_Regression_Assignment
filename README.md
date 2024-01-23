# Advance-ridge-lasso-regression
Building an Advance Linear Regression Model with Ridge/Lasso for Housing Dataset

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.The company wants to know:
- Which variables are significant in predicting the price of a house?
- How well those variables describe the price of a house.
Dataset provided is train.csv

## Conclusions
### Feature which holds significance in contributing towards buying the house are as follows:

-  OverallQual 	  0.2208
-  GrLivArea	  0.1854
-  OverallCond    0.1136
-  GarageArea	  0.0909
-  MSZoning_RL    0.0863
-  1stFlrSF       0.0759
-  MSZoning_RH    0.0739
-  MSZoning_FV 	  0.0689
-  LotArea     	  0.0643
-  FullBath       0.0603

## Final model prediction (Test)
   
Mean Square Error (MSE) Ridge 0.0021919	
Mean Square Error (MSE) Lasso 0.0021283


## Python Libraries Used
- Pandas 
- Matplotlib 
- Seaborn 
- Numpy
- Sklearn  



## Contact
Created by Siva Teja Reddy Sirigireddy


Developed as part of the Advanced Regression Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.