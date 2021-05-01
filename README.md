# D3 Interactive Visualization

## Background

This interactive web visualization features scatter plots built using D3.js exploring the visible relationships between various health risks facing particular demographics. Information is from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System. The data set is based on 2014 ACS 1-year estimates from the [US Census Bureau](https://data.census.gov/cedsci/), and includes data on rates of income, obesity, poverty, etc. by state.

**The visualization is live [HERE](https://rmurnane94.github.io/d3-challenge/).**

![1](https://github.com/rmurnane94/d3-challenge/blob/main/pics/screen2.png)

This interactive web visualization features scatter plots demonstrating the relationship between two data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`. The visualization includes multiple demographics and risk factors labels in the scatter plot axes. Various relationships can be explored by clicking the axis titles.  Circles feature the state abbreviation and the exact plot values can be seen by hovering over each.

Scatter plots are made using D3.js to plot each state with a circle element. The [`app.js`](https://github.com/rmurnane94/d3-challenge/blob/main/assets/js/app.js) file pulls in the data from [`data.csv`](https://github.com/rmurnane94/d3-challenge/blob/main/assets/data/data.csv) to creat the visualization by using the `d3.csv` function. Using D3, all of the CSV data is bound to the plotted circles. Click events tied to the axis titles select which data to display. The movement of the circles' locations and the selection of the axes are animated using transitions.  Tooltips displaying circle data when the user hovers their cursor over the element are created using the `d3-tip.js` plugin.


![2](https://github.com/rmurnane94/d3-challenge/blob/main/pics/screen3.png)
