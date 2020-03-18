# Data Wrangling in Pandas Using Seattle Airbnb Data

In this project, I take a deep look at Seattle Airbnb data to address some of the business questions as well as practice data wrangling in pandas, which might be of use for people practicing data manipulation coding interview in pandas.

## Questions answered:
I addressed these business questions in Seattle airbnb data.
* Variations in price, price per accommodate, number of Airbnb listings, and property type across different neighborhoods of Seattle.
* How much discount you should expect (or negotiate) from the owner if you book a place for a week or a month?
* How do the listing availability and prices change throughout the year? (availability and price trends).

## Installation

To run the code completely in the jupyter notebook, you need to install a few libraries using either pip or conda (Pandas, Numpy, Scipy, geopandas, and shapely).
```
pip install numpy
pip install geopandas
pip install numpy
pip install scipy
```
For instructions on installing shapely using pip click [here](https://towardsdatascience.com/install-shapely-on-windows-72b6581bb46c).

## Analysis and Conclusion
The codes insides the jupyter notebook will walk you through the 3 questions mentioned and you will see my solutions to some made up questions for data wrangling practice. The summary of the analysis is as follows:
* There is a high variation in price and number of listings in Seattle neighborhoods, where neighborhoods in Central Seattle having the largest number of listings as well as the highest price per accommodation. Also, as expected the majority of listings in central Seattle is of type apartments, where as houses are more located in neighborhoods far from center.
* For those places that offer weekly or monthly renting, you can expect around 17% discount for weekly stay and 30% discount on monthly stays.
* The availability of listings rises in early months of the year. But right after the end of Spring break and the beginning of April, there is a huge dip in listing availability. When the summer begins, the number of available listings grow again. In July and August, when Seattle is experiencing the warmest weather, less people may travel to Seattle and that’s why we see a big dip during that time. The owners might use this period to do the maintenance, upgrade, or restock. As we get close to end of the year the number of listings spikes and we observe most availability around Christmas time.
* The pricing is also showing some seasonal pattern, increasing gradually for the first 7 months of the year, then dropping in August as the demand decreases, then rising back up peaking in December.

