# Understanding AirBnB prices in Seattle
## Table of Content

 1. Libraries used
 2. Project motivation 
 3. File description
 4. Summary of the results 
 5. Acknowledgements
_______
### Libraries used
 - Numpy
 - Pandas
 - Geopandas
 - Matplotlib
 - Sklearn

_______
### Project Motivation

The dataset offers unlimited opportunities for analysis. I was particularly interesting in the pricing of the listings, hence, my analysis evolves around that.

I read some other articles in regard to AirBnB beforehand. For example,  AirBnB has posted an article **These Social Media Worthy  Amenities Rank Highest on Airbnb** in which they explore which of the amenities are highest ranked by customers. Thus, I was interested whether these preferences are also reflected in the price. 

While amenities are characteristics of individual properties I was interested looking at some meta data. Therefore, I analyzed the **impact of listings' location** has on the price. 

Another interesting article I have seen is where landlords are wondering about demand in "off-season". Again, I wanted to determine in which months of the year the demand (and presumably the resulting prices) of the listings are rather low or rather high. 
_______
### File description 

The seattle_data folder contains a dataset from Kaggle ([www.kaggle.com/airbnb/seattle](https://www.kaggle.com/airbnb/seattle)), which comprises of three different files:

-   calendar.csv: calendar availability of listings and price
-   listings.csv: information about all the available listings
-   reviews.csv: listing reviews by the users

Additionally, I added shape files from the zip code areas of Seattle for visualization purposes. 
_______
### Summary of results

I analyzed how homes in Seattle perform in terms of pricing according to Airbnb open data. I found that:

 1. Certain amenities such as a pool, hot tub, etc. increase the
    value of the rental space.
 2. The location of the home within the city impacts the price as
        well.
 3. For some zip areas, seasonality is a big factor when it comes to
            setting the rental price, whereas for other areas it might be less
            important.
___
### Acknowledgements

Credit to the AirBnB dataset published by AirBnB as well as to Kaggle for hosting it. You can find the dataset here: [https://www.kaggle.com/airbnb/seattle](https://www.kaggle.com/airbnb/seattle).
