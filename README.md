# Bike-Sharing-Prediction-Linear-Regression-Model
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

### Business Goal:
The objecttive is to to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

### Conclusion:
We can see that the equation of our best fitted line developed by Model is:

$ Count = 0.1411 + ( 0.2331 * Year - 0.1014 * holiday + 0.5106 * temp - 0.1530 * windspeed + 0.0539 * Aug + 0.0343 * Oct + 0.1185 * Sep - 0.2929 * Light Snow/(Rain + Thunderstorm) - 0.0840 * (Misty + Cloud) + 0.1019 * Summer + 0.1267 * Winter + 0.0105 * Saturday - 0.0473 * Sunday ) $

An R-Squared value of 0.8033 on the test data signifies that the model is a very good predictor and 80.33% of the variance is captured by the model.It can be further improved by using other regression techniques.

Here it can be seen that on days with high temperature, the company should increase their bike availabilty as there is high high chance of increasein booking. Similarly we can see a reduce in booking on bad weather days such as snowy or rainy days, for those days they can put up some offers to attract people and increase booking.

