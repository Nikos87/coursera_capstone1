Choosing the best location for new fast food restaurant

Nick Bananis

January 8, 2020

1. Introduction

In Greece, the nightlife is wild and most night clubs stay open until the sunrise. 
Along with the clubs there are usually fast food restaurants open the same hours, since after a drinking night, 
most people seek something to eat before going home. The Business Problem I created has to do with finding a 
good spot to open such a fast food restaurant, specifically a creperie. This project works for the southern 
suburbs of Athens (capital of Greece) and finds all the night clubs that can boost the income of a 24-hour 
fast food restaurant and all the already existing creperies (possible antagonists). Changing the location 
and the boost/antagonist name this algorithm can be beneficial for anyone who seeks to open a new restaurant 
with familiar criteria.


2. Data acquisition and cleaning

2.1 Data sources

Google maps where used to select the area examined and to find the approximate center of it.
Then in a 10,5 km range, I've searched for all the nightclubs which can be beneficial for my future restaurant
and all the already existing same-type restaurants. All that combined in a map, all created with the location data 
provided from Foursquare.
The algorith was writen on a jupyter notebook created on IBM Watson Studio and then linked to Github.

2.2 Data cleaning

From the location data taken from Foursquare, only the columns that include venue name, and anything that was 
associated with location was kept.

2.3 Possible future add-ons

The purpose of this project is to give a taste to someone on how to choose a possibly good location
to open a fast food restaurant. It helps sorting out some "good spots" from which after applying more
criteria, the best will be chosen. Some of those extra criteria can be the real estate prices, the existance
of other-type fast food restaurants, the real estate availiability, etc. Which may require some business analysis first.
 
3. Exploratory Data Analysis

3.1 Relationship between Night clubs and other creperies

The map created is a great visual tool and helps from the very first look to sort out some spots that seems ideal 
with the criteria given. For further analysis K means can be usefull to clarify things that the eye alone cannot 
catch. However, the project was kept on purpose at this point of analysis, so that every future user can apply
the extra criteria matching his needs.

5. Conclusions

As seen on the map, night clubs' and creperies' locations in Athens usually match, as given from our hypothesis.
The most interesting fact, is that the location which has the most night clubs and at the same time lacks antagonists 
seems to be near the center of the area we chose to work with, which is a matter of lack (no data where taken in concept
before choosing the location)

6. Future directions

The algorith gave a first idea on which areas seem good to focus on. From this point, some Business analysis might
be handy to provide extra criterias wwhich will lead us to the best choice.
