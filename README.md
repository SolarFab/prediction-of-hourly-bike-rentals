
# Bike rental prediction project
The goal of this notebook is to demonstrate several different regression models to predict bike rentals. For this project the  kaggle "Bike Sharing Demand" data set was used : https://www.kaggle.com/competitions/bike-sharing-demand/overview. 

### Used Regression Models

In total several different regression models were used and optimized:
- linear regression
- lasso regression
- random forest regresson
- ridge regression
- poisson regression
The optimization of hyper parameters is just an example to demonstrate the workflow and possibilities. For final optimization more computing power would be needed.


The dataset contains hourly bike rental data for two years with the following data fields:

### Data fields

- datetime - hourly date + timestamp  
- season -  1 = spring, 2 = summer, 3 = fall, 4 = winter 
- holiday - whether the day is considered a holiday
- workingday - whether the day is neither a weekend nor holiday
- weather - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog 
- temp - temperature in Celsius
- atemp - "feels like" temperature in Celsius
- humidity - relative humidity
- windspeed - wind speed
- casual - number of non-registered user rentals initiated
- registered - number of registered user rentals initiated
- count - number of total rentals


### Workflow

- import the data
- exploratory data analysis
- feature engineering
- train different regression models
- hyperparameter optimization
    
