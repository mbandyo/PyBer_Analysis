# PyBer_Analysis
This analysis compares and contrasts ride fare among cities in urban, suburban and rural areas. Aggregating daily ride data, it produces a weeky summary of fare patterns and delivers the information through user friendly graphical representations. The purpose of the project is to identify potential areas for change to optimize use of ride share. Ride share practice has many environmental and ecological benefits including less traffic, less pollution, conservation of non-renewable energy sources and more. Affordibility and convenience are major determinants of the choice for ride share. In order to facilitate ride share practices, it is important to make the service affordable and convenient. 
## Analysis 
#### Resources:
1. Data from two sources cosisting of city name, drivers per city and classification (urban/suburban/rural) of the city. 
2. Ride  data consisting of city name, date of ride, ride id and fare fare per ride.
3. Software: Python, pandas library and matploblib

Data was first combined into a single comprehensive dataset. Following sample snapshot provides an overview of the datapoints.</br>
![PyBer Data](https://github.com/mbandyo/PyBer_Analysis/blob/main/Resources/PyBer_Data.png) </br>
Summary of total rides, drivers and fares by city types were calculated. The results are as follows:
##### Total Rides &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Total Drivers &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Total Fares</br>
![Total Rides by Type](https://github.com/mbandyo/PyBer_Analysis/blob/main/Resources/Total%20Ride%20Summary.png) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp; ![Total Drivers by Type](https://github.com/mbandyo/PyBer_Analysis/blob/main/Resources/Total%20Driver%20Summary.png) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp; ![Total Fare by Type](https://github.com/mbandyo/PyBer_Analysis/blob/main/Resources/Total%20Fare%20Summary.png) </br>   
Summary of average fare per ride and average fare per driver are as follows:
##### Average Fare per Ride &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Average Fare per Driver
![Average Fare per Ride](https://github.com/mbandyo/PyBer_Analysis/blob/main/Resources/Average%20Fare%20per%20Ride%20Summary.png) &emsp;&emsp;&emsp;&emsp;![Average Fare per Driver](https://github.com/mbandyo/PyBer_Analysis/blob/main/Resources/Average%20Fare%20per%20Driver%20Summary.png)</br>

The following table consolidates summary data above:</br>
![PyBer Ride Data Summary](https://github.com/mbandyo/PyBer_Analysis/blob/main/Resources/Consolidated%20Summary%20Table.png)</br>
#### Conclusion:
The analysis reveals that the number of drivers and rides are highest for urban followed by suburban and rural cities. The total fares follow the same pattern. However, the average fare is directionally opposite i.e. highest for rural, followed by suburban and urban areas. 
Clearly, there is room for expansion of ride share facilities in suburban and rural areas, while this might reduce average fares, it would increase total fares from these areas. Following are potential actions for increasing total fares from underserved suburban and rural areas.
1. Hire more drivers in suburban and rural areas.
2. Increase the number of available rides in suburban and rural areas.
3. The timing of the available rides could be optimized during the day through more granular reserach to explore if peak hour rides are more in demand.
