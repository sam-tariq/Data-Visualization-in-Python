# Data Visualization in Python


### 1 Data Visualization

#### 1.1 Introduction

Representation of information and data in the graphical form is called data visualization. Data
visualization significantly increases audience comprehension. You can have all the knowledge in the
world, but if you can’t make sense of it, it’s useless. “The single biggest threat to the credibility of
a presentation is cherry-picked data” – these are the great words said by Edward Tufte about his
views on data visualization. It’s also a type of visual art that captures our attention and keeps our
gaze fixed on the message.
The main objective of this report is to use data visualization to generate and analyze productionquality
graphics. Here, we are using matplotlib skills, demonstrating and recreating an existing plot,
then analyzing the improvements and implementing the new/improved plot. We are analyzing two
graphs, replicating them, and making improvements. One graph shows the number of apprehensions
on the US-Mexico border and the second graph shows the production of Pinot Grigio bottles in
Italy- by region.

### 2 The First Graph
We are given a graph from BBC on Apprehensions on US-Mexico border throughout some years
with different presidencies. First, we import all packages. We are using Numpy, Pandas, and
Matplotlib, Matplotlib.patches, rcParams.

#### 2.1 Graph Data

We are given a graph from BBC on Apprehensions on US-Mexico border throughout some years
with different presidencies. The data for this graph is taken from Customs and Border Protection.

#### 2.2 Replication of the Graph

We have recreated the plot by using matplotlib. On the x-axis, we have the years ranging from
2000 to 2018 and on the y-axis, we have the number of apprehensions.

#### 2.3 Critique and Improvements

1. It is noted that 2017 has the lowest number of apprehensions since 1971; however, that data
is not shown in the main graph. We have removed that information from the graph.
2. From the graph above we can see easily that there was a decrease in apprehensions on the
US-Mexico border in 2017 compared to the previous years. The grid lines make it easy for
us to approximate those numbers but we are not shown the exact number of apprehensions
during Trump’s presidency. So, we added the values for each bar corresponding to 2016,
2017, and 2018. This is done by using the in-built functions plt.text and plt.axvline.
3. There are two colors (light and dark blue) for this histogram. These colors show all years
before Trump’s administration and during his time in office. To make it more clear we have
added a legend to the graph by showing what each color means. We have done this by
using plt.legend.
4. We have added ticks labels for each year - on the x-axis. In addition to that, we have rotated
the x-axis labels by 45 degrees and written the entire year. For example, "02" corresponds to
"2002".
5. It is unclear what the total number of migrants means. Are we counting only the migrants
who were apprehended or total (together with the ones who successfully passed the border). Due to this uncertainty, we have removed the subtitle of the graph as the total number of
migrants is irrelevant since we are only counting the apprehensions.
