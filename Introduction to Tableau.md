# Introduction to Tableau
## Getting Started with Tableau
### Introduction
It makes it easy to build beautiful interactive visualizations from raw data.
* Frame business questions
* Import and clean data
* Analyze and visualize data
* Drive business decsions.
* Present insights.

### Connecting to data
To connect to a csv file navigate to text file. On top of the column names, icons indicate the data type.  Number sign for numbers, a globe for locations, or ABC for text. Tableau is good at guessing types but it can make mistakes so it is good to check them out. Worksheets, dashboards and stories can be created after selecting the data.

### Navigating Tableau

Data pane shows the data that loaded. ***The green fields are continuous in the table** , treated as on an infinite range. ***Blue fields are discrete (categorical), treated as individually separate and distinct.***

***Dimensions contain qualitative data, such as names, dates or geographical data.*** Measures contain numeric quntitative values that can be measured and aggregated such as distance or height. Dimensions and measures affect visiualizations differently. Dimesions allows segmenting data while measures can be aggregated and add quantitative values to dimensions. Segementing means grouping similar data like for each neighborhood. They can be converted to each others. 
Columns corresponds to the x axis of the view and rows to the y axis. Pages shelf lets you break a view into several pages. Filters for filtering and marks field contains marks cards and mark types. Mark cards add context and detail to the view.

### Your first visualization
To create a visiualization we need to click on the show me botton and it suggests appropriate visualization options.

### Building and Customizing Visualizations
Slice and dice data wtih filters, create new columns using calculated fields and aggregate dimensions and measures in a view. 

### Filtering and sorting
Discrete categorical data selecting values. Conditions – toop recors. Measure filters (green ones) range of calues, at leat, at most, or equals, nunll or nnon null values.


### Sorting and filtering through selection
Dragging a dimension allows us to check which values we want to see. When dragging a measure we get an option for aggregation, we can specify a range for values.

### Filtering through the filter shelf
If we select show filter we can filter them interactively. We can filter out null values by going to the special tab and selecting non-null values. Top filter for dimensions to see top values.
### Aggregation
Aggregation means gathering and summarizing data points for analytics.
### Calculated fields
Create new data from data that already exists. To create a calculated field, functions are used.

### Creating calculated fields
To create a new calculated field go to analysis tabe and go to create calculated field.

## Digging Deeper

### Mapping your data
We can create two types of maps. One of them is the filled map that the boundaries are filled  with color. A symbol map uses symbols to represent a geographic region. Tableau can automatically assign coordinates to places on the map.
### Creating a symbol map
It is relatively straighforward.
### Working with dates
Knowing what happened when is important while doing analyisis. Tableau provides a robust date hierarcy for any date field.
### Visualizing dates
Granularity is important.  The fist section makes it discrete, the second continuous.
### Reference lines, trend lines, and forecasting
Reference line is simply a line that gets drawn on a chart representing another measure or point of reference. Trend lines are used to predict the continuation of a certain trend. Forecasting is about predictiong the future value of a measure.
### Adding reference lines, trend lines, and forecasting
To add  a reference line that indicates the average, go to the analytics pane. Under custom, reference line. To learn the trend, nevigate to the analytics pane, under model there are trendline, drag it to the view, select linear. To add forecasting just drag it to the view.

## Presenting Your Data

### Best practices for formatting your visualizations
Visualizations must be usable and intuitive. A workbook is the largerst possible ‘container’ for formatting changes. Fromat from large to medium to small. Workbook > worksheet > individual parts of view.

### Use tooltips and adjust axes as necessary
The information that appears in this tooltip is an excellent helper for conveying your data story. To costumize the tooltip click tooltip in the marks card and update it. To change the axis, right click the axis, click edit axis, change tick marks. Adding title is important.	 
### Dashboards
A workbook contains sheets, a sheet can be a worksheet, a dashboard, or a story. Dashboard is a collection of several views. Data in sheets and dashboards is connected so when you modify a sheet any dashboard containing that sheet change and vice versa. Sheets and dashboards updat with the latest available data from the datasource.
### Create a dashboard
To create it open a new dashboard and drag the sheets.


### Customize your dashboard
One way of customizing your dashboard is by adding an object to it. There is a object section. Tiled and floating object worth consideration.
### Stories
Dashboards can be added to create stories. A story is a sheet so the methods that is used to create and manage worksheets and dashboards also apply to stories. A story is also a collection of sheets. Since dashboards are sheets a story can be a collection of dashboards.
### Create a story
A story is a squence of visualizations. To add sheets just double click them.
### Customize 
It's not enough to combine dashboards into a story. You need to make sure to add some documentation so a viewer can follow your story.
