# PyBer_Analysis

## **Overview of Analysis**

The purpose of this analysis is to review the Pyber ride sharing service and what factors may go into improving the company. We will be looking at a few different vectors of data with an emphasis on reviewing the city type (rural, urban, suburban) and trying to see if we can find patterns that would lead us to making recommendations for improvement.

## **Analysis Summaries**

### **2019 Ride Sharing**

![This is an image](https://github.com/Bren42/PyBer_Analysis/blob/main/analysis/Fig1.png)

Lets start off by looking at the overall 2019 data in this scatter chart. As we can see this is a very high level overview. What it tells us initially by looking at the data is the majority of our rides are situated in urban city areas, followed suburban and then rural areas. In fact when we pull the direct values out of the data it looks to be 1625 rides for urban areas versus 625 for suburban areas and finally 125 for rural areas. So urban areas generate more ride volume than suburban and rural area combined. This is not overly surprising based on population differences and likely distances between destinations. However this data does not really tell us enough to make an informed analysis. 

### **City Summary**

![This is an image](https://github.com/Bren42/PyBer_Analysis/blob/main/analysis/city%20type%20summary.png)

As we had mentioned before the total rides is heavily skewed towards urban areas, but lets take a closer look at this summary data.
- Total Drivers: Nothing surprising here, more rides per area are going to drive up the need for more drivers to accomodate demand, this tracks with our ride data.
- Total Fares: Just on total fares we see nothing new here, each prior category is trending to high, middle, and low directly in line with their volume data.
- Average Fare per Ride: Here is were we start to see some new trending. Urban areas make up the largest share of overall dollars, however as we can see the average fare per ride between suburban($30.97) and urban($24.53) shows a 20% increase in the average fare per ride. However due to the nature of the two areas, with urban areas being more densely populated and destinations being closer this can be explained. 
- Average Fare per Driver: This is where we start seeing some significant differences. Rural has an average fare per driver of $55 dollars, but with so few rides and such a heavy skew away from the average fare per ride this does not factor as significant. What is more interesting is that suburban areas show a average fare per ride and driver that fall in close alignment. Urban fare per driver though shows we have some issues emerging, there is a 34% downward swing between the average fare per ride and the average drivers fare.

However lets look at how the rides as a percentage of the whole and driver counts as a percentage of the whole stack up against each other.

![This is an image}(https://github.com/Bren42/PyBer_Analysis/blob/main/analysis/Fig6.png)

As we can see in the chart Urban areas account for 68% of all rides in this timeframe, suburban making up another 26% and again rural following with 5%.

![This is an image}(https://github.com/Bren42/PyBer_Analysis/blob/main/analysis/Fig7.png)

When we look at the driver data though we see that urban has an outsized number of drivers at nearly 81% of all drivers even though they are only 68% of all rides, a 13% upwards swing. Suburban is drawing 26% of the ride volume with only 16.5% of the drivers. We will need to look through the fare percentages to see if our revenue aligns with our other data points.

![This is an image](https://github.com/Bren42/PyBer_Analysis/blob/main/analysis/Fig5.png)

We are starting to see some interesting patterns here. 
- Urban rides are 68% of all rides, and their percentage of total fares is 62%. However they are 80% of the total drivers. there is definitely some areas to improve here.
- Suburban rides are 26% of all rides, but their percentage of total fares is 30%, and their driver count is 16%. So we can see some real positive upsides in this area.
- Rural also shows positive trending with nearly 7% of all fares, on only 5% of the total rides and less than 3% of drivers.

## Fares over the quarter
![This is an image](https://github.com/Bren42/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

Lets also look at a time vector to see if there are any seasonal impacts.
As we can see the data in the time summary shows a very similar story as the other charts we have viewed, Urban pulling the highest share of fares consistently over the quarter, suburban follows in the middle and rural again is a small share of the overall.

## **Final Summary**
In reviewing all of our previous findings we now know the following:
- Urban rides make up the vast majority of all rides and the largest chunk of revenue. However they also are disproportionately represented with drivers.
- Suburban rides make up a much smaller percentage of the rides, but they are far better balanced with drivers to rides leading to a better per ride fare average and driver fare.
- Rural rides do have the highest average fare per driver, however all else aligns to their smaller client base and longer drives. 

#### Recommendations
Look at reducing or re-allocating drivers in the urban area. This area should have a higher portion of all calls, and thus drivers, however the average fare per driver is so low in relative comparison to all other areas that it directly points to an oversupply of labor and an area were drivers are competing against each other for fares.

