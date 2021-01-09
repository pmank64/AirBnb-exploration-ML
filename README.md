# AirBnb Dataset Exploration and Machine Learning

### Project Summary

As a team*, we were tasked with locating a dataset of our choosing, and performing cleaning, EDA, and machine learning steps. We chose an Airbnb dataset because of the varied and interesting features, the sizable number of observations, and the relevance of the subject matter. Each row of the "Listings" dataframe represents a listing on Airbnb, containing information about the property itself, as well as statistics about the host. 
Project Objectives
Our primary objectives were:
* Analyzing neighborhood popularity for superhosts and non superhosts, based on traffic, types of rooms (Private Rooms/Shared Rooms/Entire Apartment), and price
* Drawing a comparison between the pre- and post-COVID listing prices
* Predicting the type of host (superhosts/non-superhosts) and understanding what attributes contribute to the classification of a superhost
* Predicting the price for Airbnb listings in New York City and understanding what features contribute to profitable business opportunities for Airbnb
### Dataset Overview
Our data was taken from 4 files as listed below. The datasets were taken from InsideAirbnb and were last updated in October 2020.
1.	Listings (Detailed listings data for New York City.)
2.	Reviews (Detailed review data for listings in New York City.)
3.	Calendar(Detailed calendar data for listings in New York City.)
4.	Neighborhoods (Neighborhoods list for geo filter. Sourced from city or open source GIS files.)

### Conclusion

We noticied that there is higher competition for Airbnb hosts in Manhattan, and that the most expensive neighborhoods (Flatiron District and Tribeca) are located in downtown Manhattan. Also, there are a large number of entire home/apartment type listings in Manhattan which indicates that hosts in Manhattan might percieve Airbnb listings as a business opportunity, viz-av-z hosts in Brooklyn, who would be looking to save rent/money by renting out private rooms.
COVID-19 impacted the price of listings which reduced after the onset of the pandemic. The nunber of reviews also decreased as a result of the pandemic.
The number of reviews plays a significant role in determining the prediction of host types, but is not significant in predicting price of listings. However, features related to accommodation, room type and neighborhoods in Manhattan, Queens and Brooklyn play an important role in determining future price of the listings. These features would be crucial for AirBnb to predict revenue.

### Recommendations for Prospective Hosts

* Regular updates of listing images and descriptions as ratings are based on these features
* Adjustment of listing prices based on the availability of competing listings within the neighborhood, especially during special circumstances such as COVID-19
* We observe a trend of higher listing prices for superhosts, which provides prospective hosts with a great incentive to aim for becoming superhosts
* Airbnb hosts can place more emphasis in finding guests who are opinion leaders and bloggers who can leave positive reviews and increase exposure of the listing
* Prospective hosts can penetrate markets/boroughs with popular neighborhood locations where listings are in higher demand

### Future Work

* Exploring other models to predict price where overfitting is not an issue
* Finding new alternatives to deal with outliers
* Identifying new ways to deal with missing values
* Gaining more insight on the lack of number of listings for shared room types in NYC

*Yulong Gong, Ruchika Venkateswaran, Yi-shuan Wang, Yangyang Zhou
