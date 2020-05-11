# _AirBnb_Price_pred_and_analysis_
## This project is aimed to bring out the important facts about the _New_ _York_ city airbnb details by analizing its dataset..
## It also has a predictive part which is totally dedicated to find a suitable predictive model for the company, and its future growth.
\
Source of the Dataset:- https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data
<img src="airbnb_image/New_York_Map.png"><br>
<img src="airbnb_image/nyc_map.png"><br>
### Some of the facts that I found working on this dataset are..
###### 1. *Generally private rooms are considered in New York while renting on AirBnb, except in Manhatten where an Entire home/apt is prefered.*
<img src="airbnb_image/room_type.png"><br>
###### 2. *The average price of Manhatten is more and therefore calling it the most expensive of all the neighbourhoods,*
  <img src="airbnb_image/nei_violin.png"><br>
###### 3. *Bronx is the neighbourhood group which has an average low cost properties thus considering it as the cheapest among all the 5.*
###### 4. *Staten Island can be said to have a mix of both, i,e having the rich ones and also the poor ones..*
  <img src="airbnb_image/price.png">
Many kinds of analysis is presented in my Notebook, to know more facts please do go and check it out.

#### While Predicting...
##### Tried many models by reducing the error curve..
<img src="airbnb_image/alpha_optimize.png"><br>
##### and optimizing the alpha.... and found the best model which was XgboostRegressor..
###### *Please do checkout the project for more details.*
