
# Combining and Saving Data

Combining data from different sources using joins, unions and relationships. 

## Combining data tables

Unions and joins are the common ways to combine data. Union is a way to stack data vertically.
The data should contain the same structure. To combine tables where there is a relationship
between the table a join may be better. There are different ways of you can join tables. Inner,
left, right, full.

## Unioning tables

To union multiple datasheets drag the data and click open. Drag the other data below it.
Afterwards you can edit union. After that you can rename the whole data.

## Joining tables

Dragging another data within the dialogue box creates a join if you drag it out of it, it creates
a relationship. After dragging it you can choose the type of join you want. Tableau can guess
where to join tables on. But you can change it if you want.


## Relationships

It is a another way to combine data. A relationship describes how two tables relate to each other,
based on common fields, but does not merge the tables together or append fields. When a relationship
is created the tables remain seperate. Relationships has no join types. Relationships dynamically
change the join types depending on the fields being used in the visualization. Relationships enable
you to preserve all the detailed records of multiple tables in a single data source.

## Establishing a relationship

Drag the csv file you will build a relationship with.

## Extracts

The work can be saved as packaged workbook (.twbx), it is a workbook that supports files including
the data source and images. Plain workbook (.twb) doesn't contain dataset but it is a good option to 
keep the file size low. Then there are ***extracts*** that can be identified with the .hyper or .tde.
Extracts are the local copy of parts or all of the data. Data source (.tds) files contain information
on how to connect to the data source and any modification done to the data like calculated fields and 
groups.

Extracts improve performence while saving, loading and interacting with data. They support very large
datasets(billions rows of data.). You souldn't try to save a packaged workbook with that much data. 
If a real-time data is important a live connection is a better choice, since an extract requires a refresh.
Extract enable fast offline work.

## Creating extracts


# Managing and Connecting Data

## Data properties
Managing data is important. Setting columns names and data type is important to get the correct
visualizations.
* Dimensions: Qualitative valeues like names, dates, geographical data.

* Measures: Numeric/quantitative values like price, duration, age

A common example of a column that might need an adjustment would be a numeric value that is an
ID. It should be in the dimensions section instead. 

There are 7 data types in tableau. String, integer, date values, date and time values, boolean
values, geographic values, cluster or mixed values.

## Managing the presentation of data
To change the field property simply drag them to the desired section (dimension or measures). To
create aliases righ click on them click on aliases... You can select the desired colors from 
default properties. To change the number format go to the number format... Also there are lots of
date formats.

## More data management

To give a field a geogrephic role right click on it and assign an geographic role. To create a
hierarchy (like country, state, city) right click and navigate to hierarchy or drag one of them to the top
of another one. Arrange them big to small. By creating hierarchy you can add more ditails or hide some by
clicking plus and minus. You can set the default aggregation of a field by right clicking.

## Tableau connectors

Tableau server, file (exel or pdf), server (SQL server, mySQL), after connecting to data Saved date source.
Once the model is created and data is filtered, sharing this state of the data can be accomplished through
saving it as a data source generates a file with a tds extension. Data source files do not contain the actual
data but rather the information necessary to connect to the actual data as well as any modifications.

## Filters
Order of filters: Extract filters > data source filters > context filters > dimension filters > measure 
filters > table calculation filters.

## Tableau filters
To filter the data navigate to data and  click on data source filters. To set the filter order you can 
create a context filter by right clicking on the field in the filters section. Tableau consider context
filters first. Both dimension and measure fields can be used as filters.

