# Delayed Flights Data Exploration
## by Edward Kyalo


## Dataset

The dataset contains information on the approximately 1,936,756 domestic flights within the United States during the year 2008. The complete dataset can be downloaded from this kaggle webpage [here](https://www.kaggle.com/giovamata/airlinedelaycauses/download). 
Additional datasets for interpreting carrier codes and iata codes were downloaded from The Bureau of Transportation Statistics website [here](http://stat-computing.org/dataexpo/2009/supplemental-data.html)
The variables in the dataset are documented in this webpage [here](https://www.transtats.bts.gov/Fields.asp?Table_ID=236)


## Summary of Findings

Arrival delay had a left skewed unimodal distribution. Log transofrmation of the x axis and removal of extreme high outliers made the distribution somewhat less skewed. The 3 highest cause of delay were carrier, national air system and late aircraft, evidenced by a bar chart of their means. 35.2% of flights were on time, 65.4% were late, 0.4 were diverted and 0.03 were cancelled. Majority of flights were scheduled to depart between 6am and 11pm, with the peak at 7pm. Southwest Airlines had the most flights operated in 2008, beating the second in place by more than 100,000 flights. The locations of the top 20 busiest airports (for both origin and destination) were located in major metropolitan areas throughout the contiguous United States. Weather caused the most calcellations. 

The three highest delay causes had the greatest correlation with arrival delay. Arrival delays peaked in February, Juna and December. None of the destination airports with the 10 highest mean arrival delay were in the 10 busiest airports list. There was a relationship between total diverted flights and total flights operated. 

Carriers with fewer flights had wider distributions of arrival delay. Mean Carrier delay did not follow the general trend followed by National air system and late aircraft delays. 
Carriers caused the most delays for flights departing between 6am and 11am, then late aircraft caused most of the rest of the day's delays. There was a decrease in mean arrival delay among the 8 carriers with the lowest total flights operated. 



## Key Insights for Presentation

In the presentation, I focused on the arrival delay and delay causes, along with one chart each to show their relationship with carrier by total flights operated and scheduled departure time respectfully. 

I started off the presentation with a histogram of arrival delay with high outliers removed to better show the shape of the distribution. Next, I showed a barchart of mean delay for each cause, clearly showing the causes with the highest delays. There after, I presented a barchart showing mean arrival delay by carrier in order of descending total flights operated showing the increase in width of arrival delay distribution with decreasing total flights operated. The final chart is a linechart of a 15 minute rolling window if total delay for each cause over 24 hours, showing carrier delay as the major delay in the early morning hours and late aircraft asn the major cause for the remainder of the day. 
