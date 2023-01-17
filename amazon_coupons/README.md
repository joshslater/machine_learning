# Background
This analysis focuses on a data set that studies dynamic coupons for different types of goods and services while individuals are driving. Observations are made around the context of the driver when the coupon was offered, and ultimately tracks as boolean as to whether or not the coupon was accepted (either immediately or at some point in the future).

# Overall Dataset
The dataset contained 12684 observations. 24 columns represented the context of the observation (things like destination, gender, marital status, income, frequency of visits to various establishments, etc.).

Of these 12684 rows, 605 were dropped due to missing values. Additionally, one of the context columns (type of car) was dropped completely, as it was almost entirely empty.

## General Findings
* Coffee House coupons were most offered.
* Expensive Restaurant coupons were least offered.
* Overall, of the retained observations, 41.2% of coupons were accepted.

# Bar Coupons
Additional specific analysis was done on coupons for bars.

## Findings
It was observed that the following traits increased likelihood of accepting a bar coupon:
* Frequenting a bar >= 1 time per month
* Not having kid(s) in the car
* Having a higher income and not going to cheap restaurants often.

# Coffee House Coupons
Additional specific analysis was done on coupons for Coffee Houses.

## Findings
It was observed that the following traits increased likelihood of accepting a Coffee House coupon:
* Frequenting a coffee house >= 1 time per month
* Being less than 15 minutes away from the redemption location at time of offer
* Not having an urgent destination

# Next Steps
As a next step, it would be interesting to start to assess the combinatorial factors that may go into likelihood of coupon acceptance, in a multi-variate sense. 