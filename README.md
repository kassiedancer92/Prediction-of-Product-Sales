# Prediction of Product Sales

### Business problem:
This anaylsis is trying to understand what is the best predictor of sale s

### Data:

This data set contains 12 columns and 8523 row. 

<img width="788" alt="Screenshot 2023-07-06 at 11 04 51 PM" src="https://github.com/kassiedancer92/Prediction-of-Product-Sales/assets/133593433/ee45b8f8-321f-4bb2-95d9-b0e8c8f134f3">


### Exploritory Analysis

The correlations of the data set is seen below:

![image](https://github.com/kassiedancer92/Prediction-of-Product-Sales/assets/133593433/8a5a9e73-c9ff-4046-acd1-1fc88f8b9de6)

The strongest correlation with item sales is item MRP.


Countplot of item type:

![image](https://github.com/kassiedancer92/Prediction-of-Product-Sales/assets/133593433/2ba47c30-fe6e-496c-bb93-f4fe816b3d3b)

The highest number of sales is fruits and vegtables and the second highest is snack foods. The lowest product sales is seafood.

### Model

Tuned Forrest:

<img width="498" alt="Screenshot 2023-07-06 at 11 09 23 PM" src="https://github.com/kassiedancer92/Prediction-of-Product-Sales/assets/133593433/45b93c1b-1adf-4c2e-b355-3a748f331e7e">

This models goodness of fit is 59%. Only 59% of the varaince in the data can be explained by this model. RMSE shows the difference between the predctied and actual values. This model is off by ~$1,000


### Recommendations:
More exploriation should be considered to try to increase the R^2
