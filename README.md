# Aliens Arrive Project

## Introduction

Data visualization project on May 2018.
Javascript, HTML, CSS.

A Description of Data<br>
In this project, we get the inspiration from a dataset on Kaggle, which contains over 80,000 reports of UFO sightings over the last century.
https://www.kaggle.com/NUFORC/ufo-sightings/data
Also, we use the universal World-50m.json  and us-states.json for the map drawing.

Data Formatting and Filtering<br>
In this dataset, there are mainly the following columns:
datetime,city,state,country,shape,duration (seconds),duration (hours/min),comments,date posted,latitude,longitude. We use d3 and Panda( python library) for the data cleaning and formatting.

There are mainly three steps we do here: We format the datetime column to a year column in order to simplify the animation as there are more than 80,000 records.
We calculate the total amount of sightings for every year for the visualization.
We calculate the total amount of each shape of the UFO.
We reorganize the record in the U.S



## Our roles:

Shuran Li:<br>
Responsible for part of the final layout design. Completed implementation of the finalized layout using d3.js.(Section 2)<br>
Hanchun(Elena) Shao:<br>
Responsible for part of the final layout design. Completed implementation of the finalized layout using d3.js.(Section 3)<br>
Beitong Tian:<br>
Responsible for part of the final layout design. Completed implementation of the finalized layout using d3.js. (Section 1)<br>
Zhengnan Zhao:<br>
Responsible for part of the final layout design. Completed implementation of the finalized layout using d3.js. (Section 1)<br>

## Data to visual:

Aliens Arrive! UFO sightings in the last century in the U.S. Outer space is always the most attractive and mysterious topics that make not only give scientists and sci-fi writers inspirations but make the masses crazy. In this project, we hope to apply interesting interactive visualizations to several data insights about UFO sightings in the last century in the U.S. We designed three sections for delivering different data insights.

Section 1:
UFO landing map
We believe it will be amazingly fancy and inspiring for the audience if we can show them the process of all the UFO sightings in an interesting and vivid way. We come up with many ideas for this main visualization and finally decided on the ideation inspired by the sci-fi movie, Independence Day. In this movie, a huge UFO floating over the earth and all the alien army will be sent off from the gate of this huge spaceship.  We believe it will be a cool idea if we can also design a UFO floating over the U.S. Imagine all the UFOs that have been sighted are released by this huge UFO, and then landed to different spots. All the lines represent the journey that the UFO is released and fly to the earth. The circle on the map represents that the location the each UFO is sighted.
![img](https://github.com/hs926/alien-arrive/raw/master/image/section1.gif)


Section 2:
Besides a fancy visualization of the overall history of these 80000 UFO sightings, we hope to utilize the dataset to present more interesting facts. Therefore, in section 2, we hope to show audience UFO sightings by years. We imply a time slider to allow audience control the exact year. At the same time, UFO insights will be highlighted and a total amount of the sightings in that year will be shown in red dots. The audience could also hover over each dot to see the location of the UFO.  
![img](https://github.com/hs926/alien-arrive/raw/master/image/section2.gif)

Section 3:
In this dataset, we have a very interesting data points about the shape of the UFO according to the reporters. We use this data present a visualization of different shapes. The audience can hover over shapes to see how many sightings of this shape have been witnessed within the last century. We want our users to have fun and explore by themselves through irregular circular rotation. Let the user takes time to feel the shape and to find the highest and the lowest frequency.
![img](https://github.com/hs926/alien-arrive/raw/master/image/section3.gif)



The story.
In this data visualization, we hope to let audience play with our visualization with curiosity and surprises. At the beginning of our story, we used rays to simulate UFO landing over the U.S. mainland in the last century. We used automated data visualization to show viewers where and when all aliens were observed. The audience can have a basic impression of the huge number of aliens. The luminous yellow line will attract the audience's attention and shine in the dark background. We then implemented two interactive data visualizations to give our audience a better understanding of the UFO sighting. The audience could further understand the basic information including UFO shape and UFO number. In our first interaction, the audience can see the whole US map with all landing spots at the first sight. To explore the number records in specific year, audience could simply move our slider in upper left corner. The audience can have the hand-on experience to feel the dramatic increase in numbers over years and the difference between continents. In our second interaction, we displayed total 25 UFO shapes described in report over the last century and highlighted the one has highest frequency, light, which appeared 16565 times. To explore the different frequency of each shape, audience can easily hover over a shape to check its reported count.
