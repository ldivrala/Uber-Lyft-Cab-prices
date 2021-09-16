# Uber-Lyft-Cab-prices
Dataset :: https://www.kaggle.com/ravi72munde/uber-lyft-cab-prices

This dataset is a real-time data using Uber&Lyft api queries and corresponding weather conditions.The data is approx. for a week of Nov '18 at few locations of Boston.

Dataset :: \
&emsp; Cab Rides Data :: The Cab ride data covers various types of cabs for Uber & Lyft and their price for the given location. \
&emsp; Weather Data   :: Weather data contains weather attributes like temperature, rain, cloud, etc for all the locations taken into consideration.

Inspiration:: \
&emsp;  Our aim was to try to analyze the prices of these ride-sharing apps and try to figure out what factors are driving the demand. \
&emsp;  Do people avoid cabs on a sunny day? \
&emsp;  Was there a Red Sox match at Fenway that caused more people coming in?
  
  
Steps (What we did) :: 
  1. Reduce memory usage, Checking Data info (With Pandas).
  2. Handle missing Values.
  3. EDA :: \
            A. Divide columns on the basis of Category, Continous Values. \
            B. Histogram plot of Category values WRT Price Columns \
            C. Scatter Plot of Continous values WRT Price Columns \
            D. Average weather data WRT Locations Columns (Because we have only data of one week.) and copy it in Pickup locations and Destination Locations data.\
            E. Merge Uber Ride Data, Pickup Weather Data, Destination Weather Data \
            D. Corelation WRT diffrent columns and WRT Price columns

  4. Prediction :: \
            A. One Hot encoding \
            B. Preprocessing Data for prediction \
            C. Standardisation \
            D. Prediction by Linear Regression \
            E. Accuracy :: 0.92 
 


