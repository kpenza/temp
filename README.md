# Burglary is more common in Seattle

In this assignment the criminal incident data of both Seattle and San Francisco was analyzed. The analysis was performed using python and graphs plotted using matplotlib package.

The analysis of the data required data manipulation and cleansing so as to ensure proper handling.

In this blog, I will perform individual analysis of states and then proceed compare the two states

## Seattle

The data set contains crime reports over the summer 2014 period. This data was loaded and analyzed. In the dataset there is some missing data, for example, the occured date is missing, in that case the crime date is assumed to be the report date. This assumption is important, though it will not change the findings.

![Figure 1](https://raw.githubusercontent.com/kpenza/temp/master/figures/figure1.png "Figure 1")

INSERT FIGURE 1

The most common crime in the summer period is theft. Car prowl amounts to 19% of the reports or 6230 report of 32779 in the dataset. From figure1, the pattern that in seattle theft is very common, quickly emerged as 3 more occurring crimes are theft related and amount of 33.6%. 


![Figure 2](https://raw.githubusercontent.com/kpenza/temp/master/figures/figure2.png "Figure 2")

INSERT FIGURE 2

Figure 2 plots the crime occurance against the time of the day, i.e. early morning, morning, afternoon, night. It is interesting that in seattle most of the crime occur in the early morning and morning period. No crimes were registered during the night period.

![Figure 3](https://raw.githubusercontent.com/kpenza/temp/master/figures/figure3.png "Figure 3")

INSERT FIGURE 3

Figure 3 shows the number of crimes per district/zone. The district with most criminal reports is M, most of which were files in zones M1 and M3. In contract districts F and O are the districts where the number of reports is low.

## San Francisco

The dataset for San Francisco covers the summer 2014 period. The data provided is strctured differently however it loaded and analysed.

![Figure 4](https://raw.githubusercontent.com/kpenza/temp/master/figures/figure4.png "Figure 4")

INSERT FIGURE 4

https://raw.githubusercontent.com/kpenza/temp/master/figures/figure4.png

The most common crime in the summer period is larceny and it amounts to 32.5% or 9446 of 28993 in the dataset. From figure3, the second most common criminal crime is assult that amounts to 9.9% of the total reports.

![Figure 5](https://raw.githubusercontent.com/kpenza/temp/master/figures/figure5.png "Figure 5")

INSERT FIGURE 5

From figure 5 it transpires that in general most common crimes occur in the afternoon/night period of the day. This general trend is also true if larceny.

![Figure 6](https://raw.githubusercontent.com/kpenza/temp/master/figures/figure6.png "Figure 6")

INSERT FIGURE 6

The crime rate in each district is shown in figure6. This clearly shows that the district with most reports is Sourthern whilst bayview and tenderloin has the leat reports.

## Comparing Seattle and San Francisco

Direct comparison between the two subsets is not possible as the structure of the dataset are different. The category labels are different and in some cases the category is further fragmented in a states whilst the order state uses a more generic term. This make the mapping process somewhat difficult. Care has been take to avoid cirsumstances in which the severity of the crime is escalated or the crime are incorrectly categorized.

After mapping the data, the crime data is plotted. For each category the number of crimes for each district is plotted adjacent of easy comparision. Figure 7 shows this data.

![Figure 7](https://raw.githubusercontent.com/kpenza/temp/master/figures/figure7.png "Figure 7")

INSERT FIGURE 7.

Figure 7 shows that the number of burglaries in seattle is just below two fold of that in san francisco. In most theft/bulglaries/robberies seattle has a much higher incident count when compared to san francisco. On the other hand, narcotics and assults are much higher in san francisco.

Using the census 2010 data, San Francisco (city) QuickFacts from the US Census Bureau. and Seattle (city) QuickFacts from the US Census Bureau. the population is 668,342 and 852,469 respectively.


| State|Population|Reports|Incidents per capita|
|--------|---|---|---|
| San Francisco |668,342|28993|43 incidents per 1000 people|
| Seattle|852,469|32779|38.4 incidents per 1000 people|


## References

Quickfacts.census.gov, (2016). San Francisco (city) QuickFacts from the US Census Bureau. [online] Available at: http://quickfacts.census.gov/qfd/states/06/0667000.html [Accessed 6 Feb. 2016].
Quickfacts.census.gov, (2016). Seattle (city) QuickFacts from the US Census Bureau. [online] Available at: http://quickfacts.census.gov/qfd/states/53/5363000.html [Accessed 6 Feb. 2016].

