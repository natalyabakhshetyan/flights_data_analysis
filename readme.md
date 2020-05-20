# Exploring US domestic flight data
## by Natalya Bakhshetyan


## Dataset

> This document explores US domestic flight data for years 2017 through 2019. Only January data is used. A random sample of 30,000 flights was analysed, whereas the original data contains about 1.5 million flights.The original dataset was downloaded from http://stat-computing.org/dataexpo/2009/the-data.html.

## Summary of Findings

> The exploration of the data reveals interesting information about US domestic flights: 
* Saturday is the day of the week with the least number of flights. 
* Top 3 destination states are California, Texas and Florida.
* There are minimal amount of flights between 1 am and 4am, with a lot of flights occuring early in the morning and late in the afternoon.
* Flights with some destination airports have higher divertion rates than others.
* Thirsdays have the highest cancellation rate, while Fridays have the lowest.
* Some origin airports are home to longer delays than others.


## Key Insights for Presentation

> Exploration of cancellations, delays and their reasons were the key insights of this report due to the fact that the data reveals some non-obvious and useful information about those: 
* Some origin airports are more prone to cancellations than others. For the most part, airports located in cities with cold winters have higher cancellation rates than airports in cities with warm winters. 
* Cancellation reasons vary from airport to airport. The predominant cancellation reason for the 10 busiest airports is weather. Some airports have more NAS cancellations than carrier delays and vice versa. Security is the rarest cancellation reason. 
* A lot of departure delays are short, within 40 minutes, but there are also many delays ranging from 40 to more than 1000 minutes in length. 
* Late aircraft delay is the most frequent delay reason and security delay is the rarest. Some origin airports are more home to longer weather delays than others. Some are more prone to security delays than others. 

## Resources
* Data: https://www.transtats.bts.gov/Fields.asp?Table_ID=236
* Visualizations: https://python-graph-gallery.com/