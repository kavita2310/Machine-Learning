<h1>Home price prediction analysis project (Python+Machine Learning):</h1>


This project aims to predict Home Price Prediction based on historical data and various influencing factors
such as suburb, address, room, type, price, method, seller g, date, distance, postcode, bedroom2, bedroom,
car, land size, region name, property count. The goal is to developed  machine learning model that can 
accurately forecast home price.


 <h1>Project Overview</h1>:

Home prices prediction project goal is to develop a machine learning model that predicts the price of a
home based on various features such as location, size, number of bedrooms and other relevant factors. 
By leveraging historical data on home sales, the model can help real estate agents, home buyers and 
investors make data driven decision about property pricing.  This project explores various machine
learning algorithms to predict Home prices and provides insights into which features are most important
in influencing prices.


<h1>Key Analysis Performed</h1>:

•	Collect and clean Home price prediction data, including price, distance,  bad rooms2, bath room, car, land size, building area, council area, region name, property count.<br>
•	Drop the columns are address, date, post code, year built, latitude, longitude.<br>
•	Identify key features affecting price fluctuations.<br>
•	Build and evaluate Linear Regression machine learning models to predict Home prices.<br>

  <h1>Data Set</h1>
 
The dataset use for this project contains information such as:<br>
Suburb: Suburb<br>
Address: Address<br>
Rooms: Number of rooms<br>
Price: Price in Australian dollars<br>
Method:<br>
S - property sold<br>
SP - property sold prior<br>
PI - property passed in<br>
PN - sold prior not disclosed<br>
SN - sold not disclosed<br>
NB - no bid<br>
VB - vendor bid<br>
W - withdrawn prior to auction<br>
SA - sold after auction<br>
SS - sold after auction price not disclosed<br>
N/A - price or highest bid not available<br>
Type:<br>
br - bedroom(s)<br>
h - house, cottage, villa, semi, terrace<br>
u - unit, duplex<br>
t - townhouse<br>
dev site - development site<br>
o res - other residential<br>
Seller G: Real Estate Agent<br>
Date: Date sold<br>
Distance: Distance from CBD in Kilometres<br>
Region name: General Region (West, North West, North, North east …etc)<br>
Property count: Number of properties that exist in the suburb<br>
Bedroom 2 : Scraped  of Bedrooms (from different source)<br>
Bathroom: Number of Bathrooms<br>
Car: Number of cars spots<br>
Land size: Land Size in Metres<br>
Building Area: Building Size in Metres<br>
Year Built: Year the house was built<br>
Council Area: Governing council for the area<br>
Latitude: Self explanatory<br>
Longitude: Self explanatory<br>

 <h1>Technologies used</h1>:

•	Pandas : For data manipulating and processing.<br>
•	Machine Learning: Evaluate Linear Regression model of  machine learning.<br>
•	Python used for data analysis and model building.<br>
•	Matplotlib: Draw the graph.<br>


 <h1>Model Evaluation Metrics</h1>:
 
•	Root mean squared error(RMSE): To measure prediction error.<br>
•	Mean Absolute Error(MAE): To assume prediction accuracy.<br>
•	 Mean Squared Error (MSE): How well a predictive model performs by comparing the predicted values to the actual values in a dataset.<br>
•	 R2 score: how well a regression model fits the data.<br>
•	Create the target data and feature data where target data is price.<br>
•	Create a linear regression model for Target and feature data.<br>
•	Check if the model is over fitting or under fitting or it is accurate.<br>
•	 If the model is over fitting then apply ridge and lasso regression algorithms.<br>
•	Extract slope and intercept value from the model.

<h1>Insights and Findings:</h1>

•	R2 score is 0.6880.<br>
•	Mean Absolute Error is 225429.0437.<br>
•	Mean Square Error is 126325789910.3076.<br>
•	Root Mean Squared Error is 63162894955.1538.<br>
•	Positive correlation between price and land size: AS land size increases, price trends to increase.<br>
•	Positive correlation between price and number of bedrooms: As the number of bed rooms increases, price tends to increase.<br>
•	Negative correlation between price and distance to CBD: As distance to CBD increases, price tends to decrease.<br>
•	Significant prediction: Land size, number of bedrooms and distance to CBD are significant predictors of home price.<br>

