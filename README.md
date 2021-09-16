# Uber-Lyft-Cab-prices
Dataset :: [Kaggle cab price](https://www.kaggle.com/ravi72munde/uber-lyft-cab-prices "Uber lyft cab Price")

This dataset is a real-time data using Uber&Lyft api queries and corresponding weather conditions.The data is approx. for a week of Nov '18 at few locations of Boston.

* Dataset ::
  * Cab Rides Data :: The Cab ride data covers various types of cabs for Uber & Lyft and their price for the given location.
  * Weather Data   :: Weather data contains weather attributes like temperature, rain, cloud, etc for all the locations taken into consideration.

* Inspiration::
  * Our aim was to try to analyze the prices of these ride-sharing apps and try to figure out what factors are driving the demand.
  * Do people avoid cabs on a sunny day?
  * Was there a Red Sox match at Fenway that caused more people coming in?
  
  
- Steps (What we did) :: 
  - Reduce memory usage, Checking Data info (With Pandas).
  - Handle missing Values.
  - EDA :: 
    1. Divide columns on the basis of Category, Continous Values.
    2. Histogram plot of Category values WRT Price Columns 
    3. Scatter Plot of Continous values WRT Price Columns
    4. Average weather data WRT Locations Columns (Because we have only data of one week.) and copy it in Pickup locations and Destination Locations data
    5. Merge Uber Ride Data, Pickup Weather Data, Destination Weather Data
    6. Corelation WRT diffrent columns and WRT Price columns

  - Prediction ::
    1. One Hot encoding 
    2. Preprocessing Data for prediction
    3. Standardisation
    4. Prediction by Linear Regression
    5. Accuracy :: 0.92 
 


