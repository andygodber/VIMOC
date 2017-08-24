![VIMOC](https://github.com/buglabs/VIMOC/raw/master/files/pictures/VIMOC.PNG)

# Documentation for VIMOC freeboard widgets. 

Official Phase 1 freeboard dashboard can be found here:
https://freeboard.io/board/HxhPkU

## Using the dashboard

![VIMOC Line Graph](https://github.com/buglabs/VIMOC/raw/master/files/pictures/VIMOClinegraph2.PNG)

### Maps

The maps represent the location of the entire array, as well as examples of a few individual sensor locations. These maps are not clickable, and will be combined into a single clickable map in Phase 2.  For now, we wanted to let you see options and examples.

### Sensor Graph Tools

The Graph tools are dropdown selectors that allow you to choose all or individual sensors for visualization.

After selecting which sensor to visualize, the user can further refine the graph by choosing to view all directions, in only, or the outdirection.

### Graph Date Range

The Date Range tool allows the user to select specific dates, as well as API query times, in order to produce a meaningful graph.

### Site Traffic Flow

The Custom line graph uses the D3.js library, which allows us the flexibility to further customize this graph for all VIMOC projects.  Bug Labs built this line graph from scratch, instead of using a charting library, so that it can be customized to specific user requirements.

D3 uses SVG, HMTL5 and CSS standards, and is implemented in hundreds of thousands of websites.

#### Legend

Within the custom VIMOC Line graph is a legend to show direction (North, South, East, West).  This allows visualizing and filtering by both the direction (in/out) AND the orientation (N/S/E/W).  This is an added benefit of the D3 library.

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



![BUG_logo_RGB](https://github.com/buglabs/VIMOC/raw/master/files/pictures/BUG_logo_RGB.PNG)
