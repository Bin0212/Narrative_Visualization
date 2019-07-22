# [2016 US Flight Departure Delay Visualization](https://ivyieng.github.io/final/flights)

# About this Visualization
This visualization follows the **interactive slideshow** narrative visualization structure. The slideshow structural layout was constructed using [reveal.js](http://lab.hakim.se/reveal-js) and all the charts were written using D3.js embedded in the slides as iframes.

## Scenes
There are 5 main scenes between the opening and ending scene. Each scene consists of a single chart and description.

## Annotations
**Tooltips** - The tooltips in all charts follow the same CSS template to support visual consistency.

**Annotations** 
Annotations in this visualization follows the same CSS template for font and line style. Annotations are available in pie chart, bar chart, heatmap, and map.

- Bar chart annotations - For the "Average Departure Delay" bar charts in Scene 2 and 4, the average line will be cleared when users switch to the other bar chart.

- Map annotations - The annotations for low and high delay airports will only be displayed when the responsible option is checked.

## Parameters
**Slide number** - The slide numbers are shown in the bottom right corner of each slide. The previous, current, and next slide title are shown in the bottom left, center, and right respectively.

**Bar chart parameters** - The bar charts on Scene 2 and 4 contain 2 input parameters controlled by radio buttons. User can select to see the figures of average departure delay or the total number of flights.

**Map filter parameters** - The map on Scene 5-1 shows all the US airports by default. The checkboxes can let users filter the airports by 3 different levels of delay on the map.

## Triggers
**Slide navigation controls** - The navigation can be controlled by keyboard arrow keys, mouse scroll wheel, and by pressing the "<" and ">" button in the bottom right corner of each slide.

**Tooltips** - The tooltips in all the charts are triggered by mouseover event on chart elements.

**Bar chart selection** - The 2 radio buttons on Scene 2 and 4 allow users to select and view different set of figures in the bar chart.

**Map filter** - The 3 checkboxes on Scene 5-1 allow users to filter the airports by 3 different levels of delay.

**Button and hyperlinks** - The button and hyperlinks in the opening and closing scenes are triggers for showing external resources

## User Interface Events
**Mouse click** - User interacts by clicking on buttons, hyperlinks, slide navigation controls, check boxes, radiobuttons.

**Mouse hover** - User triggers tooltips on chart elements by mouseover events


## Credits
- [D3.js](https://d3js.org/)
- [reveal.js](http://lab.hakim.se/reveal-js) 
- Heatmap inspired by [Tom May](http://bl.ocks.org/tjdecke/5558084), see [license](/license/heatmap-license.txt).

## Data Source
[Bureau of Transport Statistics (BTS) - On-Time Performance dataset](https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236&DB_Short_Name=On-Time)

## Author
Manieng Ivy Lao 
([mlao2@illinois.edu](mlao2@illinois.edu))
