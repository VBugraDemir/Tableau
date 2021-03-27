
# Preparing for Analysis

## Data preparation

Visual analytics to reveal insights and show relationships not easily seen in traditional
reports. 

To slice and dice your data to break down information into smaller parts with different
perspectives. Tableau organizes data into two main groups. Dimensions and measures.
* Dimensions: Categorical or qualitative data
* Measures: Numerical data that can be aggregated.

## Preparing the data
To convert a columns right click it and select create. Everytime a column created its
default properties sould be checked. To search between rows to find similarities 
highlighters can be used from analysis. This makes Highlighter great for quick searches and scans
without doing any filters.

## Calculated Fields to extend data

To create calculated field click the dropdown menu. DATEDIFF() function can be used to calculate
differences of 2 date columns. Again their defaults should be changed again. Logic structure
can be used to create columns. Right click and show filter will let you do interactive filtering.

## Visualizations for exploratory analysis of trends
* Discrete: Trends by hour, day of the week...
* Continuous: Presenting data over time int hte sequence it historically occured.
Tableau enables us to quickly experiment with seasonality and patterns in data.

## Discrete time analysis and Quick Table Calculations
after adding data it can be set as discrete or continuous from the dropdown menu. 
Percentage of the data can be calculated from the quick table calculations. Computation 
can be changed based on table (down or cross.)

## Slicing and dicing

With 2 dimensions and one measure, a tree map can be created. Bubble chart is interesting!


# Exploring Visualizations


## Exploring user data

Changing the null value with a reasonable value is more efficient then deleting them.
The filters can be added to the right hand shel to make them interactive.

## Building a KPI dashboard
Key Performance Indicators are measurable values that track a company's key business objectiveness.
Entire view will make sure that charts will fill up whatever space is available in the 
dashboard. By getting the sheets to the dashboard their set filters come with them. By applying
to worksheets all using this data source, this will ensure that whenever a filter is applied, 
every sheet using this data source will filter its content accordingly. By selecting a chart
to use as a filter we can filter other charts accordingly.


## The distribution of users
User demographics are important. (usertype, gender, birtyear). Age is another element that 
impacts businesses. Bins are important while visualizing nurmeric values as categories. Small
bins provides more detail and noise so, finding that suits best is important.

## Working with bins
To adjust bing right click the field that will be visualized and click bins. That will create 
a new field. Too wide bins can hide important details about the distribution and narrows can
cause a lot of noise and hide important information as well.



# Mapping Analysis

## Interactive mapping of customer activity over time
Mapping customer activity can be a powerful way to reveal trends and gain insights. Using 
the Pages shelf we can put activity in motion and show the trends over time in a fluid progression
revealing information that is hardly available otherwise. Another powerful Tableau feature
table calculations.

## Customer activity in motion
To put the data in your visualization is easy. Just double click on longitude and latitude.
There are lots options that can make your map visualization better in the map section. For the
heatmap density can be chosen from the marks. For additional information the tooltips can be 
updated. To create filtering pages Pages shelf can be used. Lots of selection can be done on the
map. Searching for flaces, radial selection, rectangular selection and lasso selection (something
more custom)


## Layering and total dock utilization
To create layers we need dual axis. We can place the field to the rows for 2 times and make it
dual axis by right clicking and there will be different mark cards. By that 2 different field 
can be compared to make desicions such as increasing resource etc.

## Quick table calculations for ranking

A ***table calculation*** is a calculation that can be applied to the values in a visualization like
running total, difference, percent of total and many more. Table calculations are defined by
their scope and direction.

* Scope: defines the group on which  the calculation is performed.
* Direction: Difense how the table calculation moves within the scope. Options are accros, down,
down and across... 

***Quick table calculations*** are table calculations that you can apply to your visualization
in Tableau. Applied with the most typical settings for the calculations type. It is important to
know to do ranking and getting userbase metrics (Percent of total).

## Combining characteristic and quick table calculations
To calculate the rank simply place the field to the filter right click on it and click on rank.
Updating tooltips based on calculations can enhance the visualization. To add visualizations
to tooltips you can use insert > sheets.

## KPIs and time segments
To use KPIs within the tooltips on the map we need 2 different worksheets. Creating donut charts.
With donut charts segmentation and overall data can be seen.

# Groups, Sets, and Parameters

## Groups

There are many ways to slice and dice the data. Like filter and calculated fields. Grouping is 
when you combine related rows in a field. That crates consistency in the data.

## Groups for regions

To create groups on maps (like regions) we can select them and click on paperclip icon

## Creating seasonal groups
To create seasons we need date data.

## Parameters and sets

* Parameter: is a globar placeholder value such as a number, date or string that can replace a
constant value in a calculation, filter or reference line. After creation, parameter reside
in its own section of the data pane.

* Sets: define a subset of the data. When the criteria for segmentation or summarizing includes
more than 2 groups, you need to use another method such as creating a group or applying a
calculated field.

## Parameters

Parameters can be created from data pane under the create calculated field option. To connect
parameters with the viz use filters. Parameters can also be used with calculated field.

## Sets and Using data from different Datasets
Segmenting data into two. Those in the set and those out of the set. To create a set
control click and select rows and create set. To use two fields from different sources a linking
field sould be defined. Press link icon right of the field.