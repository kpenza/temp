# Burglary is more common in Seattle

The criminal incident data of Seattle, Washington and San Francisco, California covering the summer 2014 period was analyzed.

Data was processed using python and graphs plotted using matplotlib package. In order to be able to process the data it require manipulation and cleansing.


## Seattle

The data set contained crime reports over the summer 2014 period. This data was loaded and analyzed. Some of the entries had missing data, for example, the occured date of the crime was missing, in that case the crime date is assumed to be the report date. This assumption is important, however in this case it will not influence any findings or conclusions.

![Figure 1](https://raw.githubusercontent.com/kpenza/temp/master/figures/figure1.png "Figure 1")

Figure 1 shows the occurance of the crime and the major cateogry of the crime. The "OTHER PROPERTY" category is a general category for other types of theft, such as building theft. Car prowl is the most common crime and it amounts to 19% of the total number of report. From this chart, it emerges that the top three occurring crimes are theft related and they amount to 33.6% of the total number of reports.

## San Francisco

The data set for San Francisco covers the summer 2014 period. The data provided is structured differently and it required code amendments to successfully load and analyze the data.

![Figure 2](https://raw.githubusercontent.com/kpenza/temp/master/figures/figure2.png "Figure 2")

The most common crime in summer 2014 is larceny and it amounts to 32.5% of the total number of reports. From figure 2, the second most common criminal crime is assult that amounts to 9.9% of the total reports.

## Comparing Seattle and San Francisco

Direct comparison between the two subsets is not possible as the structure of the dataset are different. The category labels are different and in some cases a category is further fragmented in a city whilst the a broader term is used in the other city. This makes the category mapping process somewhat difficult. Care has been taken to avoid cirsumstances in which the severity of the crime is escalated or the crime are incorrectly categorized. 

The crime cateogory and the respective occurances for each city are plotted adjacent to each other, for easy comparision.

![Figure 3](https://raw.githubusercontent.com/kpenza/temp/master/figures/figure3.png "Figure 3")

Figure 3 shows that the number of burglaries in Seattle is almost double to that in San Francisco. The trend that theft/bulglaries/robberies in Seattle have higher incident counts than in San Francisco emerges. On the other hand, narcotics and assults in are much higher in San Francisco.

Using the census 2010 data, San Francisco (city) QuickFacts from the US Census Bureau. and Seattle (city) QuickFacts from the US Census Bureau. the population of San Francisco is 668,342 and that of Seattle is 852,469.

| State|Population|Reports|Incidents per capita|Theft related reports|Incidents per capita|
|--------|---|---|---|---|---|
| San Francisco |668,342|28993|43 incidents per 1000 people|11746|17.57|
| Seattle|852,469|32779|38.4 incidents per 1000 people|19624|23|


## References

Quickfacts.census.gov, (2016). San Francisco (city) QuickFacts from the US Census Bureau. [online] Available at: http://quickfacts.census.gov/qfd/states/06/0667000.html [Accessed 6 Feb. 2016].

Quickfacts.census.gov, (2016). Seattle (city) QuickFacts from the US Census Bureau. [online] Available at: http://quickfacts.census.gov/qfd/states/53/5363000.html [Accessed 6 Feb. 2016].

