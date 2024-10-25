# Data Visualization Project

## Data

The data I propose to visualize for my project is [World Population Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/world-population-dataset). In this Dataset, we have Historical Population data for every Country/Territory in the world by different parameters like Area Size of the Country/Territory, Name of the Continent, Name of the Capital, Density, Population Growth Rate, Ranking based on Population, World Population Percentage, etc.


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which countries are the outliers in population growth rate and growth rate?
 * Is there a correlation among population, growth rate and density?
 * Whether countries on each continent will have particular population features?

## Sketches
![Sketch1](sketch.jpeg)

Clicking on the bubble will take you to the detailed page of the country.

![Sketch2](sketch1.jpeg)

## Prototypes

According to the basic idea (x-axis to growth rate, y-axis to density, bubble size to population), I made [this very early prototype](https://vizhub.com/GwentMasterShen/9aaea5c82a564afead882d4a64b96200).

![FirstPrototype](first_prototype.png)

This prototype looks weird, almost all countries are at the bottom of the plot, because there is an outlier in density. It's a problem I have to solve. After that, I'll add a bunch of interactive parts, including filters that let the viewer adjust the range of the plot, a drop-down menu for selecting the country to be displayed on the plot, and mouse hovers and clicks.

## Milestones

* Complete a acceptable bubble chart.
* Add filter and drop-down menu.
* Complete the country detail page.
* Complete mouse clicking and hovering.

## Progress

* __Week 1:__ Each bubble is colored to represent the country's continent. To make the data more tightly distributed, I changed the values of the y-axis to the logarithm of the population density. Additionally I manually set the range of values for the x-axis and y-axis of the image. These manipulations made the chart more readable. In future work, I will aim to make the adjusting range part of the interactive part for the viewer.
