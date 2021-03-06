# Bike-Sharing-Demand-Prediction
 

## Problem defination:

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## Data Description:

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
## Attribute Information:

* Date : year-month-day
* Rented Bike count - Count of bikes rented at each hour
* Hour - Hour of he day
* Temperature-Temperature in Celsius
* Humidity - %
* Windspeed - m/s
* Visibility - 10m
* Dew point temperature - Celsius
* Solar radiation - MJ/m2
* Rainfall - mm
* Snowfall - cm
* Seasons - Winter, Spring, Summer, Autumn
* Holiday - Holiday/No holiday
* Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)
# Approach and Presentation.

Final Notebook- https://github.com/satyam-jyoti-sankar/Bike-Sharing-Demand-Prediction-/blob/main/Bike_Sharing_Demand_Prediction_Capstone_Project.ipynb

Presentation -  https://github.com/satyam-jyoti-sankar/Bike-Sharing-Demand-Prediction-/blob/main/bike%20sharing%20demand%20prediction.pptx

# Important Works/ Conclusion

Developed a regression model using algorithms such as Linear Regression, Random Forest and
GRADIENT BOOSTED REGRESSOR to predict the hourly demand of bikes and reduced the public waiting time .

Used different visual techniques to understood the impact of features such as time of the day, weather condition, holidays and engineered important features for the model.

Bike rental count is mostly correlated with the time of the day as it is peak at 10 am morning and 8 pm at evening.

We observed that bike rental count is high during working days than non working day.


In feature selection combine highly corelated features and makes them a single feature. Experimented with hyperparameter tuning techniques in Gradient boosting and Random forest achieved highest R2 score of 89% in both.

