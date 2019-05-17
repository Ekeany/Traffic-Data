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

<p align="center">
  <img width="929" height="611" src="/Images_/image5.PNG">
</p>

<p align="center">
  <img width="924" height="611" src="/Images_/image6.PNG">
</p>

This visualisation is an interactive graph that highlights the position of the intersection under study. Each turn on the junction is labelled from A to D. A more complex visualization was attempted by using a colour gradient the turn of each road to indicate the severity of the traffic such as google maps. However without the ability to animate the visualization it was complex and non informative, instead the following plots were generated.

<p align="center">
  <img width="703" height="504" src="/Images_/image7.PNG">
</p>

In order to contrast and compare both distributions the vehicle density on an hourly and daily scale were investigated again. The plot below is the average hourly count for each vehicle over the day including every turn. This dataset contained a different variety of classes that made it harder to simply divide into 5 classes like the previous plots, therefore all 10 sub classes of vehicles were plotted. Again due to the difference between values the van and car classes were separated from the rest.

<p align="center">
  <img width="917" height="614" src="/Images_/image8.PNG">
</p>

A treemap was used to represent the daily average of the 10 classes on the same plot in an elegant fashion. The area of a tile represents the average count for a vehicle for that particular day. Despite the distribution being similar to the entire N59, the only visible difference is the dramatic increase in the number of cyclists. More than likely due to the insight centre which is an educational institution which would therefore have different ethos than an average company.

<p align="center">
  <img width="675" height="481" src="/Images_/image9.PNG">
</p>

The next visualisation shows the total PCU value for each turn on the junction ie. turn from Road A onto Road B. The hourly PCU value of each turn were represented using a simple barchart that was faceted on the original road from which the vehicle came from. It is clearly visible that road B is the busiest as it has the highest hourly density when compared of any other turn. This is logical as road B signifies the start of the N59. The second busiest turn is turn C which is simply a continuation of the N59 as it follows the same direction and is the direct link from the N59 to the city centre. Finally turn A has the lowest amount of traffic as this essentially a private road which leads to the Dangan IDA business park. The distribution of the hourly PCU values does not have the same peaks seen before.Although Road B has a large spike at 8am and the other three roads all spike at 5pm. This indicates that the road users are commuting from the east using the N59 to travel to work. And then at 5pm they have to use the junction to travel home this seems to be where the traffic stems from as in the morning the road is large and everyone’s true destinations are scattered so the traffic is only on the N59, however at 5 they all must use the same junction to return to the N59 therefore the traffic is spread over the other 3 roads.

<p align="center">
  <img width="701" height="487" src="/Images_/image10.PNG">
</p>

A diverging bar chart was created to highlight the hours in which traffic was most prevalent on the N59 throughout the day.The total PCU value for each hour was calculated for each day and the mean PCU value for the entire week was then subtracted from each value to create the diverginging bar chart. The results are as expected , the traffic is mainly confined to a specific time period mainly from 6am to 7pm. Within this timeframe there are spikes at 8am and 5pm on weekdays. In contrast the weekends have later starts approximately 10am and have a more balanced distribution in general. There is also a difference between the east and westbound traffic despite the two sharing a similar distribution the westbound road has a higher PCU values in the morning and lower PCU values in the afternoon and evening in comparison with the eastbound traffic.

<p align="center">
  <img width="929" height="617" src="/Images_/image11.PNG">
</p>

The final set of graphs visually represent the impact that public transport can have on the traffic density of Galway. Both graphs use a simple area graph to compare the difference between the original distribution and the amended solution’s average PCU values. Figure 17 explores the effect a regular bus service from Moycullen to the IDA park would have on the traffic density. From research online a standard city bus at maximum capacity can take 40 cars off the road at a single time. Therefore assuming the buses are approximately half full each bus will remove 20 cars from the N59. A service every half hour is proposed from 7am to 8pm with two more services provided one every 15 mins or 4 every hour should be scheduled from 7am-9am and from 4pm-6pm at the peak commuting times. From the graph below there is a clear reduction in traffic density with the hourly distribution almost remaining constant. 

<p align="center">
  <img width="919" height="612" src="/Images_/image12.PNG">
</p>

The final graph from this report details the effect a cycle path from Moycullen to Galway city via the IDA Business Park and the University would have on traffic density. From research online it was suggested that a cycle lane would increase the number of cyclists by 100%. Therefore the hourly average number of cyclists was multiplied by 100% and the difference was subtracted from the car total as it was assumed that these new cyclists previous mode of transport was the car. Again the average PCU values were calculated and plotted. It is aparent that the bicycle also decreases the average traffic density however not as much as the bus example above.However a cycle lane is an inexpensive fix compared to a new bus service.

<p align="center">
  <img width="919" height="618" src="/Images_/image13.PNG">
</p>

## Conclusion.

Rising traffic congestion is an inescapable condition in growing metropolitan areas across Ireland. Peak-hour traffic congestion is an inherent result of the way modern societies operate. As the efficient operation of both the economy and school systems requires that people work, go to school, and even run errands during the same hours so they can interact with each other, inevitably overloading the existing road and transit systems. Two relatively low cost solutions (in comparison to the proposed 600 million city bypass) were explored within this report both of which had a positive impact on traffic density. Despite the regular bus service achieving lower density values. I believe no single solution is necessarily better than the other, due to the complexities of each solution and limited data. However, in my opinion sustainable transport should be promoted and encouraged in Ireland especially with or carbon emissions 2020 target looming. In the long run the Irish government should learn from these shortcomings especially with the resurgence in the construction industry. Leaving the development of new homes to the private market, while the taxpayers are left to take care of funding the public transport services needed to service them is not progressive!. We should instead look towards are friends in Europe were high density developments are created and serviced by light rail, buses and cycle lanes.



