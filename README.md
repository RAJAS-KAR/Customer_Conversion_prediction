# Item-Demand-Forecasting
# problem Statement:
                 Demand forecasts are fundamental to plan and deliver products and services. Accurate forecasting of demand can help the manufacturers to maintain appropriate stock which results in reduction in loss due to product not being sold and also reduces the opportunity cost (i.e. higher demand but less availability => opportunity lost). Despite such relevance, manufacturers have difficulty choosing which forecast model is the best for their use case. In this project, historical sales data corresponding to multiple(25) items sold in 10 stores are provided and participants are expected to come up with a best model to predict the future demand for products which results in maximum profit for the manufacturer.Predict the demand for the next 3 months at the item level (i.e. all the stores combined).
                 
# solution :
           The goal is to predict the next 3 month Sales on item level from a particular Date. So I found the rolling sum for a window 90 days and predicted the Sales.In Model Building I used Decision tree Regressor, Random Forest Regressor, Linear Regression, XG Boost, KNN Regresoor are used. In that XG Boost performed well Compared to other model.
  
# STEPS NEED TO BE FOLLOWED:

1.Import the required package
2.Import the dataset(Time series data)
3.clean the data(convert date into datetime)
4.groupby sales on item level
5.found the rolling sum for a window 90 days
6.Done some EDA(exploratort data anlysis) to understand the distribution of the data
7.Feature Engineering (extract featrue from date )
8.Fitting all REGRESSOR model to predict the next 3 month Sales on item level from a particular Date.
9.Use evaluation metric score to findout the best model(R2_score)
