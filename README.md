# Rossmann sales prediction model
This is a machine learning project for predicting drugstore chain sales.

![cover](https://github.com/GabrielAlvesDS/DataScience_em_Producao/blob/main/img/business_image2.png)

## Business Question
Rossmann Drug Stores' CFO asked for a sales forecast for each store over the next six weeks in order to set a budget for store renovations. To obtain results with a higher level of precision, we created a machine learning model and made it available for consultation through a telegram bot.

## Introducing the dataset
The dataset provides historical (daily) data on sales made by the 1,115 stores over 2 years and 7 months, and other information such as:
- Total sale in that day
- Number of consumers
- Whether the store was open or closed
- If it was a holiday (Christmas, Easter or Public Holiday)
- If it was a school holiday
- Type of store
- Level of product variety
- Distance to nearest competitor
- Closest competitor opening date
- If the store was on sale on the day
- If the store participated in the 2nd promotion
- Date on which the store started participating in the 2nd promotion
- Consecutive intervals (months) in which the 2nd promotion started


## Data Analysis

The correlation between attributes was analyzed in order to better understand which variables explain Rossmann's sales phenomenon. Below are some of the most relevant analyses:


- Multivariate analysis: Numerical Attributes

![eda-1](https://github.com/GabrielAlvesDS/DataScience_em_Producao/blob/main/img/heatmap.PNG)

- Multivariate analysis: Categorical Attributes


![eda-2](https://github.com/GabrielAlvesDS/DataScience_em_Producao/blob/main/img/eda_categorical_map.PNG)


## Tested machine learning algorithms

1. Linear Regression Model
2. Linear Regression Regularized Model - Lasso
3. Random Forest Regressor
4. XGBoost Regressor

## Selecting the algorithm with the best performance
Although Random Forest Regressor presented better results, XGBoost was chosen due to its processing efficiency.

![ml-table](https://github.com/GabrielAlvesDS/DataScience_em_Producao/blob/main/img/ml_table_of_results2.PNG)


## Hyperparameter Fine Tuning
In order to find the best parameters for the model, we were able to reduce the RMSE by 59%, reaching 1031.

![xgboost-result](https://github.com/GabrielAlvesDS/DataScience_em_Producao/blob/main/img/xgboost-final-result2.PNG)


## Model outputs
- Stores predictions 

![ml-output](https://github.com/GabrielAlvesDS/DataScience_em_Producao/blob/main/img/model-output2.PNG)

- Total Performance

![ml-output](https://github.com/GabrielAlvesDS/DataScience_em_Producao/blob/main/img/model-final-performance2.PNG)

## Access to predictions
- Contact the telegram bot and request the store sales prediction as shown in the figure below



