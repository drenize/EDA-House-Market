# EDA-Project-1-House-Prices

This notebook is about predicting house prices in King County, Washington in the context of a data science bootcamp. The project journey goes through all stages of the data science cycle from business understanding, over data cleaning, to delivering predictions. Furthermore, a train-validation-test is implemented as well a multicollinearity check. 

The project aims at comparing real estate object of mansion sized

![Kind County, Washington](https://48h57c2l31ua3c3fmq1ne58b-wpengine.netdna-ssl.com/wp-content/uploads/2018/05/Bellevue-and-Cascades-King-County.jpeg)
King County, WA/USA


## Data Science Life Cycle
- Business Understanding
- Data Mining
- Data Cleaning
- Data Exploration
- Feature Engineering
- Predictive Modeling
- Data Visualisation

## Data Cleaning
Missing values occured in three categorical variables for which an imputation by mode has been applied. 
- **waterfront**: 11% missing values
- **view**: 0.3% missing values
- **yr_renovated**: 17.8% missing values

## Data Engineering
Two variables, previously stored as object data types, were converted to an adequate data type
- **sqft_basement**: numerical, int
- **date**: from string to datetime

Date was split into a month and a year variable to explore price variations over time. 
A variable 'sqft_total_property' was created as the sum of 'sqft_living' and 'sqft_lot'.

## Model Choice
Linear regression modeling is explored for prices. Features were chosen through an algorithm by significance.

## Results and Recommendations
- 

## Future Work
- improve the linear model by reducing features
- compare price segments
- search for underrated objects
- explore multicollinearity
