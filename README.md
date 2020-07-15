# Data-Visualization-with-Plotly-Express

# Steps followed :

1. Loading the Data

2. Quick Visualizations with Custom Bar Charts
  Plotly Express functions accept tidy Pandas data frames.
In this task, we will graph the population of Canada by year using a bar plot. In a bar plot, each row of the DataFrame is represented as a rectangular mark.
We will also customize the bar plot using keyword arguments to color the bars according to the average life expectancy.

3. Plot Life Expectancy vs GDP per Capita
  Create a basic scatter plot showing life expectancy vs GDP per captita by country for 2007.
Next, break that down by continent by coloring the points using the color argument, while Plotly Express takes care of assigning the default colors, setting up the legend, etc.

4. Customize Interactive Bubble Charts
  Each point in the previous plot is a country. To scale the points by the country population, simply pass in the size argument!
If you're curious about the identity of a particular point, you can add a hover_name to display the country name.
You will never again have to worry about what a particular outlier represents. You can simply mouse over the point of interest and the hover_name will identify it.

5. Create Interactive Animations and Facet Plots
  We are able to easily interact with the plots we have created so far. Try mousing over points, clicking or double-clicking on legend items, or using the modebar that appears when you move your mouse into the frame to control the behaviour of click-drag interactions (zoom, pan, select).
Create facet plots to pick apart the continents, just as easily as coloring your points, with facet_col="continent", and make the x-axis logarithmic to see things more clearly.
Maybe you're interested in more than just 2007 want to see how the chart evolved over time.
You can animate it by setting animation_frame="year" and animation_group="country" to identify which circles match which ones across frames.
Provide prettier labels that get applied throughout the figure, in legends, axis titles and hovers. Also provide some manual bounds so the animation looks nice throughout.

6. Represent Geographic Data as Animated Maps
  As this is geographic data, you can also represent it as an animated map, which makes it clear that Plotly Express can make a lot more than just scatter plots, and that this dataset is missing data for the former Soviet Union.

# Reference : https://plotly.com/python/plotly-fundamentals/ 
