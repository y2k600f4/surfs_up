#Surfs Up Analysis

##Overview of the analysis:

The purpose of this analysis is to utilize SQLite, SQLAlchemy, and Flask to build on knowledge of SQL database structures and querying methods. In addtition to writing and executing Python code in a Jupyter notebook to create graphs. This methodology will be used to analyize a potential local business venture in Hawaii, a Surf and Shake shop serving surfborads and icecream to locals and tourists. Weather analysis is an important part in developing a proper business plan for a business involving surfing and icecream. Analytic methods will be used on weather data from the Hawaii island Awahoo, the island targeted for this business venture, to determine whether opening this business is a viable option.


##Results:

In conducting this analysis data was sampled from two different months of the year, June and December. Sampling of these two months was used to deterime if this business, a surf and icecream shop would be sustainable all year.


Using Python, Pandas, and SQLAlchemy, the date column was filtered from the measurements table in the hawaii.sqlite database in order to retrieve all the temperatures for the months of interest (June and December). Once this data was obtained, the temperatures were converted to a list,  a DataFrame was created from the list, and finally summary statistics were generated.

##Summary Statistics

###June Summary

![June Temps Summary](https://github.com/y2k600f4/surfs_up/blob/main/june_temps.png)

###December Summary

![December Temps Summary](https://github.com/y2k600f4/surfs_up/blob/main/dec_temps.png)

###Key Differences in weather between June and December

•	The average temperature in June is 74.9F and in December 71.0F, this is only ~4F delta between the two months of interest.
•	There are more data points of temperature data in June (1700) vs December (1517).
•	The lowest temperature in June is 64F and 56F in December. The highest temperature in June is 85F and 83F in December. The low temps between the two months has a delta of 8F and the delta of the high temps between the two months is only 2F.


###Summary:

Due to Hawaii's geographic location the temperature variation throughout the year is very minimal based on the two months selected for analysis (June and December) with the actual analysis shown above. These two "seasons" 6 months apart have some variation but for the most part the temperatures are pretty consistent (average temps). Temperatures are only one variable that contributes to weather and seasons. Further analysis to look at precipitation patterns in addition to winds and storm variations per month/season is recommended. This additional data analysis is recommended before determination on wether or not a Surf and icecream shop should be open all year.







