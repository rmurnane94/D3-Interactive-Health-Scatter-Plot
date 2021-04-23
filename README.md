# d3-challenge


## Background

This interactive web visualization features scatter plots exploring the visible relationships between various health risks facing particular demographics through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The data set included with the assignment is based on 2014 ACS 1-year estimates from the [US Census Bureau](https://data.census.gov/cedsci/), includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

**The visualization is live [HERE](https://rmurnane94.github.io/d3-challenge/).**

### Visualization
![1](https://github.com/rmurnane94/d3-challenge/blob/main/pics/screen2.png)
![4-scatter](Images/4-scatter.jpg)

You need to create a scatter plot between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.

Using the D3 techniques we taught you in class, create a scatter plot that represents each state with circle elements. You'll code this graphic in the `app.js` file of your homework directory—make sure you pull in the data from `data.csv` by using the `d3.csv` function. Try binding all of the CSV data to your circles. This will let you easily determine their x or y values when you click the labels.


includes multiple demographics and risk factors labels in the scatter plot and click events which data to display.  the transitions of the circles' locations as well as the range of your axes are Animated.
While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Add tooltips to your circles and display each tooltip with the data that the user has selected. Use the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)—we've already included this plugin in your assignment directory.




![2](https://github.com/rmurnane94/d3-challenge/blob/main/pics/screen3.png)
