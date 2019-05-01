# Flights data exploration
## by Benjamin UWIMANA MAHUKU


## Dataset

> This dataset reports flights in the United States, including carriers, arrival and departure delays, and reasons for delays,
from 1987 to 2008. The [data](http://stat-computing.org/dataexpo/2009/the-data.html) comes originally from RITA as the website says.
Given the size of dataset for each year, only three of them (1988, 1998 and 2008) were combined to form single file for this analysis. There are 17,596,545 flights in the clean dataset with 15 features.


## Summary of Findings

> In the exploration I found that Fridays have consistently recorded more departure delays than other days of a week for the three selected years/datasets (1988, 1998 and 2008). Plotting departure delay rates per day yields further light on this showing that more than 2.5% of fights are delays for departure on Fridays. Saturdays are having smallest departure delay rate (almost 1.8%) for the three selected years.
It also appeared that the two last selected years (1998 and 2008) have similar distributions of departure delays. But for the three years taken together, December shows greater departure delays of flights with more that 1.75% of flights delayed for departure. September is having smallest departure delays (almost 0.75% of all departure delayed flights).
Regarding reasons of delay, I noticed that **Weather Delay** is causing longest departure delays (around 80 minutes on average per month). On the other hand, **Security Delay** is having shortest departure delays (around 35 minutes on average per month). The same trend is observed when we look at average departure delays per day of week.
When we consider first 30 unique carriers linked to longest departure delays, It seems that **Weather Delay** is the most prominent reason of departure delays impacting most of unique carriers followed by, **Late Aircraft Delay** and **Carrier Delay** departure delay reasons. **Security reason** seems to impact fewer unique carriers. This trend also applies to airports of origin of flights.


## Key Insights for Presentation

> For the presentation, I focus on the length of departure delays and based on it I put them in different categories. Then I started to look at how they occur in time (on specific day of week or during specific month of the year).
Afterward, I looked at the correlation of departure delays (**DepDelay** variable) and recorded reasons of delays (**CarrierDelay**, **WeatherDelay**, **NASDelay**, **SecurityDelay**, and **LateAircraftDelay** variables in the dataset).
The next step was to look at magnitude of reasons of delays considering the average delay (in minutes) per month each of them is causing. Finally, I looked at effects of reasons of delay on unique carriers and at origin airport of flights.


## Some of resources I used

Most of resources used to complete this project are provided with course material. But in addition, I also used some sites for specific concepts, including:
- [pandas 0.24.2 documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.groupby.html)
- [Shane Lynn](https://www.shanelynn.ie/summarising-aggregation-and-grouping-data-in-python-pandas/)
- [GitHub](https://github.com/burakgunbatan/UdacityProject---CommunicateDataFindings)
- [Stack Overflow](https://stackoverflow.com/)
