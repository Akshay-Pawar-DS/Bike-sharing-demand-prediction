# Bike-sharing-demand-prediction

![image](https://user-images.githubusercontent.com/103834221/209555634-713131e3-af0c-4495-be7b-9e532848a277.png)

## Indroduction:

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## Dataset :

➢ Date :Year-Month-Day

➢ Rented Bike Count -Count of bikes rented at eachhour

➢ Hour -Hour of the day

➢ Temperature -Temperature in Celsius

➢ Humidity -%

➢ Wind Speed -m/s

➢ Visibility -10m

➢ Dew point temperature-Celsius

➢ Solar radiation -MJ/m2

➢ Rainfall -mm

➢ Snowfall -cm

➢ Seasons -Winter, Spring, Summer,Autumn

➢ Holiday -Holiday/No Holiday

➢ Functional Day -NoFunc(Non Functional Hrs),Fun(FunctionalHrs)

## Approach :

During the time of our analysis, we initially did EDA on all the features of our datset. We first analysed our dependent variable, 'Rented Bike Count' and also transformed it. Next we analysed categorical variable and dropped the variable who had majority of one class, we also analysed numerical variable, found out the correlation, distribution and their relationship with the dependent variable. We also removed some numerical features who had mostly 0 values and hot encoded the categorical variables.

Next we implemented 7 machine learning algorithms- 

### Model Training

#### LINEAR REGRESSION
#### LASSO REGRESSION
#### RIDGE REGRESSION
#### ELASTIC NET REGRESSION
#### DECISION TREE
#### RANDOM FOREST
#### GRADIENT BOOSTING
#### Gradient Boosting Regressor with GridSearchCV


### CONCLUSION:
- No overfitting is seen.

- Random forest Regressor and Gradient Boosting gridsearchcv gives the highest R2 score of 99% and 95% recpectively for Train Set and 92% for Test set.

- Feature Importance value for Random Forest and Gradient Boost are different.

- We can deploy this model.

- However, this is not the ultimate end. As this data is time dependent, the values for variables like temperature, windspeed, solar radiation etc., will not always be consistent. Therefore, there will be scenarios where the model might not perform well. As Machine learning is an exponentially evolving field, we will have to be prepared for all contingencies and also keep checking our model from time to time. Therefore, having a quality knowledge and keeping pace with the ever evolving ML field would surely help one to stay a step ahead in future.

