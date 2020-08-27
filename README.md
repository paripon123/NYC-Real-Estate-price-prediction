# NYC-Real-Estate-Price-prediction

#### Overview
In this project, the goal is to implement a model for predicting the price of real estate in New York City by apply multiple machine learning methods and discovery of an insight information of real estate market trend to predict sale value in the future.

#### About The Dataset
  - The data set using in this project is NYC Property Sales from Kaggle.com [https://www.kaggle.com/new-york-city/nyc-property-sales]
  
  - This dataset contains the location, address, type, sale price, and sale date of building units sold. A reference on the trickier fields:

     - BOROUGH: A digit code for the borough the property is located in; in order these are Manhattan (1), Bronx (2), Brooklyn (3), Queens (4), and Staten Island (5).
     - BLOCK; LOT: The combination of borough, block, and lot forms a unique key for property in New York City. Commonly called a BBL.
     - BUILDING CLASS AT PRESENT and BUILDING CLASS AT TIME OF SALE: The type of building at various points in time. See the glossary linked to below.
        
     :For further reference on individual fields see the Glossary of Terms. For the building classification codes see the Building Classifications Glossary.
     
     :Note that because this is a financial transaction dataset, there are some points that need to be kept in mind:

     - Many sales occur with a nonsensically small dollar amount: $0 most commonly. These sales are actually transfers of deeds between parties: for example, parents transferring ownership to their home to a child after moving out for retirement.
     - This dataset uses the financial definition of a building/building unit, for tax purposes. In case a single entity owns the building in question, a sale covers the value of the entire building. In case a building is owned piecemeal by its residents (a condominium), a sale refers to a single apartment (or group of apartments) owned by some individual.
     
![Alt text](https://github.com/paripon123/NYC-Real-Estate-price-prediction/blob/master/Distribution%20of%20Price%20In%20US%20Dollars.png 'Distribution Of Real Estae sale values')
     
#### Conclusion

Three machine learning regression methods (Linear Regression, Decision Tree Regressor and Random Forest Regressor) were trained. As a result, we have achieved the Random Forest Regression with Cross Validation following by Decision Tree Regressor and Linear Regression.

The best prediction performance from the test set was achieved with Random Forest Regressor, with selected features and the result is the in the following evaluation matric:
  - Root Mean Square Error (RMSE) : 428808.53
  - R- squared : 0.67
