# TLC Trip Record Data

#### Data:
* The New York City Taxi and Limousine Commission (TLC), Over 200,000 TLC licensees complete approximately 1,000,000 trips each day. According to TLC the data it is recorded since 2009 - 2021 preprocess, we choose 2019 it's before COVID-19 and specificly October 2019 because it where halloween and most month that request cars, where we will find many messy data.


#### Question/need:
* Predict most pickup zone
* Pridict the time of the trip
* Predict the price of the trip?
* Predict waiting time and the total profit amount


#### EDA:
* Visualize the average yellow trip per day 2019-10
* Visualize the average green trip per day 2019-10
* Visualize the average FHV trip per day 2019-10
* Visualize the average high volume FHV trip per day 2019-10
* Display total profit amount for each company
* Display most pickup zone
* Display most drop off zone
* Correlation of the taxi price with the distance trip
* Visualize the highest and lowest choosen company in per day and the pickup and drop off zone on 2019-10
* Visualize which is the most shared or singlr rides
* Is the price differ between taxi and other companies?



#### Data Description:
* The yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.
* The For-Hire Vehicle (“FHV”) trip records include fields capturing the dispatching base license number and the pick-up date, time, and taxi zone location ID (shape file below). These records are generated from the FHV Trip Record submissions made by bases
* Note: The TLC publishes base trip record data as submitted by the bases, and we cannot guarantee or confirm their accuracy or completeness.


#### Tools:
*	Python and Jupyter Notebook 
*	Numpy and Pandas for data manipulation 
*	Matplotlib and Seaborn for plotting visuialization 
*	Folium for for visualizing geospatial data 
*	Sklearn for LinearRegression

#### Dataset Link:
[TLC Trip Record Data](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

