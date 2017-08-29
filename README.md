![VIMOC](https://github.com/buglabs/VIMOC/raw/master/files/pictures/VIMOC.PNG)

# Documentation for VIMOC freeboard widgets. 

Official Phase 1 freeboard dashboard can be found here:
https://freeboard.io/board/PhF6lU

## Using the dashboard

![VIMOC Line Graph](https://github.com/buglabs/VIMOC/raw/master/files/pictures/VIMOClinegraph3.png)

### Maps

The maps represent the location of the entire array, as well as examples of a few individual sensor locations. These maps are not clickable, and will be combined into a single clickable map in Phase 2.  The maps are meant to be viewed as examples.

### Graph Tools 

The graph tools allow you to visualize specific sensors for any valid date range.   By default, the filters will be set to  show "ALL" sensors.

#### Sensor and Direction Filters

The dropdown selectors allow you to specify individual sensors and/or directions (in/out) for visualization(e.g.). 

![SingleSensor](https://github.com/buglabs/VIMOC/blob/master/files/pictures/SingleSensor.PNG)

#### Date Range

The Date Range tool allows the user to select specific dates, as well as API query times, in order to produce a meaningful graph.

### Site Traffic Flow

The Custom line graph uses the D3.js framework, which allows us the flexibility to further customize this graph for all VIMOC projects.  Bug Labs built this line graph from scratch, instead of using a charting library, so that it can be customized to specific user requirements.

#### Using The Line Graph

Bug Labs added subtle tool tips and user actions to get the most out of the new line widget.

##### Double Click

By default, all sensors are chosen for the selected date range. The user can double click on any sensor button on the top of the chart to turn all other lines off, except the double-clicked line(e.g.).

![DoubleClick](https://github.com/buglabs/VIMOC/blob/master/files/pictures/DoubleClick.PNG)

The user can then single click the same button to turn them all back on. Separately, the user can select any other sensor, to compare two or more sensors to each other(e.g.).

![SidebySide](https://github.com/buglabs/VIMOC/blob/master/files/pictures/SidebySide.PNG)

##### Legend

Within the custom VIMOC Line graph is a legend to show details for all visualized sensors.  Upon hover, the legend will identify all visualized lines, by color, present the time stamp, as well as the individual sensor details.

Further, when the user hovers over a specific point on any line, the legend will highlight that individual sensor within the legend(e.g.).

![LegendHover](https://github.com/buglabs/VIMOC/blob/master/files/pictures/LegendHover.PNG)

## Custom elements of the dashboard

Below are the individaul elements used for this Phase 1 deliverable:

[Map widget](https://www.dropbox.com/s/ttnektk5v7ddpax/vimocMap.js?dl=1)

Place holder for now, this widget shows the UCLA sensor location.

[Date Picker](https://www.dropbox.com/s/jiiik5ypdeqobgc/datetimepicker_widget.js?dl=1)

Custom Data/Time chooser allows the user to select the date and specific time to view historical data.

[Dropdown Selector](https://www.dropbox.com/s/q6eqjn4t645tehg/dropdown_command_small.js?dl=1)

This dropdown selector is also a placeholder, and allows the user to choose all data, or specific sensor data.

[VIMOC Line Chart](https://www.dropbox.com/s/uf704syow20tvm5/vimocChartDer.js?dl=1)

Custom line chart that allows re-use for all future VIMOC projects.  Bug Labs will further customize per end user specifications.

[VIMOC Datasource](https://www.dropbox.com/s/3xh7geybvvsb1a3/vimocDatasource.js?dl=1)

The VIMOC datasource connects to the VIMOC API to return requested historical data.



![BUG_logo_gif](https://github.com/buglabs/VIMOC/blob/master/files/pictures/BUG_logo_gif.gif)
