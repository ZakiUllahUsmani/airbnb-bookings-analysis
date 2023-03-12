# Air Bnb Booking Analysis

![tenor](https://tenor.com/view/airbnb-globe-gif-4896074.gif)

Airbnb is an online marketplace that connects people who want to rent out their homes with people who are looking for accommodations in specific locales.
The company had come a long way since 2007 when its co-founders first came up with the idea to invite paying guests to sleep on an air mattress in their living room. According to Airbnb's latest data, it has more than six million listings, covering more than 100,000 cities and towns and 220-plus countries worldwide.
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb has become a one-of-a-kind service that is used and recognized by the world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analyzed and used for security, business decisions, understanding of customers' and providers' (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services, and much more.


This dataset has around 49,000 observations in it with 16 columns and it is a mix of categorical and numeric values.
Travel industries are having an important reflection of the economy over the past few decades, and Airbnb housing price ranges are of great interest to both Hosts and Travelers. In this project, we are analyzing the various aspects with different use cases which covers many aspects of Airbnb listings. It helps in not only understanding the meaningful relationships between attributes but also allows us to do our own research and come up with our findings.

# Problem Statement

What can we learn about different hosts and areas?
What can we learn from predictions? (ex: locations, prices, reviews, etc)
Which hosts are the busiest and why?
Which room type is preferred in most popular neighbourhood?
Top neighbourhoods in NYC with respect to average price/day of Airbnb listings?


# Business objective

The objective of the project is to perform an exploratory data analysis, data pre-processing, data cleaning & imputation and at the end, apply different Data Visualization techniques to get the meaningful insight from the given data. This project aims apply some amazing Python Libraries such as Numpy, Pandas, Matplotlib and seaborn, which will give better insights and beautiful visualization.

# Features understanding.

**id:-** listing ID

**name:-** name of the listing

**host_id:-** host ID

**host_name:-** name of the host

**neighbourhood_group:-** location

**neighbourhood:-** area

**latitude:-** latitude coordinates

**longitude:-** longitude coordinates

**room_type:-** listing space type

**price:-** price in dollars

**minimum_nights:-** amount of nights minimum

**number_of_reviews:-** number of reviews

**last_review:-** latest review

**reviews_per_month:-** number of reviews per month

**calculated_host_listings_count:-** amount of listing per host

**availability_365:-** number of days when listing is available for booking

# Project Flow

* Data Loading
* Data cleaning
* Data Wrangling
* EDA and visualization
* Conclusion

 # Key findings:-
1. Manhatten has the highest number of listings (21660) followed by Brooklyn (20095) and queens (5666). Bronx (1090) and State Island (373) has the least number of listings.
2. The entire home apartment (25407) is the highest number of room type listing followed by Private room (22319). There is only a few shared room type (373).
3. Manhattan and Brooklyn make up 85% of listings available in NYC.
4. Manhatten and Brooklyn are the most liked neighbourhood groups by people.
5. Queens has significantly fewer host listings than Manhattan. So, we should take enough steps to encourage host listings in Queens.
6. The maximum demand is for private rooms and entire homes/apartments. People are more interested in cheaper rentals.

 # Conclusion:-
We can conclude from the analysis that Manhattan is the top neighbourhood group when it comes to the number of listings and highest rental prices. Given that Manhattan is world-famous for its museums, stores, parks, and theatres - and its substantial number of tourists throughout the year, hence the prices are much higher in this borough.


The number 2 neighborhood group is Brooklyn having a significant number of listings and more affordable prices if compared to Manhattan.


For other neighbourhood groups namely Queens, Bronx, and Staten Island there aren't as many listing options available, especially on Staten Island.


Considering that those are residential areas, it is possible that many guests choose these locations to save up money or perhaps to visit family and friends who live in this area.


For our data exploration purpose, it would have been nice to have couple of additional features like positive and negative reviews. Depending upon that we could have gauged the popularity of each neighbourhood.
