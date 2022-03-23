# Airline On-Time Performance Data
## by Odai Alsalieti


## Dataset

> This database contains scheduled and actual departure and arrival times reported by certified U.S. air carriers that account for at least one percent of domestic scheduled passenger revenues. The data is collected by the Office of Airline Information, Bureau of Transportation Statistics (BTS).

> [Flights](https://community.amstat.org/jointscsg-section/dataexpo/dataexpo2009) The dataset name is "Airline On-Time Performance Data". This dataset reports flights in the United States, including carriers, arrival and departure delays, and reasons for delays, from 1987 to 2008. You can see the database description [here](https://www.transtats.bts.gov/DatabaseInfo.asp?QO_VQ=EFD&Yv0x=D)

>Since this is a large dataset; there are approximately 120 million records in total, and takes up to 12 GiB storage space. So, I choose to deal with moving average for last 3 years(2006-2007-2008) [downloaded here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7)



## Summary of Findings

> These data are the data of the last three years (2008, 2007, 2006) from the data that were submitted, which were combined and analyzed, and the results of the analysis were divided into

### Univariate Exploration Result:
>  **Southwest Airlines** , **American Airlines** and **Envoy Air**: had the most delays and cancellation over mean by Carrier in **2008**, **2007**, **2006** 

> **Chicago O'Hare International Airport (ORD)** , **Atlanta Airport (ATL)** and **Dallas/Ft Worth Intl(DFW)**: had the most delays and cancellation over mean by Origin in **2008, 2007, 2006**

> **Chicago O'Hare International Airport (ORD)** , **Atlanta Airport (ATL)** and **Dallas/Ft Worth Intl(DFW)**: had the most delays and cancellation over mean by Dest in **2008, 2007, 2006**

> **Friday** had the most delays and cancellation over mean in **2008, 2007, 2006**

> the **22th** day of month had the most delays and cancellation over mean in **2008, 2007, 2006**

> **December** had the most delays and cancellation over mean in **2008, 2007, 2006**

> Cancellation by Carrier and National Aviation System are the top two reasons for cancellations over mean

> Scheduled departure time Maximum delay or cancellation is at 17:00

> Scheduled Arrival time Maximum delay or cancellation is at 20:00

> Plans with tail numbers : **N17175**, **N651ML**, **N715SF**, had the most delays and cancellation

> Flights number **44** , **16**, **357** had the most delays

> Distance = **337 miles** had the most delays and cancellation

> Airtime on short flights of **100 minutes** or less has the Greatest cancelled flights


###  Bivariate Exploration Results:
 
> There is a strong relationship between 'DepDelay' and 'ArrDelay'

> There is a positive Relation between 'ArrDelay' and 'AirTime'

> There is a positive relationship between 'Distance' and 'AirTime'

> There is a relationship between 'TaxiIn' and 'DepDelay'

> There is Inverse relationship between 'TaxiOut' and 'DepDelay' since the linear regression had negative slop

> There is Positive relationShip between 'TaxiIn' and 'ArrDelay'

> There is positive Relationship between 'TaxiIn' and 'ArrDelay'

### Multivariate Exploration results:

> Correlation Map: there is a very strong relationship between: <br>
.  'DepDelay' and 'ArrDelay'<br>
. 'Distance','AirTime'<br>

> Departure Delays by day of Month:
 23th December had the highest Average of Departure delays
 
> Departure Delays by day of Week: Friday in December is the day that had the highest Average of Departure delays

> Departure Cancelled by day of Month: 12th, 13th, 14th February had the most Cancelled flights

> Departure Cancelled by day of Week: Friday in December had the heighest average of cancelled flights

> Scheduled Time Of Departure by Month: in June at 17:00 had the heighest average of delayed flights

> Scheduled Time Of Departure Cancelled by Month: 17:00 in February


## Key Insights for Presentation

> **Southwest Airlines** , **American Airlines** and **Envoy Air**: had the most delays and cancellation over mean by Carrier in **2008**, **2007**, **2006** 

> **Chicago O'Hare International Airport (ORD)** , **Atlanta Airport (ATL)** and **Dallas/Ft Worth Intl(DFW)**: had the most delays and cancellation over mean by Origin in **2008, 2007, 2006**

> **December** had the most delays and cancellation over mean in **2008, 2007, 2006**

> **Friday** had the most delays and cancellation over mean in **2008, 2007, 2006**

> Cancellation by Carrier and National Aviation System are the top two reasons for cancellations over mean

> Plans with tail numbers : **N17175**, **N651ML**, **N715SF**, had the most delays and cancellation

> Departure Delays by day of Month:
 23th December had the highest Average of Departure delays

>Departure Delays by day of Week:
Friday in December is the day that had the highest Average of Departure delays

> Departure Cancelled by day of Month: 12th, 13th, 14th February had the most Cancelled flights
