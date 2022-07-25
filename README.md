# PyBer_Analysis


## Overview of the analysis:
Use several types of visualizations(scatter plot grapghs, pie charts and fivethirtyeight graph) to tell a compelling story about the relationship between type of city, and the number of drivers and riders, as well as the percentage of total fares, drivers, and riders by the type of city. 

The purpose of this analysis is to help PyBer improve access to ride sharing services and determine affordabilty for underserved neighborhoods. 

Data: Provided in two .csv files at city and rider level. The two datasets were merged into one which combine the info into one data source.

Tools used: Python Scripts using Pandas Libaries, Juypter Notebook and Matplotlib

## Results:

By looking at the graphs (time period from January 2019-April 2019) provided below, we can learn that Urban neighborhood represented 62.7% ($39.9k) of the total fare($63.5k), with the highest number of rides at 1625 out of 2375 in total. which is the higher than rural and suburban neighborhoods and the average fare at $24.52. Comparing the three neighborhoods, rides in rural neighborhood represented the highest average per ride at $34.62

![piechart](https://github.com/tiffanylin706/PyBer_Analysis/blob/687f57bdbba1ed5736c74e7adadb93ba1bb36a7f/analysis/Fig5.png)

![TotalFareSummary](https://github.com/tiffanylin706/PyBer_Analysis/blob/687f57bdbba1ed5736c74e7adadb93ba1bb36a7f/analysis/PyBer_fare_summary.png)


The fact that Urban neighborhood has 2405(80.9%) drivers while Suburban only has 625(16.5%) and Rural has 78(2.6%) can lead to two situations:

![TotalDrivers](https://github.com/tiffanylin706/PyBer_Analysis/blob/2d3ac4807e076a74db9eddbf872228b527415590/analysis/Fig7.png)

* Urban neigherhood has a higher demand of ride share services, therefore, the average fare per ride is lower than the other two neighborhoods due to the need and the availability of drivers. 
* Rural neighborhood pays more for their ride due to the scarcity of the drivers in the area.

This can also be interpreted by the scatterplot chart attached below.
![scatterplot](https://github.com/tiffanylin706/PyBer_Analysis/blob/687f57bdbba1ed5736c74e7adadb93ba1bb36a7f/analysis/Fig1.png)

##Summary and Suggestions:
To conclude, accoriding to the data, majority of the ride share service occurs in Urban neighborhood. In order to develop more bussiness and to lower the price for Suburban and Rural neighborhoods, there are some recommendations:

* Hire more drivers for Suburban and Rural neighborhoods in order to reduce the scarcity, this can help lower the fares and people will be more willing to use the service.
* Suburban and Rural neighborhoods may not have as high demand as Urban neighborhood does. Therefore, we can create the demand ourselves. Partner with local restaurants to provide food delivery service in order to increase the demand.
* Develop a coupon system by asking riders to share the code to their families and friends in order to get free rides or coupons could be a way to increase the demand for the Suburban and Rural neighborhoods.
