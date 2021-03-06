# AirbnbBoston
## Introduction

This GitHub repository has the code related to a Medium article that you can find [here](https://fran-alliende.medium.com/boston-airbnbs-data-analysis-6d9971dfdf2).

The objective of this work is to analyze the data from Boston Airbnb, available on this [link](https://www.kaggle.com/airbnb/boston), and answer the following questions:

1. Which are the most expensive neighbourhoods in Boston?
2. Is it possible to create clusters of the Boston Airbnb’s?
3. What are the factors that influence the price of Boston Airbnb?

## File descriptions

### [Select relevant information and basic data-cleaning](https://github.com/FranciscaAlliende/AirbnbBoston/blob/main/1%20Select%20relevant%20information%20and%20basic%20data-cleaning.ipynb)

- Selection of relevant features.
- Elimination of unpleasant characters and correction of data types.
- Change in the host_since column, from the date to the days that have passed since the host signed up on Airbnb.
- Cleaning the feature amenities and creating binary variables, where a column corresponds to an amenity. 

### [Data Understanding](https://github.com/FranciscaAlliende/AirbnbBoston/blob/main/2%20Data%20Understanding.ipynb)

- Histograms of the price and the price per accommodate.
- Percentage of null values in numerical and categorical features.
- Histograms of numerical features.
- Number of data points per category in categorical features.
- Percentage of properties that offer each amenity. 

### [Data Preparation](https://github.com/FranciscaAlliende/AirbnbBoston/blob/main/3%20Data%20Preparation.ipynb)

- Creation of the variable price for accommodation.
- Elimination of variables with more than 95% of null values.
- Filling in the null values with the median in numerical characteristics.
- Filling in the null values with the mode in categorical characteristics.
- Creation of dummy variables for all categorical characteristics.
- Detection and elimination of outliers with Isolation Forest.

### [Which are the most expensive neighborhoods in Boston?](https://github.com/FranciscaAlliende/AirbnbBoston/blob/main/4%20Which%20are%20the%20most%20expensive%20neighborhoods%20in%20Boston.ipynb)

- Aggregates of the variable price per accommodate per neighborhood.
- Histograms of price per accommodate per neighborhood. 
- Boxplot price per accommodate by neighborhood sorted by the mean. 

### [Is it possible to create clusters of the Boston Airbnb’s?](https://github.com/FranciscaAlliende/AirbnbBoston/blob/main/5%20Is%20it%20possible%20to%20create%20clusters%20of%20the%20Boston%20Airbnb%E2%80%99s.ipynb)

- k-means implementation:
  - Normalize numerical variables.
  - Elbow method.
  - Fit and predict.
- Analysis of the results:
  - Boxplot numerical variables, by cluster.
  - Plots of the categorical variables by category and cluster.
  - Plots of the amenities by category and cluster.  
 
### [What are the factors that influence the price of Boston Airbnb?](https://github.com/FranciscaAlliende/AirbnbBoston/blob/main/6%20What%20are%20the%20factors%20that%20influence%20the%20price%20of%20Boston%20Airbnb.ipynb)

- Implementation of Random Forest.
- Evaluation utilizing RMSE.
- Plot of true and predicted values.
- Repetition for price per accommodate < 200.
- Plot of the 20 most important features of the model. 











