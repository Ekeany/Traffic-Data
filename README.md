# Traffic-Data

## Introduction.

As everyone knows Galway has a serious transportation problem, due to its dependence on the private car. This dependency is heavily influenced by the weak public transport network, limited cycling facilities, large rural hinterland and it is position as the gateway to Connemara. Combining this with a road and street network that is desperately ill-suited to modern transportation. Has created crippling levels of traffic congestion that have directly affected the quality of life and functionality of this beautiful city. To counteract this problem, a fundamental shift is needed in the direction of sustainable travel and a reduction in the dependency on the private car; by creating a city that is more connected and accessible, thus enhancing the quality of life for all. The aim of this report was to not only analyse and visualise real traffic data from the N59 collected by Galway City Council, but to visualize the impact that public transport could have on daily traffic levels.

## Results.

The first plots describe the daily and weekly vehicle distributions of the eastbound and westbound traffic on the N59. To reduce the visual complexity of each graph a number of vehicle classes were merged together to create five classes, cars, vans, two wheeled, bus and heavy goods vehicle. The daily distributions were represented as a tilted bar chart whereas a pie chart was used for the weekly distributions. This dataset is slightly misleading as it suggests that there is a greater number of vans then cars on the road this is more than likely due to an error in data collection as some vans will have same axle with as a car, or a small HGV, so may be misclassified. Similarly the total number of cyclists may be under represented as some cyclists may not be detected if they cross the sensor at the same time as a vehicle or they simply are using the pavement. Despite this ratio of buses and less intrusive means of transport are significantly low.

<p align="center">
  <img width="920" height="613" src="/Images_/image1.PNG">
</p>

<p align="center">
  <img width="914" height="617" src="/Images_/image2.PNG">
</p>

The second plot visualises both dimensions of traffic, density and speed on an hourly scale. The velocity for each point was calculated as the average velocity across the week for a particular hour of the day. Whereas the size of a point was indicated by the average density of the traffic at that particular hour of the day. The density was calculated using the Passenger Car Unit scale which measures the impact that a mode of transport has on traffic variables (speed, density) in comparison to a single standard passenger car. Wednesday had abnormally high velocity values which diluted and complicated the visualization therefore this was added as a custom annotation in the upper right corner of the plot. From the visualisation lower speeds and larger point size indicate the presence of traffic congestion, it can be clearly seen that all of the weekdays have congestion around 8am and 5pm whereas the on the weekends the traffic levels are more stable throughout the day.

<p align="center">
  <img width="670" height="485" src="/Images_/image3.PNG">
</p>

<p align="center">
  <img width="682" height="489" src="/Images_/image4.PNG">
</p>

The third plot seeks to investigate the vehicle density of the N59 on an hourly scale. The hourly count for each vehicle over the week is grouped by the hour and the average value taken. The same 5 classes used previously are again implemented. As the average density of both cars and vans are much larger than the other classes they were given their own plot. From both the graphs you can see the spikes at 8am and 5pm both the car and van classes as these are personal vehicles. Whereas the buses, bicycles and HGV have a more balanced distribution throughout the day. It is clear that there are a much larger amount of commuter travelling eastbound than westbound on the N59. 
