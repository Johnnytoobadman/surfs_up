# Surfs Up Challenge

## Background:

I have decided to follow my passions for surfing and eating ice cream and am committed to buying a surf shop that also sells ice cream located in the state of Hawaii.  I have savings I am willing to invest to start the business but I will need more initial capital from outside investment. I have one potential investor, W. Avy, that has experience with opening a surf shop.  Unfortunately his shop was rained out and his business folded. Before he makes any investment he will need to see analytical eveidence that the surf shop will not be a vistim of the weather.  He has the data needed to do the analysis for the island of Oahu. He knows that in addition to analysis I have already provided the investors will want to see the minimum, maximum and average temperatures for Oahu before they are ready to invest. Specifically he wants to see this for the months of June and December.

## Resources:

 - hawaii.sqlite (Measurement (date, temperature, precipitation) and Station (station ID))

 - Jupyter Notebook version
 
 - VS code Version
 
 - Python Version
 
 - Github
 
 - Pandas Version
 
 - NumPy Version
 
 - SQLalchemy version
 
 - Flask Version
 
## Results:

The summary statistics for June are as follows:



The summary statistics for December are as follows:


## Summary:

Comparing June to DFecember it is very obvious that the temperature in Oahu does not fluctuate very much.  

 - June's average temperature is only approximately 4 degrees warmer than December.  The maximun temperature for June is only 2 degrees warmer. 
  
 - The standard deviation for both are fairly close with 3.26 for June vs. 3.75 for December. 
  
 - The major difference between the two months are the minimum temperatures where June's low is only 64 degrees compared to December's low of a chilly 56 degrees.
 
 -  It should be noted that these lowest of low temperatures would be experienced most likely during the late night and early morning hours when ice cream is less likely to be consumed. 
  
 -  One important point to make though is to seriously consider how desireable ice cream and surfing are when the average temperatures are in the low 70's.  More analysis will be needed.

### Additional analysis required:

 - Additional queries are need to  consider the entire year in terms of temperature statistics.  Why just analyze 2 months?  Why not analyze each quarter? (March, June, September, December).  The additional information may provide greater insight as to the temperature variations throughout the year.  It is not unreasonable to run the analysis on each month of the year.

 - Why are we not looking at precipitation AND temperature throughout the year.  In prior anaysis (climate-analysis) both precipitation and temperature statistics were barcharted.  A similar analysis needes to be performed showing both temperature and precipitation in the same chart. 

 - Scatter plots should be considered to better understand the incidence and quantity of precipitation throughout the year to show to the investors.
