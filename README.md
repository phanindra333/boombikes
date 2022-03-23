Bike Sharing Assignment
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes
How well those variables describe the bike demands
Table of Contents
General Info
Libraries Used
Conclusions
General Information
The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Dataset used: day.csv which has the information of all variables which influence the bike rentals
Using the Mulitple Linear regression model, the plan is to identify the variables which are significant in predicting the shared bikes demand. Also, how well those variables explain the bike rental demand.
Conclusions
The following are the variables which are significant in predicting the demand for shared bikes.

Year
Temp
Windspeed
Spring season
Jul & Sep months
Light snow/rain & Mist weather
The equation of the best fit line is:

$ count = 0.304 + 0.236 * year + 0.394 * temp - 0.153 * windspeed - 0.146 * spring - 0.073 * jul + 0.053 * sep - 0.275 * lightsnow - 0.080 * mist $
Technologies/Library Used
Python
Numpy
Pandas
Matplotlib
Seaborn
sklearn.model_selection
sklearn.metric
sklearn.preprocessing
sklearn.feature_selection
sklearn.linear_model

conclusion:
for the conclusion Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands and to book them in seasonal wise.
