# Project Name
Multiple Linear Regression - Bike Sharing Assignment


## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
It is required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
Dataset provided is day.csv

## Conclusions
 Significant variables to predict the demand of shared bikes:

  - temp
  - year
  - windspeed
  - summer
  - winter
  - saturday
  - september
  - snowy weather (Light Snow, Light Rain)
  - misty weather (Mist + Cloudy)

## Final model prediction
   
    Train dataset R squared : 0.835
    Test dataset R squared : 0.796
    Train dataset Adjusted R square : 0.832
    Test dataset Adjusted R square : 0.785


## EDA Analysis & observations
  
   - Fall season has the highest number of bookings
   - Year 2019 has more bookings than 2018
   - Demand is growing from June to September, after that there is a decrease in demand
   - Demand has increased on a holiday
   - When the weather is good and clear the demand is higher
   - Weekday is not giving much insight about the demand


## Python Libraries Used
- Pandas 
- Matplotlib 
- Seaborn 
- Numpy
- Statsmodel
- Sklearn



## Contact
Created by Soma Mukherjee


Developed as part of the Linear Regression Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore. -->